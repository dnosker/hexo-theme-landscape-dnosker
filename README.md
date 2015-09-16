# Landscape

A variation on the landscape theme (Hexo default theme).

## Customizations from forked repo:
### (https://github.com/jr0cket/hexo-theme-landscape-jr0cket.git)
- Ubuntu fonts
- padding and round corners on code blocks
- 3 styles for images when using swig (thumbnail, code & topic)
- minimised spacing everywhere, smaller header banner

## My Customizations:
- Change starting top menu to 2 items. (Home, About)
- Small positioning changes to top menu items.

## Installation

``` bash
git clone https://github.com/dnosker/hexo-theme-landscape-dnosker.git themes/landscape-dnosker
```

**Landscape requires Hexo 2.4 and above.**

### Enable

Modify `theme` setting in `_config.yml` to `landscape-dnosker`.

### Update

``` bash
cd themes/landscape-dnosker
git pull
```

## Configuration

``` yml
# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Sidebar
sidebar: right
widgets:
- category
- tag
- tagcloud
- archives
- recent_posts

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
```

- **menu** - Navigation menu
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox]
- **sidebar** - Sidebar style. You can choose `left`, `right`, `bottom` or `false`.
- **widgets** - Widgets displaying in sidebar
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
- **google_plus** - Google+ ID

## Features

### Fancybox

Landscape uses [Fancybox] to showcase your photos. You can use Markdown syntax or fancybox tag plugin to add your photos.

```
![img caption](img url)

{% fancybox img_url [img_thumbnail] [img_caption] %}
```

### Sidebar

You can put your sidebar in left side, right side or bottom of your site by editing `sidebar` setting.

Landscape provides 5 built-in widgets:

- category
- tag
- tagcloud
- archives
- recent_posts

All of them are enabled by default. You can edit them in `widget` setting.

