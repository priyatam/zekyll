# Static Site Generators and Toolkits

My ongoing research on static site generators, builders, and toolkits.

## Introduction

What are static sites generators?

Let me try:

> A toolkit that pre-processes assets (css, images, fonts) and plaintext, adds html templates (compiled or as-is), provides configurable logic for them to link together, statically, as a standalone website.

With static sites you don't need a database or server. You don't have to worry about css attacks. You can even configure your assets through a CDN. What's more, servers love them.

They serve them for free.

However, they come in several languages. What you choose depends on your comfort, your taste, whether you're a developer or a designer. There's no good answer for "what's a good static site generator", the same way there isn't a good answer for "what's a vegan cafe in San Francisco."

To know what's good for me, I tell myself: let me try it.

## How to choose

Use it. Change it. Write your own.

I [did](https://github.com/priyatam/frozen-pie).

What I learned about static sites (so far, at least):

**Minimalist**

Basic. Logic-less. File based.

Best for users getting rid of cms in search of simplicity.

Git: [Toto](http://cloudhead.io/toto), Javascript: [Wintersmith](http://wintersmith.io), etc.,

**Good intentions**

Simple, yet flexible with some options. Most popular to solve "the 80%".

Best for designers comfortable with basic programming skills, and developers who want a boilerplate to configure.

Ruby: [Jekyll*](http://jekyllrb.com), Python: [Frozen-Flask](http://pythonhosted.org/Frozen-Flask/), [Liquidluck](http://lab.lepture.com/liquidluck/), Javascript: [Hammer](http://malarkey.github.io/Rock-Hammer), etc.,

**Fullstack**

Cover a range of workflows, templating languages, markups, pre-processors that hack the hell out of your content with plugins.

Best for programmers who like to modify, integrate, and connect the missing dots with code.

Ruby: [Middleman](http://middlemanapp.com), Python: [Hyde](http://ringce.com/hyde), Javascript: [Docpad*](http://docpad.org), etc.,

**Odd, but good**

[PieCrust](http://bolt80.com/piecrust/), [Punch](http://www.laktek.com/2012/04/19/punch-a-fun-and-easy-way-to-build-modern-websites/).

## References

1. [The mother of all lists](http://nanoc.ws/about/)
2. [32 Static Website Generators](https://iwantmyname.com/blog/2011/02/list-static-website-generators.html)
3. [Hacking up sites with Middleman](http://darrenknewton.com/2012/09/16/hacking-up-sites-with-middleman/)
