---
layout: post
title:  "DigitalPhotography(II)"
date:   2019-02-13 12:45:00 +0400
categories: Photography
published: true
---
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>


# Digital Photography (II)

## 光圈（续）
同一个镜头里，光圈数N翻一倍，直径缩小1/2，因此进光量减小到1/4。由于快门时间翻一倍，进光量翻一倍，如果在光圈数上每\\(\sqrt(2)\\)倍指定一个刻度，那么每进一个刻度进光量刚好小一半。这也是光圈刻度是f2.8, f4, f5.6这种奇怪数字组合的由来。<br/>
例：
\\(2.8 * 1.414 = 3.959\\)  \\(4*1.414 = 5.656\\)

问题：手机上F2的镜头和单反上的F2镜头，单位面积传感器上收集的光量是否一样？思考为什么一般手机拍出来的低光照照片要比单反噪点更多？<br/>
手机镜头一般焦距比单反镜头小，因为需要装到薄机身中去。手机镜头的孔径也会变小因为镜头整体体积不能太大。综合起来光圈数\\(N=\frac{f}{A}\\)是一样的。<br/>
由于孔径变小了，同样的景物，手机镜头收集的光量比单反镜头小。但是由于单反镜头焦距变大，虽然光更多但是需要分散到更大的区域。收集的光量跟A平方成正比，单位区域的照射量跟f平方成反比。因此，手机镜头和单反镜头F2，传感器上单位面积受到的照射量是一样的。<br/>
然而，照片的噪点数跟每个像素能收集到的光子数相关。焦距更小的情况下，传感器面积也变小。为了让像素个数保持一致（12MP, 24MP）等，需要把像素变得更小。单位面积光照相同情况下，小的像素收集到的光子数更少。

## 景深（简介）
- 景物中的一个点在平面上聚焦成一个点
- 物体在深度方向的移动会导致失焦
- 但是物体能移动一定的距离使得失焦度不超过我们可接受的范围
- 这个范围的边界称为circle of confusion
- 物体能移动的距离就是景深，对应的，像平面附近的距离称为焦深

### 景深与运动模糊之争
一个曝光值对应着一组光圈和曝光时长的组合。光圈影响景深，曝光市场影响运动模糊度。
TStop - takes the light transmission rate into consideration

## 感光度（ISO）
在胶片时代曾被称作(ASO American Standard Organization)...<br/>
Sensitivity影响照片的噪点，在胶片时代影响胶粒。本质上影响传感器的基准电压，后面会详细介绍传感器的工作原理。
