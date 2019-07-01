# Maupassant
Maupassant theme, ported to Hugo.

1. Preview: [Linvon's Blog](http://www.linvon.cn)
2. [中文文档](README.md)

A simple Hugo template with great performance on different devices, ported from a Typecho theme by [Cho](https://github.com/pagecho/maupassant/), forked and modified from [rujews/maupassant-hugo](https://github.com/rujews/maupassant-hugo)，changed some styles.

## Main Features

1. Use the original style of quote in post
2. Increase the width of the page，almost spread the entire screen
3. Remove the sidebar of the post, the article spread the entire screen
4. Adjusted the font-size of some classes
5. Add the style of “about me” page. Like “archive”, you need to set the type of the article to "about"
6. Add icons of personal social links

## Configuration of social links

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

Just set ‘params.followme’ sections in config.toml, and name is the type of social app, url is your link。

Besides，iconfont which i used is [Logos](https://www.iconfont.cn/collections/detail?cid=16800), supported by Ali. Before you add your links, you need to check if the name of your app is matched with the name of the icon. (Only part of icons was included, replace the iconfont if needed)

