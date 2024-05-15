---
layout: post
author: jill
---

<img src="/assets/images/背景1.jpeg" class="img-rounded" style="width: 300px; height: 225px;">
<img src="/assets/images/背景2.jpeg" class="img-circle" style="width: 300px; height: 300px;">
<img src="/assets/images/背景4.jpeg" class="img-thumbnail" style="width: 300px; height: 225px;">

<style>
  /* 设置图片样式 */
  .full-width-image {
    position: fixed; /* 将图片定位为固定位置 */
    top: 0;
    left: 0;
    width: 100%; /* 图片宽度占满整个页面 */
    height: 100%; /* 图片高度占满整个页面 */
    z-index: -1; /* 将图片放置在页面底部 */
    object-fit: cover; /* 使用 cover 值保持图片比例并填满容器 */
  }
</style>

<!-- 图片 -->
<img src="/assets/images/背景5.jpeg"  class="full-width-image">