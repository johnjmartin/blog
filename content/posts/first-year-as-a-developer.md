---
title: "Five Lessons Learned During My First Year as a Software Developer at Shopify"
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

Last year I finished up my degree and went to work for
[@Shopify](https://shopify.com). I'm currently working as a Developer on
the Data Science and Engineering team there.
These are five lessons I thought worth sharing, they were jotted down
throughout my first year as a software engineer.

## Take things slow

Pull requests are there for a reason, when you start on a feature, don't let
yourself stray from the initial goal you started when you got to work that
morning.

I was forced to learn to this out of necessity; it was hard enough to get
single line changes merged with the standard of quality enforced by my team.
In order to get any work accomplished I realized I would have to reduce the
scope of my pull requests.

## The documentation isn't wrong; you're wrong

Mainly this heading makes me laugh because of how true I've seen it to be.
Do your due diligence before making large claims about how the documentation
to a codebase written by hundreds of developers much more experienced than you
is incorrect. More often than not you're misinterpreting something and should
take another few minutes to be sure of your conclusions.

If you encounter a problem which you think is serious enough to raise to a more
senior developer for advice, have a clear map in your mind about the issue
you're about to explain.

## Work takes twice as long to do right

My background before joining Shopify was a CS degree and two prior internships,
none of which - at no fault of their own - taught me to
practice test driven development. I initially estimated tasks based off just
the time I thought it would take to implement, but when factoring in sufficient
testing (there is a strict 80% [code coverage](https://codecov.io/) requirement
on most repositories), and the code review process; the actual implementation is
usually about half the time spent.

## Be clear and communicative about the work you're doing

Do not underestimate the importance of detail when working with your colleagues.
Carefully communicate feature descriptions, updates to tasks you’ve started but
had to abandon, and technical issues.

While dealing with a request to set up a database proxy between two different
cloud providers, progress was held up by consistent connection timeouts on
long-lived queries. After numerous changes to network settings on both ends of
the proxy about half of connections started succeeding. In an effort to spin a
positive narrative, I stated things were "starting to work", rather than being
forthright. After hours more investigation it was noticed that one of the
endpoints had more than one A Record (the connection was going to more than one
server). Had it been communicated earlier that half the requests were failing
we probably would have realized earlier that we needed to be configuring two
servers, not just the one.

## With time and practice, you will improve

Programming takes time. I learned how to program four years ago and one thing I
can say with absolute confidence is that you'll never stop learning.
The context that comes from experience means you can spend way less time playing
with a one line command that “might be the problem" in your code and use your
experience to quickly solve problems and pick up new styles of development.


I owe a ton to Shopify and especially my team members for taking a chance in
mentoring me, for that I say thanks.
