---
layout: post
title:  "🗓 Weekly Round Up 25th May 2020"
subtitle: "Everything that was added this week."
author: "Richard Stelling"
---

This week was release week, [alpha 4](https://github.com/Impedimenta/Suitcase/releases/tag/1.0.0-alpha.4) included, Token Replacement in Parameter Arguments, `--compatibleVersion` Argument and Interpreter Mode 🥳.

From the release notes,

> Suitcase can now be called from a script in a similar way to bash or python. Just start you script with this hash-bang,
>
> ```bash
> #! /usr/local/bin/Suitcase interpreter
> ```
>
> All arguments need to be on a single line and it supports comments using #.
> 
> Here is the YouTube-DL Example using interpreter mode,
> 
> ```bash
> #! /usr/local/bin/Suitcase interpreter
> 
> # Drag and drop URLs to the floating window
> # and download the embedded video stream using
> # `youtube-dl`. 
> 
> # Application 
> --name="Download YouTube" 
> --window-floating # The window will be infront of all others
> 
> # Dropped URL Control
> --control-type="dropped-urls-label" 
> --control-title="## Drop Your URLs Here! ##" 
> 
> # Download Button & Action
> --control-title="Download" 
>   --control-type="button" 
>   --control-action="/usr/local/bin/youtube-dl"
>   --control-action-parameter="-o,~/Downloads/video.mp4,SUITCASE_DROPPED_URLS"
>```
>

Suitcase was also [featured](https://twitter.com/rjstelling/status/1266352165234319360) in a thread of retweets by [Steve Troughton-Smith](https://twitter.com/stroughtonsmith). The [entire thread](https://twitter.com/stroughtonsmith/status/1266058437374476293) is a fantastic read with some amazing projects. 
