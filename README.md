# 基于[Hexo-theme-Anatole](https://github.com/Ben02/hexo-theme-Anatole)主题修改

## DEMO: http://tronwei.top

## 调整
1. 调整原主题的界面字体大小
2. 增加标签tag界面
3. 去除了原主题的评论插件
4. 更新了awesome-font图标源，支持最新图标
5. 配置文件增加live2d（npm install --save hexo-helper-live2d）

## 拓展：
### 1. 界面左上角增加 fork me on github 图标
在sidebar.pug文件中第一行
```
.sidebar.animated.fadeInDown
```
下增加代码
```
// 左上角 github-fork-me
  //.fork_me
   //a(href="https://github.com/weixusheng")
    //img(style="position: absolute; top: 0;left: 0; border: 0;" src="https://camo.githubusercontent.com/567c3a48d796e2fc06ea80409cc9dd82bf714434/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f6769746875622f726962626f6e732f666f726b6d655f6c6566745f6461726b626c75655f3132313632312e706e67" alt="Fork me on GitHub" data-canonical-src="https://s3.amazonaws.com/github/ribbons/forkme_left_darkblue_121621.png")
```
如果需要更换图标样式，参考以下文档
[官方文档](https://github.blog/2008-12-19-github-ribbons/)
