# VR_H5_360
three.js for CSS3D Demo
//
three.js+CSS3DRenderer.min.js

有个很重要的问题需要解决：</br>
	![](https://i.imgur.com/2xYdtxT.png)
	

**标红框的地方是放背景图片的，在项目中一定要这么放，不然，ios会闪屏！(至于原因，我也不知道呀！)还要给这个背景加上属性`-webkit-backface-visibility: hidden`，实测不闪屏了;**

