# Markdown syntax guide

## Headers

# This is a Heading h1
## This is a Heading h2 
###### This is a Heading h6

## Emphasis

*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

_You **can** combine them_

~_You **can** combine them_~

## Lists

### Unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b
- Item 3

### Ordered

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

## File Overview

| File    | Description    | Content    | Sample  |
|---------|----------------|------------|---------|
|aaa      | aaaaaaaaa      | a1         | 11111   | 
|bbbb     | bbbbbbbb       | b2         | 22222   |
|cccc     | cccccccccc     | c3         | 33333   |
|dddd     | dddddddddd     | d4         | 44444   |

## Images

![This is a alt text.](/image/sample.jpg "This is a sample image.")

| aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa | bbbbbbbbbbbbbbbbbbbbbbbbbbbbbb |
| ------------------------------ | ------------------------------ |
| ![](/image/sample.jpg)         | ![](/image/sample.jpg) | 

aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa | bbbbbbbbbbbbbbbbbbbbbbbbbbbbbb
:-----------------------------:|:-----------------------------:
![](https://github.com/stemsgrpy/test/blob/master/image/sample.gif) |  ![](https://github.com/stemsgrpy/test/blob/master/image/sample.gif)

<table>
  <tr>
    <th>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</th>
    <th>bbbbbbbbbbbbbbbbbbbbbbbbbbbbbb</th>
  </tr>
  <tr>
    <th>
      <img src="/image/sample.gif"/>
   </th>
    <th>
      <img src="/image/sample.gif"/>
    </th>
  </tr>
</table>

<p align="center">
  <img width="500" src="/image/sample.jpg">
</p>
<p align="center">
  Figure 1: aaaaaaaaa
</p>

- Video
  - link <br>`https://www.youtube.com/......v=xxxxx`
  - image <br>`http://img.youtube.com/vi/xxxxx/0.jpg`

<p align="center">
  <a href="https://github.com/stemsgrpy" target="_blank">
    <img src="/image/sample.jpg" alt="Description" width="480" height="360" border="0" />
  </a>
</p>

## Links

You may be using [Markdown Live Preview](https://markdownlivepreview.com/).

## Blockquotes

> Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz.
>
>> Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## Inline code

This web site is using `markedjs/marked`.

## Dependencies

Trained and tested on:
```
Python 3.6
NumPy 1.15.3
PyTorch 1.0
```

## Reference
https://markdownlivepreview.com/