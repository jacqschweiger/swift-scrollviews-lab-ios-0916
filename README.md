# ScrollView Fun

![BingBong](http://i.imgur.com/J3e7N2Y.jpg?1)  

> Take her to the moon for me. Okay? -[Bing Bong](http://disney.wikia.com/wiki/Bing_Bong)
 

## Learning Objectives

* Create a `UIScrollView` in Storyboard
* Properly constrain the `UIScrollView` to the `UIView`
* Create a `UIStackView` in Storyboard
* Properly constrain the `UIStackView` in the `UIScrollView` to allow for horizontal scrolling


## Instructions

*  Included in this Xcode project is the following images:

![movie](http://i.imgur.com/sfAd9md.jpg?1)

* It is **your** job to create an app that can scroll from left to right (in a page-like manner) through these various characters. Each image (while displayed) should take up the full width & height of the iPhone.

---
* In Storyboard, create a `UIScrollView` and constrain it to the edges of the `View`.
* In Storyboard, create a `UIStackView`, we want to be able to scroll horizontally.. so which one do you think we should choose? Our options are Horizontal or Vertical. Even if you feel you chose the wrong one, you can change it from Horiztonal <--> Vertical in the attributes inspector:

![attributes](http://i.imgur.com/dtfnpZ9.png?1)

* Before we move any further. I mentioned that this app should let us scroll from left to right in a page-like manner. Is there a property we're forgetting to set in the Attributes Inspector on our `UIScrollView`?
* How should we constrain the `UIStackView`? At this stage, you can make an attempt yourself to see if you can figure it out all by your lonesome or you can continue reading. I recommend making an attempt yourself and *failing* at it.. or possibly **succeeding**! It's hard to test this though without having any images.

----

* Skip this section if you made an attempt at producing the constraints for the `UIStackView` yourself.


<a href='https://learn.co/lessons/ScrollViews' data-visibility='hidden'>View this lesson on Learn.co</a>
