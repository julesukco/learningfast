+++
categories = []
date = 2021-02-01T07:00:00Z
draft = true
subtitle = ""
tags = []
title = "JavaScript API Page"
[banner]
src = ""

+++
Trials and tribulations of getting a web page to call APIs - and the dreaded CORS error

Chromium - disable-web-security. For my internal use only web site, this is the way to go. There were some plug-ins that claimed to help solve this in Chrome. I tried but they did not seem to help at all. Did find I had to start up the Chromium app from a terminal window to get it to properly work.

The overall result was a very slick app that was impressive. Coding was light once things were working. It did end up being a bit of a procedural monster and will be hard to maintain over time. May need to get really aggressive in the refactoring to keep it clean.