---
layout: post
title:  "Hello world!"
date:   2015-10-25
---

Everything seems to be working, setting Jekyll up took longer than expected but things should be running smoothly now.

{% highlight python lineanchors %}
if True:
	HelloWorld = 'Hello world!'
	print(HelloWorld)
for i in HelloWorld:
	print(i)
{% endhighlight %}


{% highlight css %}
.foobar {
  /* Named colors rule */
  color: tomato;
}
{% endhighlight %}

Here's some JavaScript:

{% highlight js %}
var isPresent = require('is-present')

module.exports = function doStuff(things) {
  if (isPresent(things)) {
    doOtherStuff(things)
  }
}
{% endhighlight %}

Here's some HTML:

{% highlight html %}
<div class="m0 p0 bg-blue white">
  <h3 class="h1">Hello, world!</h3>
</div>
{% endhighlight %}

