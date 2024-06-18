---
title: "백준"
categories:
  - computer-sicence
tags:
  - [python, blog]

# toc_icon: fa-solid fa-utensils"
author_profile: true
sidebar:
    nav: "sidebar"

# redirect_from:
#   - /CS/
---
Nested and mixed lists are an interesting beast. It's a corner case to make sure that

{{ site.title }}

**[공지사항]** [다희 블로그 신규 업데이트 안내 드립니다.](https://naver.com)
{: .notice--danger}

<div class="notice--success">
<h2> 공지사항입니다. </h2>
<ul>
    <li>공지사항 순서 1</li>
    <li>공지사항 순서 2</li>
    <li>공지사항 순서 3</li>
</ul>
</div>

[버튼입니다](https://naver.com){: .btn .btn--danger}


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