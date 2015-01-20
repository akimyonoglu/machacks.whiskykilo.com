---
layout: page
title: "Notification Center"
category: hacks
date: 2015-01-19 15:34:49
order: 6
---

#### Disable Notification Center

For me, I consider Notification Center a waste of precious menu bar space. It's limited enough on my MacBook Pro, without wasting all those pixels for something I never use.

{% highlight bash %}
launchctl unload -w /System/Library/LaunchAgents/com.apple.notificationcenterui.plist
{% endhighlight %}
