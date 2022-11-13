---

---

# brotherearth967.github.io

This is my rudimentary [website](https://brotherearth967.github.io). 

## To-do list:

- [ ] Make Pixel 404 Banner
- [ ] Update `texture-tavern`
- [x] Make banner_stuff_x30.png be the same proportions as banner_main_x30.png
- [x] Make Email, PMC and Discord pixel icons

## Configuration

### Packages

- `ruby`
- `rubygems`
  - `jekyll`
- `dart-sass`

See [Jekyll Quickstart](https://jekyllrb.com/docs/) to setup locally.

#### Files

- `Gemfile` controls [the packages involved](https://jekyllrb.com/docs/ruby-101/).

- `_config.yml` controls the config for the whole site

- `_layouts/` contains any html templates the built markdown files will use

- `assets/css/` contains stylesheets
  
  - `*.scss` files are the ones to be edited
    
    - Run `sass -w <dir path>` to start a dart-sass process watching the directory. This will automatically compile all Sass files to CSS every time you save a change.
  
  - `*.css` files are the ones to be used by html documents

#### CLI

- `bundle exec jekyll serve` builds and hosts the site on `http://localhost:4000`
  
  - `--livereload` automatically reloads the page upon source file edit

## Template

```md
---
title: Title
---

![Banner](/assets/imagename.png)

## Heading

## Heading

### Subheading

## Footnotes & Citations

[^1]: 1st Footnote

[^2]: 2nd Footnote
```
