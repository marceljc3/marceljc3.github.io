---
title: "About Me"
permalink: "/about/"
layout: page
---

## Who is this?

I am Marcel, a university student at Carleton University for Computer Science Honors. 

## What do you do?

## Installation


## Config

Your `_config.yml` could for example look like this:

```yaml
title: "Blog Title"
author: "Blog Author"
description: "My blog"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"

# Layout

show_excerpts: true             # show article excerpts instead of archive list on the home page
show_frame: true                # display a grey frame on large screens
show_sidebar: false             # show a sidebar instead of the usual header
show_minimal: false             # remove all clutter

# Menu                          # for available icons see https://fontawesome.com/v5/icons/

navigation:                     # accepts {file, title, url, icon, sidebaricon}
  - {file: "archive.html", sidebaricon: home}
  - {file: "README.md", sidebaricon: address-card}

external:                       # accepts {file, title, url, icon, sidebaricon}
  - {title: Mail, icon: envelope, url: "mailto:author@example.com"}
  - {title: Github, icon: github, url: "https://github.com/"}
  - {title: Subscribe, icon: rss, url: "/feed.xml"}

comments:
#  disqus_shortname: ""         # see https://disqus.com
#  isso_domain: ""              # see https://isso-comments.de

plugins:
 - jekyll-feed
```

## MathJax

## License

## Screenshots
