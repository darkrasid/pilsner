---
layout: post
title:  "banner test"
author: Pilsner
date:   2015-11-25 18:20:20 +0900
categories: long 
---

## devlog 소개

개발하면서 겪게 되는 다양한 일들을 log 남기듯이 적는 블로그 입니다.

## 포스트 작성법

블로그 엔진은 [Jekyll](http://jekyllrb.com/) 기반으로 되어 있습니다.

## Jekyll 설치

```bash
$ gem install jekyll
```

## 블로그 프로젝트 clone

```bash
$ git clone https://github.com/devlog/devlog.github.io.git
```

## 일단 로컬에서 jekyll 서버 띄어보기

```bash
# 위에서 clone 받은 디렉토리로 이동하여
$ jekyll serve
```

## 포스트 작성

포스트는 `_posts` 디렉토리 안에 있으며 마크다운 문법으로 작성하면 됩니다.

```bash
# 템플릿 포스트 복사
$ cp 2015-11-23-template.md {date}-{post 제목}.md
# 에디터로 포스트 작성
$ vi {date}-{post 제목}.md
```

## 로컬에서 확인

위에서 로컬에 jekyll 서버를 띄어 놓았다면 http://localhost:4000 에서 확인 가능 합니다.

## 커밋 후 Github으로 푸쉬

```bash
$ git commit -a
$ git push origin master
```

