## hexo-auto-excerpt

Hexo supports excerpts by adding <!-- more --> tag. You can automate this by using hexo-auto-excerpt plugin.

### Install

```sh
npm install --save hexo-auto-excerpt
```

### Option

在 hexo 配置文件中添加如下信息：

摘录的字符数是设置为 350，可以自定义。

```sh
excerpt_length: 350
```

如果什么都不写，都不设置，则默认是 300.

default length is 300, if not specified.
