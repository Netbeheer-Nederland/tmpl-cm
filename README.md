# Conceptual Model

_Template repository_.

## Dependencies

* `git` set up with SSH
* `gh` authorized with SSH
* `python` version 3.12 or higher
* `uv` version 0.7.8
* `copier` (Python library) version 9.4.1 or higher
* `just` rask runner version 1.38.0 or higher

## Creating a conceptual model

Simply run:

```
$ copier copy --trust gh:Netbeheer-Nederland/tmpl-cm im-name-of-model
```

Copier will ask you for some information and store the answers in a file used to set project variables.

Once it's done, you can run `just initialize` to:

* Create a local Git repository
* Create a remote GitHub repository
* Set up branch protection rules
* Install a Python virtual environment for local development
