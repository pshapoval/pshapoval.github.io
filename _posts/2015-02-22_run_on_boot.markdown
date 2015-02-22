---
layout: post
title:  "Running script on startup"
date:   2015-02-22 23:43:00
categories: Ububtu crontab
---

Run your script on every system boot it's easy
<!--more-->
Use crontab
```
crontab -e
```
Then add following rule and save it
```
@reboot /path/to/your/script
```
