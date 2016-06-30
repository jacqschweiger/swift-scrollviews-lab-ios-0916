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
* In Storyboard, create a `UIStackView`, we want to be able to scroll horizontally.. so which one do you think we should choose? Our options are Horizontal or Vertical. Even if you feel you chose the wrong one, you can change it from Horizontal <--> Vertical in the attributes inspector:

![attributes](http://i.imgur.com/dtfnpZ9.png?1)

* Before we move any further. I mentioned that this app should let us scroll from left to right in a page-like manner. Is there a property we're forgetting to set in the Attributes Inspector on our `UIScrollView`?
* How should we constrain the `UIStackView`? At this stage, you can make an attempt yourself to see if you can figure it out all by your lonesome or you can continue reading. I recommend making an attempt yourself and *failing* at it.. or possibly **succeeding**!

----

* Skip this section if you made an attempt at producing the constraints for the `UIStackView` yourself.
* First you need to constrain the `UIStackView` to the edges of its parent view. Its parent view is the `UIScrollView`.
* Against what feels normal for you when making constraints, we need to set a _Height_ & _Width_ constraint on the `UIStackView`. Think of the `UIScrollView` as a fixed window that we're peering into it and its content (its content being the `UIStackView`) is what's inside that window. That content can be larger than the window, we can move the window from side to side and while it's moving we can only see what's visible through the window.

![appleKid](http://i.imgur.com/RjWzoO3.jpg?1)

* This image is a better representation of the prior bullet point. The black box is the `UIScrollView` and the photo of the boy is the content. We can move the window around to view the content.
* So all of that out of the way, we setup our window `UIScrollView` (sticking with the analogy) to be constrained to the `View`. We need to set the _height_ & _width_ of this `UIStackView`, which in this analogy is the photo of this boy.
* The height should be set to equal the height of the `View`. This is so we can't scroll up & down, we only want to scroll left and right.
* We have 5 photos we need to add to this `UIStackView`, what should the width of this `UIStackView` be set to? In setting up the width constraint equal to the `View`, you should set the multiplier equal to something other than 1.
* It might be hard to guess exactly how your `UIStackView` should be laid out, but make an attempt at setting the correct attributes before adding the `UIImageView`'s below. It might be hard to guess right the first time.. but don't just guess. Make an attempt to think through what you're setting here.

![stackAttributes](http://i.imgur.com/D6grpTZ.png)

---

* Add five(5) `UIImageView`'s to your `UIStackView`
* Set a separate image into each `UIImageView`. The images are included in the project for you.
* `UIImageView`'s has a property which dictates how the `UIImage` will fill within its space, mess around with the various options to see what looks best.

![imageViewOptions](http://i.imgur.com/ZKVSCFA.png)

* There are other options as well on `UIImageView`. The `UIImageView` acts like the picture frame to your `UIImage`. This can help you out in a situation where you might see some images bleeding over its frame (picture frame). Mess around here to see how you can fix that problem:

![moreOptions](http://i.imgur.com/pyjC0dC.png)

---

* Word of advice when working with `UIScrollView`'s. Run and run often.

![yay](https://media.giphy.com/media/12d19apJyRsmA/giphy.gif)



<a href='https://learn.co/lessons/ScrollViews' data-visibility='hidden'>View this lesson on Learn.co</a>
