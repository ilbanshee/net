---
layout: post
title: "Alias Method"
date: 2012-02-05 13:33
comments: true
categories:
- Code
- Informatica
- English
---

Need to generate random samples from a given discrete distribution?
The *Alias Method*
(wonderfully described [here](http://www.keithschwarz.com/darts-dice-coins/))
comes to mind... for those who haven't heard of it it's a simple but powerfull
$$\Theta(1)$$ random generator with a $$\Theta(n)$$ initial setup time,
so... need to generate random samples from a given discrete distribution
in Scala?
Check out this implementation.

{% gist 1745222 %}

PS: I love github's gist feature!
