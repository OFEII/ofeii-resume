## OFEII's card

一个基础简单但有点设计，用心制作的个人名片页面

网址直达👉[https://ofeii.github.io/ofeii-card/](https://ofeii.github.io/ofeii-card/)

### PC端页面展示

![PC端页面展示](https://github.com/OFEII/ofeii-card/blob/master/images/pc-ofeii-card.png)

### 移动端页面展示

![移动端页面展示](https://github.com/OFEII/ofeii-card/blob/master/images/moblie-ofeii-card.png)

## 兼容性

| Chrome | Firefox | Mircosoft Edge | Internet Explorer | 手机浏览器 |
| ------ | ------- | -------------- | ----------------- | ---------- |
| ⭕      | ⭕       | ⭕              | ❌                 | ⭕          |

## 设计理念

### 1.个人简洁名片card

名片在社交场合之中颇为重要，虽然现在电子名片逐渐取缔了纸质名片。以前别人在出差商务社交时都会进行交换名片，而如今仅需手机扫个码就足以交换信息了。像中国的微信 QQ，国际的line等等。名片起源于中国，于唐朝传入日本及周边的国家，今日，日本依然重视名片，延伸成一种名片礼仪的文化，名片的重要性可媲美ID card。综上，我觉得名片是一种文化，里面流露了人情关怀和社交诚意。如今20应届即将踏入社会，闲暇之余，于是乎，萌生了这个制作OFEII's card的想法。

- info-个人简介 联系方式

  name college  get in touch with me.....

- social-社交平台

  github phone leetcode codepen nowcoder juejin  ofeii-demo ofeii-note........

#### 

### 2.新拟态UI设计风格（Neumorphism / soft ui）

在线工具生成网址：[https://neumorphism.io/](https://neumorphism.io/)

介于扁平与阴影的一种表现手法，通过受光面和阴影颜色的对比，引起视觉差异，提高物品的真实感。

特点：

- **模拟光源照射的真实拟物场景**。物体阴影+受光面+受光面的反射面 ==> 更逼真。
- **元素与背景对比较弱**。与背景颜色相近色，没有丰富的色彩选择 ==> 提高受光面反射光的亮度。
- **主要以圆角或卡片形状为主。**一般不大面积进行覆盖，好比真实物体置身于现实场景中。

缺点：

- 对比度弱，色彩单一，层次感不够。
- 对背景依赖度高，使用不当易造成视觉干扰。
- 样式复杂，不易修改。

## 细节



### 1.凸起凹陷的真实质感

**图标留白处选中与未选中状态切换。**在icon-box里面点击图标外的空白处，可进行选中与未选中状态的切换。主要运用到input type="checkbox"和css :checked伪类选择器，通过改变box-shadow的样式来切换，从而达到图标的凸起和凹陷的真实质感。



![凸起凹陷的真实质感](https://github.com/OFEII/ofeii-card/blob/master/images/mobile-ofeii-card-checkbox.png)

### 2.提示工具tooltip

**提示图标指引到网站平台名字的tooltip。**因为处于简洁设计出发，图标icon下面都没有使用文字注释，于是乎，当鼠标移动到图标上面时，添加多一个tooltip类。:hover选择器用于移到图标上面显示图标指引的网站名字提示。（telephone图标点击可以直接拨打电话 href="tel:xxxx"）

![提示工具tooltip](https://github.com/OFEII/ofeii-card/blob/master/images/moblie-ofeii-card-tooltip.png)





### 3.顶部的文字排版

运用不同的font-size和 line-height进行排版，使文字更加活泼😂，整体居左对齐text-align: left。

中文字体：微软雅黑Microsoft YaHei

英文字体：Saira Extra Condensed

![文字排版](https://github.com/OFEII/ofeii-card/blob/master/images/moblie-ofeii-card-info.png)

### 4.配色方案

主要的拟态颜色是淡蓝色#EBF5FC，文字的颜色主要为#343A40和#BD5D38搭配，总体配色不丰富，这和拟态的风格和设计理念的简约有一定的联系。

![配色方案](https://github.com/OFEII/ofeii-card/blob/master/images/ofeii-card-colors.png)

### 5.SVG优化

部分图标引入SVG进行性能上的一些优化，理论上icon图标用svg会比png更优化一些。F12中的network可以发现svg的size和time会比png小一点。

## TodoList

1. 完善名片信息，将社交平台打理一下，写写文章。
2. 利用vue重构一下，做成可复用，可改变配色方案的，导出....
3. 请各位大佬多多指教！

