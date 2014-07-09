## Keep This Readme Weird

## Install

```
bundle install
```

## Run

To start the server run:

```
$ jekyll serve -w
```

This will pick up changes as they are made.

## Build CSS before pushing to GitHub

Temporarily remove the `---` lines from the top of `css/main.sass`, then run:

```
sass css/main.sass css/main.css -I_sass
```

Make sure to revert the `---` change, so that jekyll will keep building the css locally.
