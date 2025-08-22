---
title: This is test file for the markdown renderer for posts page
description: Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex est nisi fugit explicabo ad, facere placeat dolor minima dicta harum, aliquid cumque fuga laboriosam. Perspiciatis, molestias vero! At, perferendis quos.
keywords: [test-file, testfile, testing]
updated_at: 2025-08-22
og: https://ignoumax-prod-s3.s3.ap-south-1.amazonaws.com/public/og/test-file.png
---

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex est nisi fugit explicabo ad, facere placeat dolor minima dicta harum, aliquid cumque fuga laboriosam. Perspiciatis, molestias vero! At, perferendis quos.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex est nisi fugit explicabo ad, facere placeat dolor minima dicta harum, aliquid cumque fuga laboriosam. Perspiciatis, molestias vero! At, perferendis quos.

## This is first sub-heading

Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex est nisi fugit explicabo ad, facere placeat dolor minima dicta harum, aliquid cumque fuga laboriosam. Perspiciatis, molestias vero! At, perferendis quos.

## Emphasis

*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

_You **can** combine them_

## Lists

### Unordered

* Item 1
* Item 2
* Item 2a
* Item 2b
    * Item 3a
    * Item 3b

### Ordered

1. Item 1
2. Item 2
3. Item 3
    1. Item 3a
    2. Item 3b

## Table

### Normal Table
|1st Col|2nd Col|3rd Col|
|-|-|-|
Lorem ipsum| dolor sit| amet consectetur|
adipisicing e|lit. Ex est ni|si fugit explic|
abo ad, facere p|laceat dolor min|ima dicta harum|

### Table with metadata

|Column 1|Column 2|
|-|-|
|Row 2, Col 1 = Cell 2-1|[Link](/posts/test-file)|
|![testing-image-in-table](https://ignoumax-prod-s3.s3.ap-south-1.amazonaws.com/public/misc/icon-192x192.png)|Cell 3-2|
|_italic + **bold**_|`Cell 3-2`|

## Image

![working 512x512 image](https://ignoumax-prod-s3.s3.ap-south-1.amazonaws.com/public/misc/icon-512x512.png)

![invalid image url](/icons/invalid-url.png)

![This is an alt text.](https://ignoumax-prod-s3.s3.ap-south-1.amazonaws.com/public/misc/icon-apple-touch.png "This is a sample image.")

## Links

You may be using [Markdown Live Preview](https://markdownlivepreview.com/).

## Blockquotes

> Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz.
>
>> Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## Inline code

This web site is using `markedjs/marked`.

## Accordions for FAQs

<details>
<summary>This is 1st Question</summary>
Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex est nisi fugit explicabo ad, facere placeat dolor minima dicta harum.
</details>

<details>
<summary>Links inside the answer body working?</summary>
[Go to apple.com](https://apple.com) ipsum dolor sit amet adipisicing elit. Ex est nisi fugit explicabo ad, facere placeat dolor minima dicta harum.
</details>

## Youtube Video

<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe> 
