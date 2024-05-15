---
layout: post
author: jill
---

<form class="form-horizontal" role="form">
  <div class="form-group">
    <label for="firstname" class="col-sm-2 control-label">名字</label>
    <div class="col-sm-10">
      <input type="text" class="form-control" id="firstname" placeholder="请输入名字">
    </div>
  </div>
  <div class="form-group">
    <label for="lastname" class="col-sm-2 control-label">姓</label>
    <div class="col-sm-10">
      <input type="text" class="form-control" id="lastname" placeholder="请输入姓">
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-offset-2 col-sm-10">
      <div class="checkbox">
        <label>
          <input type="checkbox">请记住我
        </label>
      </div>
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-offset-2 col-sm-10">
      <button type="submit" class="btn btn-default">登录</button>
    </div>
  </div>
</form>

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