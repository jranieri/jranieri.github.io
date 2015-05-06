---
layout:     post
title:      "Let's test the post with latex"
subtitle:   "My first post with some good old latex and maybe some code"
date:       2015-05-06 18:06:00
category: article
---

<p> Let me make sure I am not crazy, latex works! $$\phi(x,y)$$</p> 

<p>This was a test for not inline text, what happens if I want it inline? $\phi(x,y)$.</p>

now we are going to check how python code looks like

{% highlight python %}
class test():
	def __init__(self,N):
		self.N=N

	def star(self,A,B):
		self.star=A+B
{% endhighlight %}

now we are going to check how matlab code looks like

{% highlight matlab %}
N=64
x=randn(N,1)
X=fft(x)

plot(fftshift(X))


{% endhighlight %}

All good... can we try the blockquotes?

> Hej, I wrote you an email 10 years ago... still waiting for a reply!

Ok, now we put an horizontal line

***

Nice!

*** can we put videos?

<iframe width="420" height="315" src="http://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
