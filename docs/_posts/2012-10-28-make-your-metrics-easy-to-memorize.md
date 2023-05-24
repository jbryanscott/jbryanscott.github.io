---
layout: post
title:  "Make your metrics easy to memorize"
date:   2012-10-29 06:44:00 +0000
categories: startups
published: true
---

One of the most important responsibilities of an analytics team inside a startup is to evangelize key performance metrics to decision makers elsewhere in the company. This boils down to:

1. Defining and focusing on a few great metrics
1. Ensuring that decision makers understand roughly how these metrics are calculated and why they are the best metrics
1. Ensuring that decision makers know the approximate value of these metrics **at all times**


I focus on #3 in this post.

Why is #3 so important? In startups, decision makers are constantly making decisions. Members from the analytics team usually won’t be there. Therefore, unless decision makers have a persistent idea of their performance metrics, they will inevitably make decisions that are data-ignorant. And a major goal of the analytics team is to avoid the company making data-ignorant decisions.

Phrased another way: When metrics—products of a good analytics team—are easier to use, customers—decision makers around the company—will use them more.

So what qualifies metrics as easy to use? You need to check off #1 and #2, but I won’t address those in this post.

A successful tactic I’ve seen is to make your metrics easy for decision makers to memorize. Once decision makers memorize metrics, they become more comfortable with them, use them more often, and apply them more correctly. This increases the leverage of the analytics team and makes it more effective.

Because your audience is not the type to memorize 68,000 digits of π, you have to simplify your metrics. But how?

For broad consumption, I like to communicate four pieces of information in a metric:

- Unit (e.g. users, dollars, days)
- Order of magnitude (e.g. thousands, millions, billions)
- Rounding to two significant digits

Examples (from 2012 data):

- The decimal value of π: 3.1 (unit-less)
- United States GDP: $15 trillion
- World Population: 7.0 billion people
- Expected odds of being killed in a plane crash in one year for an American: 1 in 11 million (unit-less)

I think it’s obvious why units and order of magnitude are important pieces. But why two significant digits?

- For memorization’s sake, fewer digits is better. Most everyone can recount that π is about 3.1 or 3.14 but few people can remember more. Worse, more digits can distract the reader from the highest order digits. People also tend to transpose digits of big numbers in their heads. So I’ll take the bare minimum number of digits, please.
- One digit is often not enough to do meaningful calculations for decisions that are within 10%. And for startups, almost all of your atomic metrics-based decisions are calls within 10%.
- Two digits is almost always sufficient for meaningful calculations.
- Three digits doesn’t add nearly as much incremental value, so we’ve already reached diminishing returns on a continuously decreasing function (average value per digit as a function of number of significant digits).