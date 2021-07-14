---
layout: post
title:  "First post"
date:   2021-07-14 21:10:33 +0900
categories: jekyll update
---

Alright, here it is. my first blog post.
I've decided that it is time to set up my own blog site for once for several reasons:

`1. I'm tired of losing track of my own progress, forgetting what I've already done in the past`

`2. It would probably be better to leave some sort of documentation on my future progress for archiving purposes`

`3. It is much easier to reflect on my own past mistakes this way`

I've honestly been thinking about this for more than a few months now, and my initial plan was to start studying web dev, and to build a blog on my own.

Guess how well that went. Turns out web development isn't as easy as I had thought it would be. I had greatly underestimated the amount of effort I would need to put in for it.

So for now I'm using [Jekyll][jekyll] to get this blog up and running, took me a few hours to set everything up and now it looks good. sort of. maybe. ok maybe it doesnt look that great visually but improvements are coming soon ™️.

Here are some of the troubles I had to go through:

* This was my first time doing anything with [Ruby][ruby], which means I had to install it for the first time, and I still cannot figure out why such setup processes dont add itself to the PATH environment variable upon completion. It is quite annoying having to manually add new installations to PATH every time.
* I followed [Github Pages' documentation][gitpagedoc] step-by-step and noticed there are a few errors that may occur depending on your local environment. First of all there is this [dumb issue][dumb-issue] that still hasn't been fixed for almost 5 years which cost me about an hour to figure out(They say that they've fixed it but...liars). Following the exact instructions in the default Gemfile works better than following [their documentation][gitpagedoc] as well.




[jekyll]: https://jekyllrb.com/
[dumb-issue]: https://github.com/tmm1/http_parser.rb/issues/47
[ruby]: https://www.ruby-lang.org/
[gitpagedoc]: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll