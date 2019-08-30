---
layout: post
title: Tìm điều kiện để hàm số đơn điệu
author: bar
tags: [hàm-số, đơn-điệu]
categories: [ Toán-12 ]
image: assets/images/ham_so.jpg
beforetoc: "Bài giảng cung cấp cách giải và một số ví dụ tìm điều kiện của tham số để hàm số đồng biến hoặc nghịch biến trên một tập cho trước."
toc: true
mathjax: true
comments: true
featured: true
hidden: true
# rating: 4.5
---
**Bài 1.** Tìm tất cả các giá trị thực của tham số $ m $ để hàm số $ f(x)=x^3-2mx^2+5x-4$ đồng biến trên tập $ \mathbb{R} $.  
**Lời giải**
* Tập xác định: $ \mathcal{D}=\mathbb{R}. $
* Đạo hàm: $ y'=3x^2-4mx+5 $
* Hàm số đồng biến trên tập $ \mathbb{R} $ khi và chỉ khi  
<p style="text-align: center;">$$y'=3x^2-4mx+5 \geq 0, \forall x\in \mathbb{R}$$</p>
Do đây là một tam thức bậc hai có hệ số $ a=3>0 $ nên điều kiện cần và đủ là  
<p align="center">$$\Delta'=4m^2-15 \leq 0$$</p> 
Giải bất phương trình này, chúng ta có đáp số $ m\in \left[-\sqrt{\frac{15}{4}};\sqrt{\frac{15}{4}}\right]$.  

**Bài 2.** Tìm tất cả các giá trị thực của tham số $ m $ để hàm số $ f(x)=\dfrac{2x^2-5x+m}{x-2} $ đồng biến trên từng khoảng xác định.  
**Lời giải**  
* Tập xác định: $ \mathcal{D}=\mathbb{R}\setminus\\{2\\}. $
* Đạo hàm: $ y'= \dfrac{x^2-4x+10-m}{(x-2)^2}$
* Hàm số đồng biến trên từng khoảng xác định khi và chỉ khi. 
$$y'\geq 0,  \forall x\ne 2 $$
