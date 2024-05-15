---
layout: post
author: jill
---

<table class="table table-striped">
  <caption>条纹表格布局</caption>
  <thead>
    <tr>
      <th>名称</th>
      <th>城市</th>
      <th>邮编</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Tanmay</td>
      <td>Bangalore</td>
      <td>560001</td>
    </tr>
    <tr>
      <td>Sachin</td>
      <td>Mumbai</td>
      <td>400003</td>
    </tr>
    <tr>
      <td>Uma</td>
      <td>Pune</td>
      <td>411027</td>
    </tr>
  </tbody>
</table>

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