<!--
 * @Author: Huangjs
 * @Date: 2021-05-10 15:55:29
 * @LastEditors: Huangjs
 * @LastEditTime: 2023-10-09 15:39:16
 * @Description: ******
-->

## lightdom

一些dom操作

### 安装使用

```sh

npm install @huangjs888/lightdom --save

```

### 使用方法

```js

import { createElement, setStyle, addClass, hasClass, removeClass } from '@huangjs888/lightdom';

const dom = createElement(
  {
    className: ['test', 'test2'],
    style: { width: 100, marginTop: 20 },
  },
  createElement('span', { style: { color: 'red' }, dataName: 'span element' }, 'Hello World'),
  document.body,
);
setStyle(addClass(removeClass(dom, 'test2'), 'test3'), { height: 100, marginLeft: 20 });
console.log(hasClass(dom, 'test2'));
console.log(hasClass(dom, 'test3'));


```
