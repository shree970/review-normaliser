# 5* Review normaliser

Always a relevant XKCD

![xkcd](https://github.com/shree970/review-normaliser/blob/main/images/xkcd.png) 

There is very well know issue with 5 star review systems, better visually discribed as J distribution.

![j-shaped](https://github.com/shree970/review-normaliser/blob/main/images/j.png)

In other words, there is a small spike in extremely negative reviews (★), almost nothing in the middle (★★, ★★★ and ★★★★) and a large spike in positive reviews (★★★★★). This is counter-intuitive, and not ideal — given the option of 5 ratings, one would expect a range of opinions on a given item that don’t cluster to the extremes. 

This does not reflect the genral view of audience and is driven by biases.

Therefore a 'Normal' distribution is more preferred, and is inherently natural.

![gaussian-shaped](https://github.com/shree970/review-normaliser/blob/main/images/normal.png)

In this project, we try to make a tool bar that automaticaly calculates the "Normalness" of reviews.