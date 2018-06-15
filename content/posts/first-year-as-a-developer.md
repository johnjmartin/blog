---
title: "What I've learned in my first year as a Software Engineer"
date: 2018-06-14T10:24:40-04:00
description: "What I've learned since entering the workforce"
categories: [
    "programming"
]
tags: [
  "software",
    "development"
]
---


These are some anecdotes I thought worth sharing, they were jotted down
throughout my first year as a software engineer [@Shopify](https://shopify.com).

## Things take twice as long to do right

My background before joining  was a CS degree and two prior internships,
none of which - at no fault of their own - taught me to
practice test driven development. I initially estimated tasks based off just
the time I thought it would take to implement, but when factoring in sufficient
testing (there is a strict 80% [code coverage](codecov.io) requirement on most
repositories), and the code review process, the actual implementation is usually
about half the time spent.


## Take things slow

Pull requests are there for a reason, when you start on a feature, don't let
yourself stray from the initial goal you started when you got to work that
morning.

I was forced to learn to this out of necessity; it was hard enough to get
single line changes merged with the standard of quality enforced by my team,
if I was going to get any work accomplished I realized I would have to greatly
reduce the scope of my pull requests.

As an example, imagine you create a branch named: `update-cli` because you've
noticed a bug in your app's cli which ..


## The documentation isn't wrong; you're wrong

Mainly this heading makes me laugh because of how true I've seen it to be.
Do your due diligence before making large claims about how the documentation
to a codebase written by developers much more experienced than you is incorrect.
More often than not you're misinterpreting something and should take another few
minutes to be sure of your conclusions.

If you encounter a problem which you think is serious enough to raise to a more
senior developer for advice, have a clear map in your mind about the issue
you're about to explain.

## Be clear and communicative about the work you're doing

A record pointed at two proxies, only one of which we were updating configs on; saw that 50% of requests were working, chose to metion that “one worked!” rather than actually pointing out half were working. if i had we could have gotten to the bottom of the problem faster

## It gets faster



    1. the context that comes from experience means you can spend way less time playing with a one line command that “might not work” because this command “might” only work with the exact path to the file
    2. other examples of trying stupid things because you can’t come up with anything better
