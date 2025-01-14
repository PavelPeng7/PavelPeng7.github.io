---
layout:     post
title:      Pavel's Store
subtitle:   Unity Plugins,Models,VFX
date:       2025-01-10
author:     Pavel
header-img: img/玩具总动员4_ 杂物.png
catalog: true
tags:
    - 专辑
    - 商店
---

Welcome to the store of Pavel.

<iframe id="iframe1" frameborder="0" src="https://itch.io/embed-upload/12498996?color=19181e" allowfullscreen="" width="960" height="540">
    <a href="https://pavelpeng.itch.io/unity-dynamic-stylized-sky">Play Unity Dynamic Stylized Sky on itch.io</a>
</iframe>

<iframe id="iframe2" frameborder="0" src="https://itch.io/embed/3238945" width="552" height="167">
    <a href="https://pavelpeng.itch.io/unity-dynamic-stylized-sky">Unity Dynamic Stylized Sky by Pavel</a>
</iframe>

<script>
  function adjustIframeSize() {
    // 获取第一个 iframe
    var iframe1 = document.getElementById('iframe1');
    // 获取第二个 iframe
    var iframe2 = document.getElementById('iframe2');

    // 定义阈值
    var widthThreshold1 = 768; // 中等屏幕的最大宽度
    var widthThreshold2 = 384; // 小屏幕的最大宽度

    // 设置第一个 iframe 尺寸
    if (iframe1) {
      if (window.innerWidth <= widthThreshold2) {
        iframe1.width = 256;
        iframe1.height = 144; // 16:9 的宽高比
      } else if (window.innerWidth <= widthThreshold1) {
        iframe1.width = 414;
        iframe1.height = 233; // 16:9 的宽高比
      } else {
        iframe1.width = 960;
        iframe1.height = 540; // 默认尺寸
      }
    }

    // 设置第二个 iframe 尺寸
    if (iframe2) {
      if (window.innerWidth <= widthThreshold2) {
        iframe2.width = 276;
        iframe2.height = 84; // 保持宽高比例（原比例约为 552:167）
      } else if (window.innerWidth <= widthThreshold1) {
        iframe2.width = 414;
        iframe2.height = 125; // 保持比例
      } else {
        iframe2.width = 552;
        iframe2.height = 167; // 默认尺寸
      }
    }
  }

  // 页面加载时调整尺寸
  document.addEventListener('DOMContentLoaded', adjustIframeSize);

  // 窗口尺寸变化时调整尺寸
  window.addEventListener('resize', adjustIframeSize);
</script>