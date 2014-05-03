# hexo-theme-lion

A brand new theme for [Hexo]. Modify from Hexo's default theme [landscape](https://github.com/tommy351/hexo-theme-landscape.git)

- [Preview](http://chideat.info)

## Installation

### Install

``` bash
$ git clone https://github.com/chinat/hexo-theme-lion.git themes/lion
```

**Lion requires Hexo 2.4 and above.**

### Enable

Modify `theme` setting in `_config.yml` to `lion`.

## Configuration

### Fancybox

Lion uses [Fancybox] to showcase your photos. You can use Markdown syntax or fancybox tag plugin to add your photos.(Same as Landscape)

```
![img caption](img url)

{% fancybox img_url [img_thumbnail] [img_caption] %}
```

### Sidebar

You can put your sidebar in left side, right side of your site by editing `sidebar` setting.

Lion provides 5 built-in widgets:

- category
- tag
- tagcloud
- archives
- recent

A Few of them are enabled by default. You can edit them in `widget` setting.

[Hexo]: http://zespia.tw/hexo/
[Fancybox]: http://fancyapps.com/fancybox/
[Font Awesome]: http://fontawesome.io/
[Grunt]: http://gruntjs.com/
