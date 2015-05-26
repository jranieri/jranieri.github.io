---
layout:     page
title:      "How to link an Ipython notebook and a presentation on a static blog made with Jekyll"
date:       2015-05-07 1:42:00
category: article
---

Here the target is to keep everything as light as possible. 

My plan is to use notebooks for all the notes relating to research: it will make me improve my Python skills and will make the reading very interactive. I tried various systems for the conversion of an Ipython notebook to either markdown or HTML but all of them crash very soon with the CSS of the blog. In any case, you will loose the interactivity with the conversion.

Thus, I decided to go for the ultra-lazy-but-efficient solution: include the notebooks by a link to the nbviewer. The code snippet follows:
{% highlight html%}
<a href="http://nbviewer.ipython.org/url/URL_OF_THE_NOTEBOOK">Ipython Notebook</a>
{% endhighlight %}

For example: <a href="http://nbviewer.ipython.org/url/raw.githubusercontent.com/jranieri/jranieri.github.io/master/_notebooks/Untitled.ipynb">Check this example!</a>.
Unfortunately, we need to go to the NBviewer server and we cannot interact directly with the notebook here. The advantage is the simplicity. Moreover, we keep the notebook in the same github repository (ease of upload and versioning). 

<hr>

The second thing I want to discuss is the integration of slide presentations inside the blog. After looking around, I believe that the best options in terms of simplicity and usability is to host the presentations on Slideshare. After uploading them, it is sufficient to use the embed code, that looks like:
{% highlight html%}
<iframe src="https://www.slideshare.net/slideshow/embed_code/key/KWOI2RV5FbuAMI" width="476" height="400" frameborder="0" marginwidth="0" marginheight="0" scrolling="no"></iframe>
{% endhighlight %}

The result is a very nice box that allows the user to move between the slides: 

<iframe src="https://www.slideshare.net/slideshow/embed_code/key/KWOI2RV5FbuAMI" width="476" height="400" frameborder="0" marginwidth="0" marginheight="0" scrolling="no"></iframe>