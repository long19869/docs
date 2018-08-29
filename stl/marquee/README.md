﻿# &lt;stl:marquee&gt; 无间隔滚动

```html
<stl:marquee
  direction="滚动方向"
  height="高度"
  isDynamic="是否动态显示"
  scrollDelay="滚动延迟时间（毫秒）"
  width="宽度">
</stl:marquee>
```

## 使用说明

通过 stl:marquee 标签在模板中创建一个能够无间隔滚动的内容块

`<stl:marquee>` 的作用与 HTML 标签 `<marquee>` 类似，区别在于 `<stl:marquee>` 能够将滚动的底部和头部连接起来，形成无间隔的滚动。

`<stl:marquee>` 标签适合作为滚动的新闻公告等页面标签显示。

`<stl:marquee>` 标签对应的实体为{stl:marquee}。

## 属性

| 属性        | 说明                 |
| ----------- | -------------------- |
| scrollDelay | 滚动延迟时间（毫秒） |
| direction   | 滚动方向             |
| width       | 宽度                 |
| height      | 高度                 |