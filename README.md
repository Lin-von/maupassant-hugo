# Maupassant
Maupassant theme, ported to Hugo.

1. 预览效果:[Linvon's Blog](http://www.linvon.cn)
2. [English Docs](README_EN.md)

一款非常简洁、性能高的Hugo主题，适配不同的设备（PC，Mobile等）。从 [rujews/maupassant-hugo](https://github.com/rujews/maupassant-hugo) fork，对此前的样式做了一些小改动。

## 主要改动内容

1. 正文引用使用了最初的样式
2. 页面宽度增加，基本铺满。
3. 正文不再有边侧导航栏，文章铺满全屏
4. 调整了一些字号大小
5. 增加了“关于”页面的样式，类似于归档，将文章type设置为about即可
6. 增加了个人社交连接图标

## 社交链接配置

```toml
[[params.followme]]
  name = "github"
  url = "https://github.com/Lin-von"
[[params.followme]]
  name = "facebook"
  url = "https://www.facebook.com/linvon77"
[[params.followme]]
  name = "twitter"
  url = "https://twitter.com/linvon7"
```

在config.toml中直接配置params.followme项即可，name为社交类型，url为个人地址。

使用的图标库是[Logos](https://www.iconfont.cn/collections/detail?cid=16800)，由阿里支持的，添加社交类型需要先看一下name与图标名称是否对应（仅取用了部分图标，必要时请更换图标库。）

