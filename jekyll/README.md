# Jekyll

## Overview
[Jekyll](http://jekyllrb.com) is a Ruby based site generator.

Works out of the box with markdown, textile, and hosted on github by creating a _gh-pages_ branch or an org/user level project.

Blog-aware: posts, meta-data based on [^yaml]YAML, page templates, categories, tags, permalinks, variables in pages (YAML), syntax highlighting, and a powerful templating language (liquid).

Templates are dynamic, output is static.

Deploy generated files on any web host including Amazon S3, {your own ftp server}

Global config, page variables, site variables.

[Liquid Templates](https://github.com/Shopify/liquid) provide tags, filters, converters. Tags are really cool: they add dynamic behavior for the pre-processor to generate a custom, static site.

Rich Plugins: Caching, Full-text search, page excerpts, less processor, and many more.

Dead simple CSS themes.

## First time users

    brew install ruby

    export BREW_RUBY_GEM="/usr/local/opt/ruby/bin"

    brew install rbenv

    export RBENV_ROOT=/usr/local/var/rbenv

    export PATH=$RBENV_ROOT:$BREW_RUBY_GEM:$PATH

## Build

> check ruby version
    rbenv local

    gem install jekyll

    jekyll new jekyll-blog

    cd jekyll-blog

    jekyll serve








