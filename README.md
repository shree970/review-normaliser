# 5* Review normaliser

Always a relevant XKCD

![xkcd](https://github.com/shree970/review-normaliser/blob/main/images/xkcd.png) 

There is very well know issue with 5 star review systems, better visually discribed as J distribution.

![j-shaped](https://github.com/shree970/review-normaliser/blob/main/images/j.png)

In other words, there is a small spike in extremely negative reviews (★), almost nothing in the middle (★★, ★★★ and ★★★★) and a large spike in positive reviews (★★★★★). This is counter-intuitive, and not ideal — given the option of 5 ratings, one would expect a range of opinions on a given item that don’t cluster to the extremes. 

This does not reflect the genral view of audience and is driven by biases.

Therefore a 'Normal' distribution is more preferred, and is inherently natural.

![gaussian-shaped](https://github.com/shree970/review-normaliser/blob/main/images/normal.png)

In this project, we try to make a tool bar that automaticaly scores the "Normalness" of reviews.  

References: 

[The Problem of J-Curves (in Online Ratings Systems)](https://levelup.gitconnected.com/the-problem-of-j-curves-in-online-ratings-systems-caf94fab4819)

[The Problem with 5 Star Rating Methods](https://teamhively.com/638-the-problem-with-5-star-rating-methods)

[http://www.lifewithalacrity.com/2006/08/using_5star_rat.html](http://www.lifewithalacrity.com/2006/08/using_5star_rat.html)
[This paper](https://www.researchgate.net/publication/228604596_Why_Do_Online_Product_Reviews_Have_a_J-Shaped_Distribution_Overcoming_Biases_in_Online_Word-of-Mouth_Communication )