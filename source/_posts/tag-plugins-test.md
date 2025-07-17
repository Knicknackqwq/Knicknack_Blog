---
title: tag_plugins_test
date: 2025-07-04 15:54:23
tags: 
    - test_tag_plugins
    - private
categories: test_1
---


<u>下划线演示</u>

文字**加粗**演示

文字*斜体*演示

文本`高亮`演示

文本~~删除~~线演示

<font size = 5>5号字</font>
<font face="黑体">黑体</font>
<font color=blue>蓝色</font>

<table><tr><td bgcolor=MistyRose>这里的背景色是：MistyRosen，此处输入任意想输入的内容</td></tr></table>


### test2

{% note modern %}默认 提示块标签{% endnote %}

{% note default modern %}default 提示块标签{% endnote %}

{% note primary modern %}primary 提示块标签{% endnote %}

{% note success modern %}success 提示块标签{% endnote %}

{% note info modern %}info 提示块标签{% endnote %}

{% note warning modern %}warning 提示块标签{% endnote %}

{% note danger modern %}danger 提示块标签{% endnote %}


### test3

{% timeline 时间轴样式%}

<!-- timeline 2020-07-24 [2.6.6 -> 3.0](https://github.com/volantis-x/hexo-theme-volantis/releases) -->

1. 如果有 `hexo-lazyload-image` 插件，需要删除并重新安装最新版本，设置 `lazyload.isSPA: true`。
2. 2.x 版本的 css 和 js 不适用于 3.x 版本，如果使用了 `use_cdn: true` 则需要删除。
3. 2.x 版本的 fancybox 标签在 3.x 版本中被重命名为 gallery 。
4. 2.x 版本的置顶 `top: true` 改为了 `pin: true`，并且同样适用于 `layout: page` 的页面。
5. 如果使用了 `hexo-offline` 插件，建议卸载，3.0 版本默认开启了 pjax 服务。

<!-- endtimeline -->

<!-- timeline 2020-05-15 [2.6.3 -> 2.6.6](https://github.com/volantis-x/hexo-theme-volantis/releases/tag/2.6.6) -->

不需要额外处理。

<!-- endtimeline -->

<!-- timeline 2020-04-20 [2.6.2 -> 2.6.3](https://github.com/volantis-x/hexo-theme-volantis/releases/tag/2.6.3) -->

1. 全局搜索 `seotitle` 并替换为 `seo_title`。
2. group 组件的索引规则有变，使用 group 组件的文章内，`group: group_name` 对应的组件名必须是 `group_name`。
2. group 组件的列表名优先显示文章的 `short_title` 其次是 `title`。

<!-- endtimeline -->

{% endtimeline %}
