---
layout: article
title: Tìm điều kiện để hàm số đơn điệu
tags: [hàm-số, đơn-điệu]
mathjax: true
mathjax_autoNumber: true
---
**Bài 1.** Tìm tất cả các giá trị thực của tham số $ m $ để hàm số $$ f(x)=x^3-2mx^2+5x-4$$ đồng biến trên tập $ \mathbb{R} $.  
***Lời giải***
* Tập xác định của hàm số là $ \mathcal{D}=\mathbb{R}. $
* Đạo hàm: $ y'=3x^2-4mx+5 $
* Hàm số đồng biến trên tập $ R $ khi và chỉ khi  
$$y'=3x^2-4mx+5 \geq 0, \forall x\in \mathbb{R}$$
Do đây là một tam thức bậc hai có hệ số $ a=3>0 $ nên điều kiện cần và đủ là
$$\Delta'=2m^2-15 \leq 0$$
Giải bất phương trình này, chúng ta có đáp số $ m\in \left[-\sqrt{\frac{15}{2}};\sqrt{\frac{15}{2}}\right]. $

When $$a \ne 0$$, there are two solutions to $$ax^2 + bx + c = 0$$ and they are
$$x_1 = {-b + \sqrt{b^2-4ac} \over 2a}$$
$$x_2 = {-b - \sqrt{b^2-4ac} \over 2a} \notag$$