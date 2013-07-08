# Zekyll

Static file generators come in more than ten languages. What you choose depends on your comfort, your taste, whether you're a developer or a designer. 

I recommend javascript and ruby toolkits. I think they're simple, designer friendly, and are backed by a thriving community who care about the web. 

In this POC, I compile a list of seven toolkits with five languages, mostly for fun and learning. They are by no means the best, though some would argue they're popular. I happen to like them. If I had more time I'd include seven more.

## What I talk about when I talk about static sites

> A toolkit that pre-processes static assets (css, images), content, templates, and simple logic between them in order to generate a custom website.

This makes the site lightening *fast*. 

When you don't have a database, a server computing or rendering pages or data, when you can use the global delivery of a CDN to optimize and cache files like images, when you don't worry about css attacks (hackers hate static sites), let me tell me you, a site with pure static assets will roar.

Servers love them. They do: they serve them for free. The best things in life are better when they're free.

Like Sex?

You can classify the toolkits into the following:

**Small**

The Minimalist, ascetic. No sex. 

Logic-less, file based.

Best for non-tech users, who want to get rid of drupal, joomla, and wordpress.

Example: 

- Git: [Toto](http://cloudhead.io/toto)
- Javascript: [Wintersmith](http://wintersmith.io)

**Medium**

Simple, default, few options only. Sex is fine with your partner.

Most popular in this category as they solve 80% of your problems.

Best for designers. 

Example: 

- Ruby: [Jekyll](http://jekyllrb.com)
- Python: [Frozen-Flask](http://pythonhosted.org/Frozen-Flask/)
- Javascript: [Hammer](http://malarkey.github.io/Rock-Hammer)

**Large**

Fullstack, free love included--go 60's! 

Covers a wide range, including complex workflow requirements like the ability to use any templating language, custom pre-processors, helpers, and plugin ecosystems.

Best for programmers looking for a lightweight alternative to full blown web frameworks, or designers ready to take the leap.

Example: 

- Ruby: [Middleman](http://middlemanapp.com) 
- Python: [Hyde](http://ringce.com/hyde) 
- Javascript: [Docpad](http://docpad.org)

---    

## A Designer's workflow

Write html, css, and occasionally, javascript. This is not 1996: things have improved since then; there's a better way: *Pre-processors*.

Instead of HTML, use *Markdown, HAML, Slim*. 

Instead of repeating HTML, use Templates like *Jade*. 

Plain old CSS is so 1999--use *Stylus, SCSS, Compass, Less*. 

Not everyone likes Javascript, use *Coffescript*.

---   
 
## Jekyll

[Jekyll](http://jekyllrb.com) is a Ruby based site generator. 

Works out of the box with markdown, textile, and hosted on github by creating a _gh-pages_ branch or an org/user level project.

Blog-aware: posts, meta-data based on [^yaml]YAML, page templates, categories, tags, permalinks, variables in pages (YAML), syntax highlighting, and a powerful templating language (liquid).

Templates are dynamic, output is static.

Deploy generated files on any web host including Amazon S3, {your own ftp server}

Global config, page variables, site variables.

[Liquid Templates](https://github.com/Shopify/liquid) provide tags, filters, converters. Tags are really cool: they add dynamic behavior for the pre-processor to generate a custom, static site.

Rich Plugins: Caching, Full-text search, page excerpts, less processor, and many more.

Dead simple CSS themes.

## Liquid Duck
(A.K.A Felix Felicis)

Jekyll-inspired Python based static site generator.

Uses pip, a cli similar to jekyll cli.

Supports markup of Markdown and reStructuredText.

Why Liquid when you have Jekyll? Because Idiomatic Python--a Pythonista [doesn't agree](http://liquidluck.readthedocs.org/en/latest/design.html) all of Jekyll.
> Don’t create anything.

No invalid markup like Jekyll does. 

[^yaml]: a key,value pair that adds up as meta data for jekyll pre-processor.

Uses Jenja2 as template engine.

Live reload and live preview with tornado (pip). Other goodies include zsh and webhooks plugins.

Overall, simpler than Jekyll, and also lesser plugins & ecosystem--but who knows this might be a good thing.

## Middleman

**Config**

All configuration options are present in a single file: `config.rb`. Standard options include preprocessors, engines, helpers, path overrides, build config etc., See topics below for relevant config options.

**Content**

All content must be stored in yyyy-mm-dd-title.html.ext format. The date and html are mandatory, else middleman chokes. You can, however, change the style of permalinks in config.rb 


**Templates & Layouts**

A page is a decorated with a layout in two ways: yaml in the page itself, config.rb

    page "/admin/*", :layout => "admin"
    
*Partials* are a way of sharing content across pages to avoid duplication. They can be used in page templates and layouts.    
    
**Blogging**

Hello.

**Dynamic Pages**

Hello.

**Filters**

Modify content on-the-fly and intercept requests before they are processed by the server using *Rack Middleware*. 

**Local Data**

Hello.

---    

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

If you're a solo designer I recommend the Ruby stack, simply because the toolkits go deep into the pixels of a responsive web.

---

## References

1. [The mother of all lists](http://nanoc.ws/about/)
2. [32 Static Website Generators](https://iwantmyname.com/blog/2011/02/list-static-website-generators.html)
3. [Hacking up sites with Middleman](http://darrenknewton.com/2012/09/16/hacking-up-sites-with-middleman/)
4. 