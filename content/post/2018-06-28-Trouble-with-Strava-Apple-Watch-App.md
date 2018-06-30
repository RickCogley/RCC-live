+++
date = 2018-06-29T12:00:31+09:00
title = "Having Trouble With Strava Apple Watch App?"
slug = "trouble-with-strava-apple-watch-app"
tags = ["apple watch", "healthfit", "bug", "watchos", "ios", "fitness", "exercise", "calibration", "strava"]
draft = "false"
+++

Are you having trouble with the Strava Apple Watch app not picking up your heartrate or GPS data? Read on for one way to opt out of this buggy situation...

<!--more-->

I love my Apple Watch, and it has really prompted me to live a more healthy life. That's great. I'm also a long time Strava Premium user, so if possible, I wanted to use the Strava Apple Watch App directly. 

That hasn't worked. 

Apparently, this situation where Strava's Apple Watch App "forgets" its settings and needs to be reinstalled, is pretty common. It's not just me. The reinstall process is pretty involved, and it ends up you need to take many steps to purge the app from your iPhone and Apple Watch. After three rounds of this crap and noticing how silent Strava have been answering the cries of users with this same problem, I started looking for an alternative. 

## Enter HealthFit

Thank all good fortune for Stephane Lizeray and their [HealthFit](https://itunes.apple.com/us/app/healthfit/id1202650514?mt=8) app. HealthFit is an app that is designed with one thing in mind: **exporting your workouts**. That is, it exports the workouts you track from your Apple Watch's standard "[Workouts](https://support.apple.com/en-us/HT204523)" app, to various services, either directly or via "Flexible & Interoperable File Transfer" ([FIT](https://www.thisisant.com/developer/resources/tech-faq/category/153/)) protocol files. 

This is what the Apple AppStore page has to say about HealthFit: 

> _HealthFit exports automatically in background your workouts from Apple Watch as FIT files, a popular open format supported by all the major fitness platforms, such as Garmin Connect, Strava, TrainingPeaks, Final Surge, Selfloop, Smashrun, RunKeeper, MapMyFitness, MapMyRun, MapMyBike, Ride with GPS, Cycling Analytics, Today's Plan, Runalyze..._

How it works is, you just use the usual Apple Watch _Workouts_ app, and when you save your activity, HealthFit will sync to the apps you have connected. In my case, I want to use Strava and Garmin Connect, so I set up a direct connection to Strava, and am also dropping the FIT files into Dropbox. That means, I can import those into Garmin Connect as well. 

I assume there is some functionality I will lose by _not_ using the Strava app on my Apple Watch, but, there's just no excuse for software that's as buggy as Strava is on Apple Watch. 

The AppStore page has detailed notes you should read, but I'll summarize a couple of points. HealthFit: 

* can sync your exercise data such as distance, pace, GPS route, running or swimming cadence, laps, splits, segments and so on. 
* can sync your health data like Resting Heart Rate (RHR), Heart Rate Variability (HRV), Active Calories, Sleep Analysis, Steps count, Body Weight, BMI, Fat percentage, Oxygen Saturation, Blood Glucose, Blood Pressure, Insulin Delivery, Menstruation, Water Consumption. 
* lets you export all your workouts into FIT files in a `HealthFit` folder in Dropbox or iCloud Drive.
* can send workouts by email. 
* lets you filter your workouts by source and workout types. 

## But First, Calibrate Your Apple Watch

My excitement about this new world order was quickly tamped down after I discovered that my sweaty 30-minute walk this AM registered as a paltry 5 minutes of active exercise. What the what?!

Some digging around led me to [this page](https://support.apple.com/en-us/ht204516) from Apple. The bottom line is, I had to re-calibrate my Apple Watch to make sure it properly detects exercise, as, um, exercise. It appears you're supposed to do this when you get your Apple Watch. I hadn't. Here's how to do it: 

* Pick an area that you can walk or run uninterrupted for 20 min, in a "flat, open outdoor area that offers good GPS reception and clear skies". 
* Before your calibration workout, in the iPhone Watch app, My Watch tab, go to Privacy > Motion and Fitness > Reset Calibration Data.
* Restart your Apple Watch and iPhone for good measure.  
* On the Apple Watch, Workouts app, select "Outdoor Walk" (or Run), tap the elipsis icon, set the time to 20 min. 
* Start, and maintain a consistent & typical pace. 

Once I did those steps, I got 20 exercise minutes out of a 20 minute calibration walk. We'll see what happens now, for normal walks with a bit of stopping at traffic lights and so on. 

## HealthFit Syncs and Syncs Well

The idea of HealthFit and its core concept of simply doing a great job of syncing your health and fitness data, to me follows the [unix philosophy](http://www.linfo.org/unix_philosophy.html) of application programs that "do one thing well". I get the feeling it is probably made by a small shop (after all, it's listed under an individual's name in the App Store), and I'm grateful that they decided to scratch this itch. 

Sometimes, quality software's a labor of love, rather than the product of a big team. 

_Kudos Stephane Lizeray_.

## Updates

* 20180630 - it still works on day 2. If I don't walk as fast as I did when calibrating, the "heat map" is more orange than green. This is expected. 

:watch: :bug: :running: :heart: :pray:


