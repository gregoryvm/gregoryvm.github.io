---
layout: post
title: An overview of our project.
subtitle: What ambitions do we have for our app.
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

A postmortem of your development experience, where you discuss some of the issues that arose during the development of your process. You can (and should) include both negative and positive points; they will not count against your project mark. It is highly recommended that you include the last three items from the list above. Also ensure that you discuss the area you identified for improvement after your iteration 2 retrospective; how did it go? This should be informal, you can choose two or three of the following items to discuss, or something else you find interesting or relevant:
What was the overall architecture of your system (particularly if it is different from the demo system)?
What went right in the development process?
What went wrong in the development process?
What would you do differently, if you had the chance to start over?
How large is the project (number of methods, classes, etc)? How much of this is (roughly) devoted to each major system component? And any other quantifiables (e.g. if you have a record of hours spent on tasks).
What took the most time? The least? Any surprises?
Are there any particular design smells, or brilliant design decisions?
Are there any outstanding bugs?
Did any features work better than expected?
Are you using any technologies other than what was required (e.g. JMock, GUI builders, etc.)?
Are you using any specific techniques covered in the course (TDD, pair programming, scrums, etc)?
How did the project change from your initial (iteration 0) vision or stories, or did it work out as predicted?
What did you learn about team or large project development? What will you start doing, keep doing, or stop doing next time?
Can you draw any conclusions from what you’ve done?

This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

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
