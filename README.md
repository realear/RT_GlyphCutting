# RTGlyphCutting

#### 介绍
Glyphs3 Filte插件，根据添加的参考线切割字形。


#### 使用说明

添加全局参考线和本地参考线，然后根据参考线进行字形切割。
全局参考线针对全部字形，设置了全局参考线，在字体窗口，选择字形执行过滤器后，都会通过全局参考线的位置进行切割，本地参考线只针对设置了的字形。

切割宽度可以字形设置，如果选择本地参考线，才会去执行本地参考线的切割。

![输入图片说明](screenshot.png)

选择以参考线坐标点为中心发散切口，会以参考线的坐标点为中心为交点，沿着射线的方向进行发散，展开角度可以字形设置。

![输入图片说明](image/%E5%8F%91%E6%95%A3.png)

随机选项，使用在多字选择时候，可以随机在每个字形按照设置的范围进行随机切割。随机最大数超过总参考线数，会以参考线总数为最大数。

![输入图片说明](image/%E5%88%87%E5%89%B2.gif)