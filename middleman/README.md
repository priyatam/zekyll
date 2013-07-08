# Middleman


## Config

All configuration options are present in a single file: `config.rb`. Standard options include preprocessors, engines, helpers, path overrides, build config etc., See topics below for relevant config options.

## Content

All content must be stored in yyyy-mm-dd-title.html.ext format. The date and html are mandatory, else middleman chokes. You can, however, change the style of permalinks in config.rb 


## Templates & Layouts

A page is a decorated with a layout in two ways: yaml in the page itself, config.rb

    page "/admin/*", :layout => "admin"
    
*Partials* are a way of sharing content across pages to avoid duplication. They can be used in page templates and layouts.    
    
## Blogging

TBD.

## Dynamic Pages

TBD.

## Filters

Modify content on-the-fly and intercept requests before they are processed by the server using *Rack Middleware*. 

## Local Data

TBD.







