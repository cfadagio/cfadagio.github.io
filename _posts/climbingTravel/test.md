---
layout: single
title:  "사이드바 메뉴 설정"
folder: "jekyll"
categories:
  - climbingTravel
tags: [blog, jekyll]

author_profile: true
sidebar:
  nav: "docs"

toc: true
toc_label: "목록"
toc_icon: "bars"
toc_sticky: true

date: 2021-07-30
---

Nested and mixed lists are an interesting beast. It's a corner case to make sure that

* Lists within lists do not break the ordered list numbering order
* Your list styles go deep enough.

### Ordered -- Unordered -- Ordered

1. ordered item
2. ordered item 
   * **unordered**
   * **unordered** 
     1. ordered item
     2. ordered item
3. ordered item
4. ordered item

### Ordered -- Unordered -- Unordered

1. ordered item
2. ordered item 
   * **unordered**
   * **unordered** 
     * unordered item
     * unordered item
3. ordered item
4. ordered item

### Unordered -- Ordered -- Unordered

* unordered item
* unordered item 
  1. ordered
  2. ordered 
     * unordered item
     * unordered item
* unordered item
* unordered item

### Unordered -- Unordered -- Ordered

* unordered item
* unordered item 
  * unordered
  * unordered 
    1. **ordered item**
    2. **ordered item**
* unordered item
* unordered item

### Task Lists

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request