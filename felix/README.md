# Felix Felicis / Liquidluck

Jekyll-inspired Python based static site generator.

Supports markup of Markdown and reStructuredText.

Why Liquid when you have Jekyll? Because Idiomatic Python--a Pythonista [doesn't agree](http://liquidluck.readthedocs.org/en/latest/design.html) says:
> Don’t create anything.

No invalid markup like Jekyll does.

Uses Jenja2 as template engine.

Live reload and live preview with tornado. Other goodies include zsh and webhooks plugins.

No support for plugins or extensions. That's a feature.

Overall, a simpler design than Jekyll.

## First time users

    virtualenv ENV

    ./ENV/bin/pip install

# Build and Run

    ./ENV/bin/liquidluck init
> hit enter and accept all defaults
> a default hello-world.md is added under content/

    ./ENV/bin/liquidluck build -v

    ./ENV/bin/liquidluck server




