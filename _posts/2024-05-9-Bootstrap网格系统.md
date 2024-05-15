---
layout: post
author: ted
---

<div class="container">
    <h1>Hello, world!</h1>
    <div class="row">
        <div class="col-md-3" style="background-color: #dedef8;box-shadow: inset 1px -1px 1px #444, inset -1px 1px 1px #444;">
            <h4>第一列</h4>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            </p>
        </div>
        <div class="col-md-9" style="background-color: #dedef8;box-shadow: inset 1px -1px 1px #444, inset -1px 1px 1px #444;">
            <h4>第二列 - 分为四个盒子</h4>
            <div class="row">
                <div class="col-md-6" style="background-color: #B18904; box-shadow: inset 1px -1px 1px #444, inset -1px 1px 1px #444;">
                    <p>
                        Consectetur art party Tonx culpa semiotics. Pinterest 
        assumenda minim organic quis.
                    </p>
                </div>
                <div class="col-md-6" style="background-color: #B18904; box-shadow: inset 1px -1px 1px #444, inset -1px 1px 1px #444;">
                    <p>
                         sed do eiusmod tempor incididunt ut labore et dolore magna 
        aliqua. Ut enim ad minim veniam, quis nostrud exercitation 
        ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    </p>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6" style="background-color: #B18904; box-shadow: inset 1px -1px 1px #444, inset -1px 1px 1px #444;">
                    <p>
                        quis nostrud exercitation ullamco laboris nisi ut 
        aliquip ex ea commodo consequat.
                    </p>
                </div>
                <div class="col-md-6" style="background-color: #B18904; box-shadow: inset 1px -1px 1px #444, inset -1px 1px 1px #444;">
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit, 
        sed do eiusmod tempor incididunt ut labore et dolore magna 
        aliqua. Ut enim ad minim.
                    </p>
                </div>
            </div>
        </div>
    </div>
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