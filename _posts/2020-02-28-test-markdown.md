---
layout: post
title: How to Dyno
subtitle: Tips to help you with those pesky dynamic movements to far holds
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Dyno Side By Side Comparison**
<iframe width="640" height="360" src="/assets/img/HorizontalDyno.mp4" frameborder="0" allowfullscreen></iframe>

**Dyno Breakdown**
<div style="position:relative;height:0;padding:56.25% 0 0 0;"><iframe src="https://www.dartfish.tv/Embed?CR=p191109c538461m7985583&VW=100%&VH=100%&sh=li&aid=accd8f56-2bc5-4737-8a9e-8693ca6b194f" style="position:absolute;display:block;width:100%;height:100%;max-width:100%;max-height:100%;left:0;right:0;top:0;bottom:0;margin:auto;" frameborder="0" allowfullscreen ></iframe></div>

## Here is a secondary heading

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
