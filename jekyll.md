---
layout: default
title: Jekyll
nav_order: 2
parent: Home-Lab
last_modified_date: 2023-04-17 18:56:35
---

# Jekyll build
## Local
Build the site and make it available on a local server.
```shell
bundle exec jekyll serve
```

## Production
Build the site for production. Find output in _site
```shell
JEKYLL_ENV=production bundle exec jekyll b
```