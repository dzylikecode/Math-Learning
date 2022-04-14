---
title: README
date: 2022-04-02 20:55
---
# Fourier变换

## concept

- Fourier变换

![](./_image/2022-04-02/4757fe94931f6429300a76cb3f221c3a.jpg)

- Fourier逆变换

![](./_image/2022-04-02/a7f1dc8fbcbb68e27cf30397ceff2113.jpg)


> 抽象，关注整体的变换关系，用以下记法

![](./_image/2022-04-02/9def0ad04e945c19425c3b1481aead74.jpg)

![](./_image/2022-04-02/927f2c1ea82ef71a3d4aba19b21b905f.jpg)

> 可以说象函数F(w)和象原函数f(t)构成了一个Fourier变换对，它们有相同的奇偶性.
> 
> 考虑奇偶性，于是有正弦和余弦变换

![](./_image/2022-04-02/90644a6f2f14647fbdbf8852c6488f6a.jpg)

![](./_image/2022-04-02/56daccba76a1130ccc4b739de7c1b2e4.jpg)

![](./_image/2022-04-02/7a8eb681e6221d2692811951e803f533.jpg)

> 考虑象函数的关系，根据积分变换的核，很好猜出关系

![](./_image/2022-04-02/7c8153df15f1ce95c1fbd8db507a804e.jpg)


### exercise

![](./_image/2022-04-08/5b123e2780f8e08afa1f081a305d35b2.jpg)


![](./_image/2022-04-08/e6e0a6e912efcd6c1114504d646928cd.jpg)

> 可以看到 Laplace 变换的结构

![](./_image/2022-04-08/43bd7eec215a52edac2c001f82523d43.jpg)

![](./_image/2022-04-08/53d66c92fac0b6671113f4b18cfbd190.jpg)
首先,换元

![](./_image/2022-04-08/cdcdeeaa3f81122bd43aa86cd6595e6f.jpg)

转化积分路径

![](./_image/2022-04-08/c03300a1c4acd7da7d4511ad912e1435.jpg)

![](./_image/2022-04-08/eecfa13a908162a7600973dfc6ea28b5.jpg)

AD = BC = 0,AB = 高斯积分

![](./_image/2022-04-08/27ed23b49acb33316ec11f817bc31b93.jpg)

![](./_image/2022-04-08/56cab83ab0aba3850f5abef5289c41fa.jpg)


## 单位脉冲函数

对于许多集中于一点或一瞬时的量，例如点电荷、点热源、集中于一点的质量以及脉冲技术中的非常窄的脉冲等，就能够像处理连续分布的量那样，以统一的方式加以解决

δ-函数是一个广义函数，它没有普通意义下的“函数值”，所以，它不能用通常意义下“值的对应关系”来定义.在广义函数论中，δ-函数定义为某基本函数空间上的线性连续泛函

性质 1

![](./_image/2022-04-08/3035f5a3c92890a3eeb07dd20aaf7323.jpg)

性质 2:筛选性

![](./_image/2022-04-08/78c8bda483ea4025a9a0ab374f5d66ca.jpg)

> 也可用来作定义

![](./_image/2022-04-08/921aa75025f9ea4981378a09fbb7999f.jpg)


![](./_image/2022-04-08/b0a557df3bce0ef63cc50090bc12d698.jpg)

利用筛选性

![](./_image/2022-04-08/19278837b7974f1aafdaaf8fda07055c.jpg)

此处反常积分不是普通意义下的积分值.所以，δ(t)的Fourier变换是一种广义Fourier变换.

![](./_image/2022-04-08/a3c92cfba417b94172e63cefeaf55830.jpg)
> 利用逆变换证明












