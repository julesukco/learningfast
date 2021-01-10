+++
categories = ["Development", "Web", "API"]
date = 2021-01-09T07:00:00Z
draft = true
subtitle = "Creating a UI with data from APIs - easily, with no code"
tags = []
title = "Simple Web UI"
[banner]
src = ""

+++
After a sprint demo from the teams, had an idea to hit some web APIs and display the status of a complex orchestration engine in an exec dashboard. Started by thinking about using Python scripting - then decided to find a no-code web tool instead. All I needed was something I can run on my local machine and hit internal apis. Therefore deploying the app to a server would not be an option due to connectivity issues.

Options looked at:

* backendless - signed up, no clue how to use it. abandoned
* fluid - web and a native mac app. looks promising - good for UI (mobile and web) mockups, but can't call out to an api
* parabola - calls APIs, automation workflow, no presentation

Nothing really doing what I need so far.

Found a React js dev site called codesandbox.io that may be of use as it runs solely as a .HTML page.