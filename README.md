# GitHub Pages template repo using Just the Docs Jekyll theme

## This template is a starter for jekyll page

See [Jekyll](https://jekyllrb.com/)
Also uses just-the-docks theme from https://pmarsceill.github.io/just-the-docs/


### Develop

To use local config run:

```
$ bundle exec jekyll serve --config _config_local.yml
```

### Publish

Remember to set the GitHub Pages setting in repo settings.
Use `main` branch and `/(root)` folder to create the pages content.

Do not select theme from the settings. The theme is configured in _ _config.yml_ file with config
```
    remote_theme: pmarsceill/just-the-docs
```
