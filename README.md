Track Work Time
===============

This app can track your work time easily! It lets you categorize each recorded interval by a client/task and a free text. Of course, the list of clients/tasks can be edited to suit your needs.

Additionally, if you wish, your flexible time account is taken care of: you always see how much you worked. You can also keep an eye on how much work time is left for today (by a notification which you can enable).

You even may provide the geo-coordinates of your work place and the app can automatically clock you in while you are at work. This is done without using GPS, so your battery won't be emptied by this app.

If you prefer to use other apps like Llama or Tasker for tracking your movements, that's fine - TWT can be triggered from these apps and just do the book-keeping of your work time. In this case, you have to create broadcast intents called org.zephyrsoft.trackworktime.ClockIn or org.zephyrsoft.trackworktime.ClockOut. When using ClockIn, you can also set the parameters task=... and text=... in the "extra" section of the intent so your events are more meaningful. For more details on this, see the web site.

Otherwise you may provide a visible ssid at your work place the app can use to clock in automatically when this ssid is in range (you don't need to be connected to this network). In this case you should enable wifi-radio manually.

Finally, the app can generate reports for you. The raw events report is the right thing if you want to import your data somewhere else, while year/month/week reports are fine if you want to keep track of your task progress.

**This is an open source project**, so if there is something you don't like, you are very welcome to contact me or even write some code yourself and contribute it. Please don't try to communicate with me via reviews, that doesn't work in both directions. Just write me an email, and I'll see what I can do - web site and email address as stated above.

Important note: This app definitely won't send your personal data anywhere. It uses the INTERNET permission only to send crash reports, but those reports contain neither any times nor any coordinates you may have tracked.