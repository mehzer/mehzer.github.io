---
layout: post
title:  "Half-Life of a Blog Post"
date:   2013-11-15
excerpt: <div class="row"><div class="col-sm-6 col-md-3"><div class="thumbnail"><img src="/images/content-half-life.png"/></div></div><div class="col-sm-6 col-md-9"><p class="lead">How long does a blog post retain its impact? Here I look at some blog posts from the HWX site and then figure out the half-life of a piece of content to feed into content planning.</p></div></div>
---

<p class="lead">How long does a blog post retain its impact? Here I look at some blog posts from the HWX site and then figure out the half-life of a piece of content to feed into content planning.</p>

I spend a lot of time planning and executing on an editorial calendar aligned to our overall corporate and product narratives. While you can't predict the impact of an individual post, it would be useful to know how long it would remain fresh for. Social distribution doesn't remain live for very long and should be subject to best timings and recycling efforts (and of course a lot of tech tries to solve that problem automagically) but I was curious on the [half-life](http://en.wikipedia.org/wiki/Half-life) of the original material. Original material is typically a blog post related to some story arc we have in-market. Understanding it's half-life helps plan the best rhythm and volume for content production.

For this quick calculation, I looked at 5 'business' focused posts (versus the more technical content). An example post is [something like this](http://hortonworks.com/blog/hadoops-part-in-a-modern-data-architecture/).

<div class="alert alert-info">I found that the range of a blog post half life was between 4.8 and 6.4 days, suggesting the need for fresh content approximately once per week.</div>

This may hint that a more rapid rhythm than that would signal to readers a specific 'push' on a given topic. I'll take a look at that some other time.

##Calculating Half-Life

Running your own calculation is fairly simple. This particular chart shows a single post with a half-life of 5.9 days. The others looked pretty much the same. You can see a small bump around Day 20 when the post was recycled through social distribution. 

<p><div class="row">
  <div class="col-md-8 col-md-offset-2">
		<img src="/images/content-half-life.png" class="img-responsive"/>
	</div>
</div></p>

First of all, the easiest way to get the Pageviews information is via this [Google Analytics Query Explorer](http://ga-dev-tools.appspot.com/explorer/). This can be set with query terms as follows to return a list of daily pageviews. 

<p><div class="row">
  <div class="col-md-8 col-md-offset-2">
<img src="/images/query-explorer-settings.png" class="img-responsive"/>
	</div>
</div></p>

Grab a reasonable sample size of pageviews, and throw it into Excel. Then chart that simply as a line.

[This guide](http://www.lepla.org/en/modules/Activities/m22/m22-evaxl.htm) then explains a simple way to use trend lines to calculate half-life in Excel. That essentially nets out to: add in an exponential trend line, access trend line options and display the equation, then perform the reduction.



