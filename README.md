# XFun

一个简洁、大气、时尚的 [Hexo]主题.

![XFun](./xfun-demo.png)

## Installation

### Install

```bash
$ git clone https://github.com/jianjunx/hexo-theme-xfun.git themes/xfun
```

XFun 的主题搜索依赖[hexo-generator-search]插件，请 hexo 项目中执行以下命令安装

```bash
$ npm install hexo-generator-search --save
```

并在 hexo 的\_config.yml(不是 xfun 主题里的那个)中添加如下配置

```yml
search:
  path: search.json
  field: post
  content: true
```

如果要启用 RSS 的话请先安装[hexo-generate-feed]

```bash
$ npm install hexo-generate-feed --save
```

### Enable

Modify `theme` setting in `_config.yml` to `xfun`.

### Update

```bash
cd themes/xfun
git pull
```

## Configuration
