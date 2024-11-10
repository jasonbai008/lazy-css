# lazy-man-css

A commonly used CSS toolkit for lazy people, like me.  
懒人工具CSS合集

## How to use

Using npm:
```sh
npm install lazy-man-css
# in your main.js
import "lazy-man-css"
```

Using CDN:
```html
<link rel="stylesheet" href="https://unpkg.com/lazy-man-css@3.0.0/index.css">
```

In HTML:
```html
<div class="textCenter">文字水平居中</div>
<div class="textMiddle">文字垂直居中</div>
<div class="slh">省略号...</div>
```

## Useful Links

- [How to publish your own package on npm](https://zhuanlan.zhihu.com/p/215842050)

## Useful Classes

```css
/* 弹性盒子布局 */
.flex
.flexCenter
.justifyCenter
.alignCenter

/* 文本对齐 */
.textCenter
.textLeft
.textRight
.textMiddle

/* 单行省略号 */
.slh

/* 外间距 */
.m0
.m5
.m10
.m15
.m20
.mt0
.mt5
.mt10
.mt15
.mt20
.mr0
.mr5
.mr10
.mr15
.mr20
.mb0
.mb5
.mb10
.mb15
.mb20
.ml0
.ml5
.ml10
.ml15
.ml20

/* 内间距 */
.p0
.p5
.p10
.p15
.p20
.pt0
.pt5
.pt10
.pt15
.pt20
.pr0
.pr5
.pr10
.pr15
.pr20
.pb0
.pb5
.pb10
.pb15
.pb20
.pl0
.pl5
.pl10
.pl15
.pl20
```