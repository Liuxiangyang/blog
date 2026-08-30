---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date | time.Format "2006-01-02" }}
draft: true
tags: [""]
categories: [""]
# popular: true   # 取消注释加入热门文章
# donate: true    # 取消注释开启文章底部打赏
---

开始写正文...
