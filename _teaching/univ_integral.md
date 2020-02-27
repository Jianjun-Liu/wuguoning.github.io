---
title: "定积分的应用"
collection: teaching
type: "Undergraduate course"
permalink: /teaching/univ_integral
venue: "China University of Petroleum at Beijing, Department of Science"
date: 2020-02-27
location: "Beijing, CN"
---

这部分介绍一元函数定积分的应用。

## 目录

+ [第一节 求平面图形的面积](#cotes1)
+ [第二节 由平行截面求体积](#cotes2)
+ [第三节 平面曲线的弧长和曲率](#cotes3)
+ [第四节 物理应用](#cotes4)


---

<a name="cotes1"></a>
## 📌**<span style="color:blue">1. 求平面图形面积</span>**

**直角坐标下求面积**

一般地，求由$y = f_2(x), y = f_x(x)$以及两条直线$x = a, x = b$所围成的图形的面积为：

<center>
  $A = \int_a^b \vert f_2(x) - f_1(x) \vert\, \mathrm{d}x$
</center>


<center>
  <a href="https://www.geogebra.org/classic/ck2yr2ws">
  <img src="./imags/integral1d/Integral_area_between_functions.png"  width="600" height="700" />
  </a>
</center>

---

**参数方程下求面积**

<center>
  <a href="https://www.geogebra.org/classic/pf6sg96c">
  <img src="./imags/integral1d/para_curve_area.png"  width="600" height="500" />
  </a>
</center>

---

**极坐标下求二重积**

极坐标下求面积公式为：
<center>
  $A = \int_{\alpha}^{\beta}\dfrac{1}{2}r^2(\theta)\,\mathrm{d}\theta$
</center>
下图为公式的推导，及其求$r = 4 + 4\cos \theta(0 \le \theta \le 2\pi)$的面积。

<center>
  <a href="https://www.geogebra.org/geometry/p3efte9c">
  <img src="./imags/integral1d/polar_area.png"  width="600" height="700" />
  </a>
</center>
  
---

<a name="cotes2"></a>
## 📌**<span style="color:blue">1. 求界面为已知的几何体的体积</span>**

设一个几何体$S$自变量$x$的变化范围为：$[a,b]$.在$x$处的截面的面积为$A(x)$，

  <center>
  <a href="https://www.pearsonhighered.com/thomas13einfo/">
     <img src="./imags/integral1d/volume_slice1.png" width="400" height="400"/>
  </a>
  </center>

当区间$[a,b]$被分割为：

<center>
  $a = x_0 < x_1 < \cdots < x_n = b$
</center>

则在$[x_{k-1},x_k]$区间上对应的几何体体积约为：

<center>
  $V_k = A(x_k)\Delta x_k$
</center>

其中$x_k = x_k - x_{k-1}, A_k$为$x = x_k$处的切面的面积。

  <center>
  <a href="https://www.pearsonhighered.com/thomas13einfo/">
     <img src="./imags/integral1d/volume_slice2.png" width="400" height="400"/>
  </a>
  </center>

所以几何体$S$的体积为：

<center>
  $V = \int_a^b A(x)\, \mathrm{d}x.$
</center>


---
**✏️例子**

设一个锥体高度为3米，地面为3米的正方形，其垂直于$x$轴的截面的边长为$x$米，求其体积。

  <center>
  <a href="https://www.pearsonhighered.com/thomas13einfo/">
     <img src="./imags/integral1d/volume_slice_exp1.png" width="400" height="400"/>
  </a>
  </center>

<details>
  解： $V \int_0^3 x^2\,\mathrm{d}x = \left[\dfrac{x^3}{3}\right]_0^3 = 9m^3$
</details>

---
**✏️例子**

祖暅原理
  <center>
  <a href="https://www.geogebra.org/3d/szc4qgum">
     <img src="./imags/integral1d/Cavalieri_principle.png" width="600" height="700"/>
  </a>
  </center>

---
**✏️例子**

求下列楔形几何体的体积
  <center>
  <a href="https://www.pearsonhighered.com/thomas13einfo/">
     <img src="./imags/integral1d/volume_slice_exp2.png" width="400" height="400"/>
  </a>
  </center>

<details>
解： 

$V = \int_a^b A(x)\, \mathrm{d}x = \int_0^3 2x \sqrt{9 - x^2}\, \mathrm{d}x = 18$

</details>

---

<a name="cotes3"></a>
## 📌**<span style="color:blue">3. 求平面曲线的弧长</span>**


  <center>
  <a href="https://www.geogebra.org/geometry/tevpmdxf">
     <img src="./imags/integral1d/Arc_length.png" width="600" height="700"/>
  </a>
  </center>

---

# Calculus and its Visualization: an Introduction

<center>
<a href="https://www.geogebra.org/material/edit/id/yxadpqun#bookcontent">
   <img src="./imags/surface.png" width="200" height="200"/>
</a>
</center>


---

# 👏 THANKS

<center>

<a href="https://www.geogebra.org">
   <img src="./imags/geogebra.png" width="200" height="60"/>
</a>

<a href="https://www.geogebra.org">
   <img src="./imags/github.png" width="200" height="60"/>
</a>

<a href="https://www.wikipedia.org/">
   <img src="./imags/wiki.png" width="200" height="50"/>
</a>
</center>
