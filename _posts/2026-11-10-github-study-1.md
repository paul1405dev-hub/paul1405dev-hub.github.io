---
layout: post
title: 깃허브 공부 1일차
subtitle: github pages, jekyll에 관하여
tags: [study]
comments: true
mathjax: true
author: 광진
---

{: .box-success}
github pages, jekyll 다운 및 원하는 블로그를 테마를 fork 해오는 과정에 대해서 배웠고 해당 블로그의 기능들을 익혀 수정하는 것에 대해 공부

## 사전 준비 과정 3가지

{: .box-note}
**1. Ruby 설치**<br/>
<https://rubyinstaller.org/downloads/>

{: .box-note}
**2. Jekyll, Bundler 설치**

```bash
gem install jekyll bundler
```

{: .box-note}
**3. 새 사이트 생성 및 서버 확인**

```bash
jekyll new .
jekyll serve --watch
```

이후 <https://github.com/topics/jekyll-theme>에서 테마를 고름

![스크린샷]({{ '/assets/img/스크린샷%202026-11-05%20104336.png' | relative_url }})

(참고사진)
