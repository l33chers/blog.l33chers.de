+++
title = "Deleted"
date = "2026-01-09T18:01:33+01:00"
author = "m4j0rl33cher"
authorTwitter = "" #do not include @
cover = ""
coverCaption = ""
tags = ["forensics", "uscybergames", "ucg" ]
keywords = ["ucg", "autopsy"]
description = ""
showFullContent = false
readingTime = false
hideComments = false
color = "" #color from the theme settings
+++

Challenge text:

One of the US Cyber Games administrators deleted a File that they need for the season 5 that they need to give to Brad. Recover the deleted file from the image and provide us with the flag for this file that Brad and Jessica paid a Graphic Artist to create.

Solution:

Open the disk image in Autopsy and search for deleted files and extract the deleted image - it's the flag:

![](/images/ucgVdeletedflag.jpg)
