# light-hugo-notes

This a responsive hugo theme meant for use as a personal notebook. Its based on the light-hugo theme here: https://github.com/tblyler/light-hugo

Supports pagination and tags. Create an empty 'all.md' page with `layout = "all"` if you want a list page of all notes without pagination.

License: Mozilla Public License Version 2.0

Example config.toml
```
title = "My Notebook"
languageCode = "en-us"
baseurl = "http://my.private.notebook/"
theme = "light-hugo-notes"
paginate = "7"
copyright = "My Copyright"

[[menu.header]]
  name = "Tag"
  weight = 2
  url = "/tags/"

[taxonomies]
  tag = "tags"
```
