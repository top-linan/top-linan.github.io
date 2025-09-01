---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


# Curriculum Vitae

<!-- 下载按钮 -->
<p>
  <a class="btn btn--primary" href="{{ '/files/cv.pdf' | relative_url }}" target="_blank" rel="noopener">
    📄 打开 / 下载我的简历（PDF）
  </a>
</p>

<!-- 内嵌 PDF 预览（浏览器支持时直接展示） -->
<object
  data="{{ '/files/cv.pdf' | relative_url }}"
  type="application/pdf"
  width="100%"
  height="900px">
  <embed
    src="{{ '/files/cv.pdf' | relative_url }}"
    type="application/pdf"
    width="100%"
    height="900px" />
  <!-- 回退内容（不支持内嵌时显示下载链接） -->
  <p>你的浏览器不支持直接预览 PDF。你可以
    <a href="{{ '/files/cv.pdf' | relative_url }}" target="_blank" rel="noopener">点击这里下载</a>。
  </p>
</object>

