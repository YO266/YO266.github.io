---
layout: post
author: ted
---

<div class="dropdown">
    <button type="button" class="btn dropdown-toggle" id="dropdownMenu1" data-toggle="dropdown">主题
        <span class="caret"></span>
    </button>
    <ul class="dropdown-menu" role="menu" aria-labelledby="dropdownMenu1">
        <li role="presentation" class="dropdown-header">下拉菜单标题</li>
        <li role="presentation">
            <a role="menuitem" tabindex="-1" href="#">Java</a>
        </li>
        <li role="presentation">
            <a role="menuitem" tabindex="-1" href="#">数据挖掘</a>
        </li>
        <li role="presentation">
            <a role="menuitem" tabindex="-1" href="#">数据通信/网络</a>
        </li>
        <li role="presentation" class="divider"></li>
        <li role="presentation" class="dropdown-header">下拉菜单标题</li>
        <li role="presentation">
            <a role="menuitem" tabindex="-1" href="#">分离的链接</a>
        </li>
    </ul>
</div>

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