---
layout: post
title: "Flexbox is Awesome"
date: 2015-03-28 10:58:22 -0700
comments: true
categories: CSS
---

It burbled to my consciousness as if waking from a dream. CSS3 [Flexbox](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Flexible_boxes "CSS3 Flexbox") is a tool meant for the modern age of web design, at least as my company understands it.

So much of this CSS tool works the way I want a tool to work: I want to set a container element, like a div, and define *generally* how its nested elements should behave. Then, I want to, for each item, define CSS rules to describe specifically how it should act.

This is how front-end web developers think. We don't think in terms of mathematical dryness like "margin: 5px 0 10px 0;". We want to say something like, "ok all you list-items, start out pushed up against the right side of your container, and extend leftward as far as you can go."

P.S. That would be ul { display: flex; justify-content: flex-end; }

It strikes me that the irony is, it took a few decades in order for the W3C to define how developers and designers have been thinking this whole time. It makes me wonder if it was a matter of browser sophistication, or it took that governing body a while to figure out how best to implement it.

The matter of exploring how a governing body of a technology or suite of software operates ought to be the subject of another post.