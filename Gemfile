# Site settings
title: "Sustainability and the Environment through the Dunitz Archive"
email: arutkows@usc.edu
description: >
  Writing 150 with the Dunitz Archive assignment modules for the class.
baseurl: "/dunitz150" # the subpath of your site, e.g. /blog/
url:  # the base hostname & protocol for your site
git_address: https://github.com/andyrutkowski/dunitz150
git_edit_address: https://github.com/andyrutkowski/dunitz150/blob/gh-pages

# theme options from https://bootswatch.com/
# comment out this to use default Bootstrap
bootwatch: paper

# Build settings
markdown: kramdown
highlighter: rouge
gems:
  - jekyll-feed
  - jekyll-redirect-from
  - jekyll-seo-tag
  - jekyll-sitemap

exclude:
  - Gemfile
  - Gemfile.lock
  - .idea/
  - .gitignore
  - README.md
timezone: Europe/Berlin
defaults:
- scope:
    path: _posts
    type: posts
  values:
    layout: post
    sectionid: blog

- scope:
    path: _docs
    type: docs
  values:
    layout: docs
    sectionid: docs
    seo:
      type: "WebPage"

collections:
  docs:
    permalink: /:collection/:path/
    output: true
  posts:
    permalink: /blog/:year/:month/:day/:title/
output: true
