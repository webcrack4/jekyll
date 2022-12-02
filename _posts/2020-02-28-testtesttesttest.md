---
layout: post
title: Sample blog post 111
subtitle: Each post also has a subtitle
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
  ![](https://jsd.cdn.zzko.cn/gh/webcrack4/jekyll@wtf{{ myimage.path }})
  ![](https://gcore.jsdelivr.net/gh/webcrack4/jekyll@wtf{{ myimage.path }})
{% endfor %}