---
layout: post
title: Easy Self Tracking 
---

[Example](http://lifehacker.com/how-to-track-everything-in-your-life-without-going-craz-1466537828) of using Google docs forms for self tracking. I made my own form though, which was trivially easy, just go to docs.google.com/forms and follow the gui. I set up a cron job on the Rondo frontend that should execute at 8am every morning sending me an email with a link to the form. I seem to remember emails from cron on Rondo coming at odd times, so I'll have to watch out for that. I checked into that, and found that I couldn't get Rondo to send emails to my gmail at all (maybe they'll all arrive at once later?). It sends instantly to my princeton email, so I just sent the link to that address for now.
