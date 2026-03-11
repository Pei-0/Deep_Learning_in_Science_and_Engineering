# HW5: Physics-informed Neural Network

## 📌 作業說明
本作業透過物理資訊神經網路(PINN)，求取一維波動方程式之解。

### 波動方程式

$$
\frac{\partial^2 E(x,t)}{\partial x^2}
-
c^2
\frac{\partial^2 E(x,t)}{\partial t^2}
=0
$$

$$
E(0,t)=E(1,t)=0, \quad t\in[0,1]
$$

$$
E(x,0)=\sin(\pi x)+\sin(A\pi x), \quad x\in[0,1]
$$

$$
\left.\frac{\partial E(x,t)}{\partial t}\right|_{t=0}=0, \quad x\in[0,1]
$$

### 分析解
$$
E(x,t)=\sin(\pi x)\cos(c\pi t)+\sin(A\pi x)\cos(Ac\pi t)
$$

## 🖼️ 求解結果
![PINN solution](.png)