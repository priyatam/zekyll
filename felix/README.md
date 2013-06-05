# Felix Felicis

## Overview
(A.K.A Felix Felicis)

Jekyll-inspired Python based static site generator.

Uses pip, a cli similar to jekyll cli.

Supports markup of Markdown and reStructuredText.

Why Liquid when you have Jekyll? Because Idiomatic Python--a Pythonista [doesn't agree](http://liquidluck.readthedocs.org/en/latest/design.html) all of Jekyll.
> Don’t create anything.

No invalid markup like Jekyll does.

Uses Jenja2 as template engine.

Live reload and live preview with tornado (pip). Other goodies include zsh and webhooks plugins.

Overall, simpler than Jekyll, and also lesser plugins & ecosystem--but who knows this might be a good thing.

# Bootstrap

    virtualenv ENV

    ./ENV/bin/pip install

# Build and Run

    ./ENV/bin/liquidluck init
> hit enter and accept all defaults
> a default hello-world.md is added under content/

    ./ENV/bin/liquidluck build -v

    ./ENV/bin/liquidluck server




