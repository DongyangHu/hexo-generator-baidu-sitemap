# Sitemap generator

Generate sitemap.

**使用站图的初衷是[为自己的博客添加站内搜索](http://gengbiao.me/2014/10/22/hexo%E6%B7%BB%E5%8A%A0%E7%99%BE%E5%BA%A6%E7%AB%99%E5%86%85%E6%90%9C%E7%B4%A2/),如果想更好的发挥站图的作用，建议手动提交baidusitemap给百度.**

## Install

``` bash
$ npm install hexo-generator-baidu-sitemap --save
```

## Update

if you install with --save, you must remove firstly when you update it.
``` bash
$ npm remove hexo-generator-baidu-sitemap
$ npm install hexo-generator-baidu-sitemap --save
```

## Options

You can configure this plugin in `_config.yml`.

``` yaml
baidusitemap:
    path: baidusitemap.xml
```

- **path** - Sitemap path. (Default: baidusitemap.xml)


