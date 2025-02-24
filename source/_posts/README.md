---
title: READ ME
date: 2025-02-19
updated:
tags: READ
categories: 
keywords:
description:
top_img: 
comments: true
cover: 
toc:
toc_number:
toc_style_simple:
copyright:
copyright_author: blaze
copyright_author_href:
copyright_url:
copyright_info: 版权声明
mathjax:
katex:
aplayer:
highlight_shrink:
aside:
abcjs:
noticeOutdate:
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)



Page Front-matter 页面配置：

```markdown
---
title:
date:
updated:
type:
comments:
description:
keywords:
top_img:
mathjax:
katex:
aside:
aplayer:
highlight_shrink:
random:
limit:
  type:
  value:
---
```

| 参数             | 解释                                                         |
| ---------------- | ------------------------------------------------------------ |
| title            | 【必需】页面标题                                             |
| date             | 【必需】页面创建日期                                         |
| type             | 【必需】标签、分类和友情链接三个页面需要配置                 |
| updated          | 【可选】页面更新日期                                         |
| description      | 【可选】页面描述                                             |
| keywords         | 【可选】页面关键字                                           |
| comments         | 【可选】显示页面评论模块 (默认 true)                         |
| top_img          | 【可选】页面顶部图片                                         |
| mathjax          | 【可选】显示 mathjax (当设置 mathjax 的 per_page: false 时，才需要配置，默认 false) |
| katex            | 【可选】显示 katex (当设置 katex 的 per_page: false 时，才需要配置，默认 false) |
| aside            | 【可选】显示侧边栏 (默认 true)                               |
| aplayer          | 【可选】在需要的页面加载 aplayer 的 js 和 css，请参考文章下面的音乐配置 |
| highlight_shrink | 【可选】配置代码框是否展开 (true/false) (默认为设置中 highlight_shrink 的配置) |
| random           | 【可选】配置友情链接是否随机排序（默认为 false）             |
| limit            | 【可选】配置説説显示数量                                     |
| limit.type       | 【可选】配置説説显示数量的类型 （date 或者 num）             |
| limit.value      | 【可选】配置説説显示数量的值                                 |

Post Front-matter 页面配置：

```markdown
---
title:
date:
updated:
tags:
categories:
keywords:
description:
top_img:
comments:
cover:
toc:
toc_number:
toc_style_simple:
copyright:
copyright_author:
copyright_author_href:
copyright_url:
copyright_info:
mathjax:
katex:
aplayer:
highlight_shrink:
aside:
abcjs:
noticeOutdate:
---
```

| 参数                  | 解释                                                         |
| --------------------- | ------------------------------------------------------------ |
| title                 | 【必需】文章标题                                             |
| date                  | 【必需】文章创建日期                                         |
| updated               | 【可选】文章更新日期                                         |
| tags                  | 【可选】文章标签                                             |
| categories            | 【可选】文章分类                                             |
| keywords              | 【可选】文章关键字                                           |
| description           | 【可选】文章描述                                             |
| top_img               | 【可选】文章顶部图片                                         |
| cover                 | 【可选】文章缩略图(如果没有设置 top_img,文章页顶部将显示缩略图，可设为 false/图片地址/留空) |
| comments              | 【可选】显示文章评论模块(默认 true)                          |
| toc                   | 【可选】显示文章 TOC(默认为设置中 toc 的 enable 配置)        |
| toc_number            | 【可选】显示 toc_number(默认为设置中 toc 的 number 配置)     |
| toc_style_simple      | 【可选】显示 toc 简洁模式                                    |
| copyright             | 【可选】显示文章版权模块(默认为设置中 post_copyright 的 enable 配置) |
| copyright_author      | 【可选】文章版权模块的文章作者                               |
| copyright_author_href | 【可选】文章版权模块的文章作者链接                           |
| copyright_url         | 【可选】文章版权模块的文章连结链接                           |
| copyright_info        | 【可选】文章版权模块的版权声明文字                           |
| mathjax               | 【可选】显示 mathjax(当设置 mathjax 的 per_page: false 时，才需要配置，默认 false ) |
| katex                 | 【可选】显示 katex (当设置 katex 的 per_page: false 时，才需要配置，默认 false ) |
| aplayer               | 【可选】在需要的页面加载 aplayer 的 js 和 css,请参考文章下面的音乐 配置 |
| highlight_shrink      | 【可选】配置代码框是否展开(true/false)(默认为设置中 highlight_shrink 的配置) |
| aside                 | 【可选】显示侧边栏 (默认 true)                               |
| abcjs                 | 【可选】加载 abcjs (当设置 abcjs 的 per_page: false 时，才需要配置，默认 false ) |
| noticeOutdate         | 【可选】文章过期提醒 (默认为设置中 noticeOutdate 的 enable 配置) |
