---
title: jekyll
---

install jekyll: https://jekyllrb.com/docs/installation/windows/

add `gem "webrick"` and `gem 'wdm', '>= 0.1.0' if Gem.win_platform?` to `Gemfile`

bundle install
bundle exec jekyll serve

## Icon

find icon in https://fontawesome.com/icons
```html
<script src="https://kit.fontawesome.com/dc3b63b893.js" crossorigin="anonymous"></script>
```

img to svg converter: https://www.pngtosvg.com/

## Issues
### Invalid argument @ rb_sysopen
`rm -rf _site`
