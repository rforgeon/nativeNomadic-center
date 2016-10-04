---
layout: post
title: CoWorking
thumbnail-path: "https://cldup.com/KlE-6j6pu7.png"
short-description: Hourly co-working rental platform.

---

{:.center}
![]({{ site.baseurl }}https://cldup.com/KlE-6j6pu7.png)

## Explanation

nativeNomadic was my first attempt at a Ruby on Rails app. The goal was to create an MVP platform for independent coworking spaces. The platform allows these independent coworking spaces to put up their extra space at an hourly rate.

## Problem

My biggest problem was figuring out how to create a sophisticated platform that allows for uploading locations and transferring money between two parties - while taking a small cut.

This MVP became possible once I found the resource [Base Rails](https://www.baserails.com/#course). Base Rails allowed me to quickly get a better handle on RoR and build off the course to form my own platform.

## Solution

Base Rails helped me establish a peer to peer platform, however, the example was for a Etsy look-a-like. I refactored this example to include Google's map API and time sessions that would decrement a user's purchased credit (using Stripe) at an hourly rate. When clicking "Start Session," you are taken to a form to enter your entry time and exit time.

{:.center}
![]({{ example }}https://cldup.com/fQwrk7FLZQ.png)

## Results

I got one coworking space signed up, located at the Palace of Fine Arts in San Francisco. However, after about a month of being on the platform, the management decided to close the coworking space and focus on renting out for events full time.

In this time, I didn't market the platform drastically, however, from what I managed (one Facebook ad and some Instagram followers) I never had someone book the space through my platform. I chalk this mostly up to awareness. The hourly rate was $4/hour.

## Conclusion

After showing my app to a product manager at DoorDash, he claimed that he liked how I'd set it up, but was concerned that there was only one location on the platform.

"To drive people to this, you need options. People will only be interested and come back if they know they have more of a selection."

My next goal for nativeNomadic CoWorking is to to implement a hack to get the "fly wheel" going to provide more options.

I'm excited to add this new hack and I'll keep you updated on it's implementation 🔜
