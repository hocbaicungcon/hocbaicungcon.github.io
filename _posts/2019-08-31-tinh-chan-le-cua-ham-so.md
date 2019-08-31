---
layout: post
title: Tính chẵn lẻ của hàm số lượng giác
author: bar
tags: [lượng giác, tính chẵn lẻ]
categories: [ Toán 11 ]
image: assets/images/luong_giac.jpg
# beforetoc: "Bài tập chương I, ứng dụng đạo hàm để khảo sát và vẽ đồ thị hàm số."
toc: true
mathjax: true
comments: true
featured: true
<!-- hidden: true -->
---

**Bài toán.** Xét tính chẵn lẻ của một hàm số lượng giác.

Trước hết, ta nhớ lại một hàm số $ f(x) $ được gọi là chẵn nếu nó thỏa mãn hai điều kiện sau:
- Tập xác định $ \mathcal{D} $ của nó phải là một tập đối xứng, nghĩa là nếu $ x\in \mathcal{D} $ thì $ -x\in \mathcal{D} $,
- Điều kiện thứ hai là $ f(-x)=f(x) $ với mọi $ x\in \mathcal{D}. $

Tương tự, nếu điều kiện thứ hai được thay thế bằng: $ f(-x)=-f(x) $ với mọi $ x\in \mathcal{D}, $ thì hàm số $f(x)$ được gọi là hàm số lẻ.

Đối với một hàm số lượng giác, chúng ta chú ý thêm tính chất:
- $ \cos (-x) = \cos x$
- $ \sin (-x) = -\sin x $
- $ \tan (-x) = -\tan x $
- $ \cot (-x) = -\cot x $

Đồ thị của một hàm số chẵn thì đối xứng qua trục tung, đồ thị hàm số lẻ thì đối xứng qua gốc tọa độ.

**Ví dụ 1.** Xét tính chẵn lẻ của hàm số
$$ f(x)=|\sin x| + \cos x $$.

Chúng ta có tập xác định $ \mathcal{D}=\mathbb{R} $, do đó điều kiện thứ nhất được thỏa mãn. Ta xét điều kiện thứ hai, có
<p align="center"> $$ f(-x)=|\sin(-x)|+\cos(-x)=|-\sin x|+\cos x=|\sin x|+\cos x=f(x) $$</p>
Như vậy, hàm số đã cho là hàm số chẵn.


**Ví dụ 2.** Xét tính chẵn lẻ của hàm số
$$ f(x)=\tan x + 2\sin x $$.

Chúng ta có tập xác định $ \mathcal{D}=\mathbb{R}\setminus\\{\frac{\pi}{2}+k\pi\\} $.
<p align="center"> $ \forall x\in \mathcal{D} $ thì $ x\ne \frac{\pi}{2}+k\pi $ nên $ -x\ne -\frac{\pi}{2}-k\pi $.</p>
Chú ý rằng $ k $ là toàn bộ các số nguyên nên suy ra $ -x $ cũng thuộc tập xác định. Do đó điều kiện thứ nhất được thỏa mãn. Ta xét điều kiện thứ hai, có
<p align="center"> $$ f(-x)=\tan(-x)+2\sin(-x)=-\tan x-2\sin x=-f(x) $$</p>
Như vậy, hàm số đã cho là hàm số lẻ.