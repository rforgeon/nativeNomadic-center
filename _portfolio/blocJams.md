---
layout: post
title: Bloc Jams
thumbnail-path: "https://cldup.com/44XaNm1bzZ.png"
short-description: Web-App Music Player.

---

{:.center}
![]({{ site.baseurl }}https://cldup.com/44XaNm1bzZ.png)

## Explanation

This app was an assignment for my bootcamp - [Bloc](https://www.bloc.io).

## Problem

I used this assignment to first implement plain vanilla javascript and DOM manipulation. From there, my assignment was to refactor the app with jQuery.

## Solution

This assignment was a great way to understand the basis of jQuery and use of javascript to manipulate HTML/CSS.


## Results

I now have a better understanding of javascript and jQuery. Their uses and respective advantages.

When comparing vanilla 🍦 JavaScript to jQuery, there are both advantages and disadvantages to each. On one hand, jQuery provides clean, concise code that gets the job done. Here is an example snippet:

🍦JavaScript:
```javascript
var c = document.getElementsByClassName("comment");
```
jQuery:
```javascript
var c = $(".comment");
```
However, in this instance, jQuery is almost [60x slower](https://www.sitepoint.com/jquery-vs-raw-javascript-1-dom-forms/). This comes at the price of a bit cleaner code.

A great way to increase performance is by using 🍦JavaScript's modern API's such as document.querySelectorAll. Using this API will require you to check for older browsers as described by [Chris Ferdinandi](https://gomakethings.com/ditching-jquery-for-vanilla-js/). However, for an application with limited backwards compatibility, Chris, recommends 🍦JavaScript's modern API's over jQuery.

## Conclusion

I've learned a ton about javascript and jQuery through this project. I look forward to further refactor the app to include [redux](https://github.com/reactjs/redux) architecture and implement [React](https://facebook.github.io/react/).  
