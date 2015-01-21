---
layout: post
title:  "#import an implementation file"
date:   2015-01-18 22:41:57
categories: mistake objective-c xcode
---
One of the most annoying, hard to notice mistakes I stumbled upon is to import an implementation file (AKA .m file). 

{% highlight objective-c %}
#import “SomeClass.m”
{% endhighlight %}

xCode will probably will throw this error - `Linker command failed with exit code 1 (use -v to see invocation)` 
