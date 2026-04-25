---
# build:
#   list: always
#   publishResources: true
#   render: always

# build:
#   list: never
#   publishResources: false
#   render: never

title: "开发测试 Demo"
# 同目录中以 featured- 开头的图片作为缩略图
date: 2026-04-23

# 使用 categories 进行大类划分
categories: ["建站"]
# 使用 tags 进行细化标注
tags: ["Hugo", "CSS"]

# draft: false

params:
  color: red
  size: medium

summary: "这是我开发 Hugo 做的 Demo，用于记录语法和技巧"
---
<!-- 这是我开发  [Hugo](https://gohugo.io) 做的 Demo，用于记录语法和技巧 more 方式. -->
<!--more-->

## 介绍

这是我开发  [Hugo](https://gohugo.io) 做的 Demo，用于记录语法和技巧。

- 普通 Markdown 语法。

[shortcodes](https://gohugo.io/content-management/shortcodes/)

### Ref

[Link A]({{% ref "/posts/my-web-site" %}})

[Link B]({{% ref path="/posts/my-web-site" %}})

### Relref

[Link A]({{% relref "/posts/my-web-site" %}})

[Link B]({{% relref path="/posts/my-web-site" %}})

[打开新页面](https://www.google.com){:target="_blank"} 行不通

### Youtube

{{< youtube 0RKpf3rK57I >}}

### X

{{< x user="SanDiegoZoo" id="1453110110599868418" >}}

### highlight

This is some {{< highlight go "hl_inline=true" >}}fmt.Println("inline"){{< /highlight >}} code.

-----

### Details

{{< details summary="See the details" >}}
This is a **bold** word.
{{< /details >}}

-----

### Instagram

{{< instagram CxOWiQNP2MO >}}

### Param

We found a {{% param "color" %}} shirt,  Size: {{% param "size" %}}.

-----

### QR

{{< qr >}}
<https://uncle-it.com>
{{< /qr >}}

{{< qr text="tel:+12065550101" />}}

### Vimeo

{{< vimeo 19899678 >}}

### Figure

{{< figure
  src="assets/caton.jpg"
  alt="A photograph of Zion National Park"
  link="<https://www.nps.gov/zion/index.htm>"
  caption="Zion National Park"
  class="ma0 w-75"
>}}


