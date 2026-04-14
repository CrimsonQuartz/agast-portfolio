+++
title = "First Post"
date = "2026-04-14T04:16:50-05:00"
#dateFormat = "2006-01-02" # This value can be configured for per-post date formatting
author = ""
authorTwitter = "" #do not include @
cover = ""
tags = ["", ""]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
+++


# Creating this site

I've always wanted to have my own site, now here I am, procrastinating a homework assignment by researching topics beyond what my class is teaching lol. Welcome to **agast.net**

Heres a short little write-up for practice & documentation

## Tools & Sites Used

> [Hugo](https://gohugo.io/) : Framework for website

> [Cloudflare Pages](https://pages.cloudflare.com/) : Website deployment

> [GitHub](https://github.com/CrimsonQuartz/agast-portfolio) / Git : Repo storage, and git to push updates

> [panr's terminal theme for hugo](https://github.com/panr/hugo-theme-terminal?tab=readme-ov-file)

## Setup steps

First I used my extremely basic html knowledge to make a temporary site to test deploying websites via github into cloudflare.

Then, I began researching different ways to make a custom site thats pretty to look at. After awhile, I decided to go with Hugo, as it seemed to be something "easy-to-learn, 
hard-to-master" - Perfect for someone like me who is constantly learning.

Commence serveral hours of making changes, breaking stuff, consulting documentation (and a little help from claude)...........

## Lessons Learned

The biggest issue I ran into was initially I was making edits to /themes/terminal 

This would make changes to design layouts and colors on my locally ran dev-instance, but once I committed & pushed the changes, the prod-instance did not change. 
I finally figured it out - the sites source was pulling the /themes/terminal from Panr's master repo, overwritting any of my changes in prod. To fix this, I instead did the proper placement of /static.

## Whats next

Lots!

I still need to add different programming projects I've done for classes these last few years, some more write-ups, adding more information about me, and more!

Stay tuned for more changes

-Andrew Gast
