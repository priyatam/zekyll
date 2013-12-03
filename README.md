# Seven Static Site Toolkits

Static file generators come in more than ten languages. What you choose depends on your comfort, your taste, whether you're a developer or a designer. 

I recommend javascript and ruby toolkits. I think they're simple, designer friendly, and are backed by a thriving community who care about the web. 

In this POC, I compiled a list of toolkits with several languages, mostly for fun and learning. They are by no means the best; I just like them, that is all. If I had more time I'd include more.

## What I talk about when I talk about static sites

> A toolkit that pre-processes static assets (css, images), content, templates, and simple logic between them in order to generate a custom website.

This makes the site lightening *fast*. 

When you don't have a database, a server computing or rendering pages or data, when you can use the global delivery of a CDN to optimize and cache files like images, when you don't worry about css attacks (hackers hate static sites), let me tell me you, a site with pure static assets will roar.

Servers love them. They do: they serve them for free. The best things in life are better when they're free. Think Sex.

You can classify the toolkits into the following:

**Small**

The Minimalist, ascetic. No sex. 

Logic-less, file based.

Best for users getting rid of cms in search of simplicity.

Examples: 

- Git: [Toto](http://cloudhead.io/toto)
- Javascript: [Wintersmith](http://wintersmith.io)

**Medium**

Simple, yet flexible with limited options. Sex is fine with some strings attached.

Most popular in this category as they solve 80% of your problems.

Best for designers and developers who are comfortable with basic programming skills.

Examples: 

- Ruby: [Jekyll*](http://jekyllrb.com)
- Python: [Frozen-Flask](http://pythonhosted.org/Frozen-Flask/), [Liquidluck](http://lab.lepture.com/liquidluck/)
- Javascript: [Hammer](http://malarkey.github.io/Rock-Hammer)

**Large**

Fullstack, free love included, no strings attached. Think of the 60s.

Covers a wide range of workflows templates, markups, pre-processors that hack the hell out of your content with helpers and plugins.

Best for programmers getting ready for the leap.

Examples: 

- Ruby: [Middleman](http://middlemanapp.com) 
- Python: [Hyde](http://ringce.com/hyde) 
- Javascript: [Docpad*](http://docpad.org)

---    

## A Designer's workflow

I think?

Write html, css, and templates. 

Things have improved since 1996; there's a better way: *Pre-processors*.

Instead of HTML, use *Markdown, HAML, Slim*. 

Instead of repeating HTML, use Templates like *Jade*. 

Plain old CSS is so 1999--use *Less, Stylus, SCSS, Compass, Bourbon mixins*. 

Not everyone likes Javascript, use *Coffescript*.

Designers can choose a Ruby or a Python stack:

Ruby stack:

- html: haml, slim
- templates: handlebars
- css: sass, compass
- grids: h5bp, susy
- gen: middleman


Javascript stack:

- html: jade, handlebars, coffeekup
- css: less, stylus
- grids: bootstrap, cofeescript
- gen: node, docpad

---

## Ideal Toolkit

1. Write in Markdown
2. Metadata in YAML
3. Embed image, video, code, photos in posts
4. Pages, Blogs, Wikis
5. Full-text search capability
6. Start with Html5 Boilerplate / Bootstrap
7. One click push to github-pages
8. Discuss comments
9. Tweet / Pingback buttons 

## Notable Frameworks

1. [PieCrust](http://bolt80.com/piecrust/)
2. [Punch](http://www.laktek.com/2012/04/19/punch-a-fun-and-easy-way-to-build-modern-websites/)

## References

1. [The mother of all lists](http://nanoc.ws/about/)
2. [32 Static Website Generators](https://iwantmyname.com/blog/2011/02/list-static-website-generators.html)
3. [Hacking up sites with Middleman](http://darrenknewton.com/2012/09/16/hacking-up-sites-with-middleman/)
