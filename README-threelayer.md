# maptalks

maptalks 是针对2D地图添加了视角和旋转等功能，实现的2.5D的地图库，以针对threejs支持著称。

不过本篇只针对maptalk中的插件 threeLayer 的功能进行介绍，maptalks 的基础功能请查看: https://github.com/WhatGIS/maptalkMap#readme

ThreeJS 是一组支持WebGL功能的js库，支持三维对象和三维显示，并能呈现一些特殊效果，如果

三维的地图加上三维对象，呈现三维的效果，那必然实时相当的惊艳，目前GIS的方向也在逐渐向这个方向发展，

Web上的Cesium，手机AR，眼镜的VR，甚至与基于实时的激光雷达，现在的GIS页面，不显示个三维效果，

都不好意思出去和人打招呼。

TheeJS 的官方地址：https://threejs.org/  大家可以查看一下threejs的内容和效果。简单了解一下，会对下面的内容有帮助。

maptalks 中的插件 threelayer 支持大部分的 threejs 内容，也就是说，通过地理位置，把一个三维对象

放在那里，然后使用 threejs 的 webgl 特性来处理对象。

maptalks.three 的地址为 https://github.com/maptalks/maptalks.three ， 里面有源码和demo，有兴趣的可以自己拉下来看。

这里讲的都是我自己跑的例子，以及针对每个demo自己的理解。仅供参考。



