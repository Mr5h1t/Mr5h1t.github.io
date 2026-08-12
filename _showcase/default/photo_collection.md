<!-- 暂时禁用（模板示例内容）。以后有真实内容时，把上面这行注释标记删除，并恢复下面的 front matter 即可。
---
show: true
width: 4
date: 2021-09-12 00:01:00 +0800
height: 295px
images:
- src: https://picsum.photos/seed/first1111/800/800
  title: Photo 1
  desc: Description 1.
  link: https://picsum.photos/
- src: https://picsum.photos/seed/second22/800/800
  title: Photo 2
  desc: Description 2
- src: https://picsum.photos/seed/third33/800/800
---
-->

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
