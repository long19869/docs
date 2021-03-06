# STL 元素

STL 元素包裹在开始和结束尖括号 **<>** 中，属性用空格隔开，可以包含其他标签作为子标签，例如：

```html
<stl:a channelIndex="首页">链接</stl:a>
```

STL 元素之间可以相互嵌套；例如：

```html
<stl:a channelIndex="首页">
  <stl:content type="title"></stl:content>
</stl:a>
```

STL 元素最终将解析为 HTML 标签或者纯文字。

## 栏目标签

内容标签包含获取内容列表以及内容属性相关的标签。

| STL 元素                                          | 说明                                               |
|---------------------------------------------------|----------------------------------------------------|
| [stl:channel 获取栏目值](../channel/)             | 通过 stl:channel 标签在模板中显示指定栏目的属性值  |
| [stl:channels 栏目列表](../channels/)             | 通过 stl:channels 标签在模板中显示栏目列表         |
| [stl:pageChannels 翻页栏目列表](../pageChannels/) | 通过 stl:pageChannels 标签在模板中显示翻页栏目列表 |

## 内容标签

内容标签包含获取内容列表以及内容属性相关的标签。

| STL 元素                                          | 说明                                               |
|---------------------------------------------------|----------------------------------------------------|
| [stl:content 获取内容值](../content/)             | 通过 stl:content 标签在模板中显示指定内容的属性值  |
| [stl:contents 内容列表](../contents/)             | 通过 stl:contents 标签在模板中显示内容列表         |
| [stl:pageContents 翻页内容列表](../pageContents/) | 通过 stl:pageContents 标签在模板中显示翻页内容列表 |

## 导航标签

导航标签包含所有与页面导航相关的标签，包括链接、当前位置、导航、以及下拉菜单等。

| STL 元素                                  | 说明                                                              |
|-------------------------------------------|-------------------------------------------------------------------|
| [stl:a 获取链接](../a/)                   | 通过 stl:a 标签在模板中创建链接，系统将根据所处上下文计算链接地址 |
| [stl:location 当前位置](../location/)     | 通过 stl:location 标签在模板中插入页面的当前位置                  |
| [stl:navigation 显示导航](../navigation/) | 通过 stl:navigation 标签在模板中显示链接导航                      |
| [stl:tree 树状导航](../tree/)             | 通过 stl:tree 标签在模板中显示树状导航                            |

## 图片及多媒体标签

图片标签包含所有涉及到显示图片以及组织图片显示样式的相关标签。

| STL 元素                                      | 说明                                                    |
|-----------------------------------------------|---------------------------------------------------------|
| [stl:image 显示图片](../image/)               | 通过 stl:image 标签在模板中显示栏目或内容的图片         |
| [stl:file 文件下载链接](../file/)             | 通过 stl:file 标签在模板中显示文件下载链接              |
| [stl:video 播放视频](../video/)               | 通过 stl:video 标签在模板中显示视频播放器               |
| [stl:audio 播放音频](../audio/)               | 通过 stl:audio 标签在模板中显示并播放音频文件           |
| [stl:flash 显示 Flash](../flash/)             | 通过 stl:flash 标签在模板中获取并显示栏目或内容的 Flash |
| [stl:player 播放视频](../player/)             | 通过 stl:player 标签在模板中播放视频                    |
| [stl:focusViewer 滚动焦点图](../focusViewer/) | 通过 stl:focusViewer 标签在模板中显示滚动焦点图         |

## 判断标签

判断标签用于根据条件判断显示内容，包含通用的 if 标签以及用于列表的 itemTemplate 标签。

| STL 元素                                    | 说明                                                               |
|---------------------------------------------|--------------------------------------------------------------------|
| [stl:if 条件判断](../if/)                   | 通过 stl:if 标签在模板中根据条件判断显示内容                       |
| [stl:itemTemplate 列表项](../itemTemplate/) | 通过 stl:itemTemplate 标签在模板中控制列表中每一项的显示内容及样式 |
| [stl:loading 载入模板](../loading/)         | 通过 stl:loading 标签在模板中创建载入中显示的内容                  |
| [stl:yes 成功模板](../yes/)                 | 通过 stl:yes 标签在模板中显示成功模板                              |
| [stl:no 失败模板](../no/)                   | 通过 stl:no 标签在模板中显示失败模板                               |

## 翻页标签

翻页标签包含所有涉及翻页时所需要用到的标签，包括翻页元素、栏目翻页列表、内容翻页列表等。

| STL 元素                                  | 说明                                                                                 |
|-------------------------------------------|--------------------------------------------------------------------------------------|
| [stl:pageItems 翻页项容器](../pageItems/) | 通过 stl:pageItems 标签在模板中插入翻页项的容器，当不需要翻页时容器内的内容不显示    |
| [stl:pageItem 翻页项](../pageItem/)       | 通过 stl:pageItem 标签在模板中显示翻页项（上一页、下一页、当前页、页跳转、页导航等） |

## 数据库标签

数据库标签用于获取指定数据库信息，包括显示列表以及获取值所需要的标签。

| STL 元素                                                  | 说明                                                          |
|-----------------------------------------------------------|---------------------------------------------------------------|
| [stl:sqlContents 数据库列表](../sqlContents/)             | 通过 stl:sqlContents 标签在模板中显示数据库列表               |
| [stl:sqlContent 数据库值](../sqlContent/)                 | 通过 stl:sqlContent 标签在模板中显示数据库值                  |
| [stl:queryString SQL 查询语句](../queryString/)           | 通过 stl:queryString 标签在模板中定义 SQL 查询语句            |
| [stl:pageSqlContents 翻页数据库列表](../pageSqlContents/) | 通过 stl:pageSqlContents 标签在模板中显示能够翻页的数据库列表 |

## 站点标签

站点标签包含获取网站列表以及网站属性相关的标签。

| STL 元素                        | 说明                                    |
|---------------------------------|-----------------------------------------|
| [stl:value 获取值](../value/)   | 通过 stl:value 标签在模板中获取值       |
| [stl:sites 站点列表](../sites/) | 通过 stl:sites 标签在模板中显示站点列表 |
| [stl:site 获取站点值](../site/) | 通过 stl:site 标签在模板中显示站点值    |

## 其他标签

其他常用的 STL 标签。

| STL 元素                              | 说明                                                             |
|---------------------------------------|------------------------------------------------------------------|
| [stl:action 执行动作](../action/)     | 通过 stl:action 标签在模板中创建链接，点击链接后将执行相应的动作 |
| [stl:container 容器](../container/)   | 通过 stl:container 标签在模板中定义容器，切换上下文              |
| [stl:count 显示数值](../count/)       | 通过 stl:count 标签在模板中显示统计数字                          |
| [stl:dynamic 动态显示](../dynamic/)   | 通过 stl:dynamic 标签在模板中实现动态显示功能                    |
| [stl:each 列表项循环](../each/)       | 通过 stl:each 标签在模板中遍历指定的列表项                       |
| [stl:include 包含文件](../include/)   | 通过 stl:include 标签在模板中包含另一个文件，作为模板的一部分    |
| [stl:marquee 无间隔滚动](../marquee/) | 通过 stl:marquee 标签在模板中创建一个能够无间隔滚动的内容块      |
| [stl:printer 打印](../printer/)       | 通过 stl:printer 标签在模板中实现打印功能                        |
| [stl:rss Rss 订阅](../rss/)           | 通过 stl:rss 标签在模板中生成 Rss 阅读器能够浏览的 Rss 订阅      |
| [stl:search 搜索](../search/)         | 通过 stl:search 标签在模板中显示搜索结果                         |
| [stl:select 下拉列表](../select/)     | 通过 stl:select 标签在模板中显示栏目或内容下拉列表               |
| [stl:tabs 页签切换](../tabs/)         | 通过 stl:tabs 标签在模板中显示页签切换                           |
| [stl:tags 标签](../tags/)             | 通过 stl:tags 标签在模板中显示内容标签                           |
| [stl:zoom 文字缩放](../zoom/)         | 通过 stl:zoom 标签在模板中实现文字缩放功能                       |


