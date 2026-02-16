# <center>hw_2<center>

### 1. 大本钟的分针长 4.5m，质量为 100kg，时针长 2.7m，质量为 60kg。二者对中心轴的角动量和转动动能各是多少？将二者都当成均匀细直棒处理。

**解：**

分针  
$$
L_1 = I_1 \omega_1 = \frac{1}{3} m_1 L_1^2 \cdot \frac{2\pi}{T_1}  = \frac{3}{8}\pi \, \text{J·s}
$$
$$
K_1 = \frac{1}{2} I_1 \omega_1^2 = \frac{1}{2} \times \frac{1}{3} m_1 L_1^2 \cdot \frac{4\pi^2}{T_1^2}  = \frac{\pi^2}{9600} \, \text{J}
$$

时针  
$$
L_2 = I_2 \omega_2 = \frac{1}{3} m_2 L_2^2 \cdot \frac{2\pi}{T_2}= \frac{145.8\pi}{21600} 
$$
$$
K_2 = \frac{1}{2} I_2 \omega_2^2 = \frac{1}{2} \times \frac{1}{3} m_2 L_2^2 \cdot \frac{4\pi^2}{T_2^2}  = \frac{72.9\pi^2}{466560000} \, \text{J}
$$



### 2. 唱机的转盘绕着通过盘心的固定竖直轴转动，唱片放上去后将受转盘的摩擦力作用而随转盘转动。设唱片可以看成是半径为 $R$ 的均匀圆盘，质量为 $m$，唱片和转盘之间的滑动摩擦系数为 $\mu_k$。转盘原来以角速度 $\omega$ 匀速转动，唱片刚放上去时它受到的摩擦力矩多大？唱片达到角速度 $\omega$ 需要多长时间？在这段时间内，转盘保持角速度 $\omega$ 不变，驱动力矩共做了多少功？唱片获得了多大动能？

<img src="C:\Users\ss\AppData\Roaming\Typora\typora-user-images\image-20251112034017284.png" alt="image-20251112034017284" style="zoom:50%;" />

**解：**

(1) 摩擦力矩  
$$
\tau = \mu_k mg  R 
$$

(2) 角加速度和时间  
$$
\alpha = \frac{\tau}{I} = \frac{\mu_k mgR}{\frac{1}{2}mR^2} = \frac{2\mu_k g}{R}
$$
$$
t = \frac{\omega}{\alpha} = \frac{\omega}{\frac{2\mu_k g}{R}} = \frac{R\omega}{2\mu_k g}
$$

(3) 驱动力矩做功  
$$
W = \tau \theta = \tau \omega t = \mu_k mgR \cdot \omega \cdot \frac{R\omega}{2\mu_k g} = \frac{1}{2}mR^2\omega^2
$$

(4) 唱片获得的动能  
$$
K = \frac{1}{2}I\omega^2 = \frac{1}{2} \cdot \frac{1}{2}mR^2 \cdot \omega^2 = \frac{1}{4}mR^2\omega^2
$$



### 3. 两个滑冰运动员，体重都是 60kg，他们以 6.5m/s 的速率垂直地冲向一根 10m 长细杆的两端，并同时抓住它，如本题图所示。若将每个运动员看成一个质点，细杆的质量可以忽略不计。

<img src="C:\Users\ss\Documents\Tencent Files\3434725684\nt_qq\nt_data\Pic\2025-11\Ori\b6056ce7ac11071787bcb5d3b1cff354.png" alt="b6056ce7ac11071787bcb5d3b1cff354" style="zoom: 33%;" />

#### （1）求他们抓住细杆前后对于其中点的角动量；

#### （2）他们每人都用力往自己一边收细杆，当他们之间距离为 5.0m 时，各自的速率是多少？

#### （3）求此系杆中的张力；

#### （4）计算每个运动员在减少他们之间距离的过程中所作的功，并证明这功恰好等于他们动能的变化。

**解：**

(1) 抓住细杆前的角动量  
$$
L = 2mv  d  = 3900 \, \text{kg·m}^2/\text{s}
$$

(2) 收杆后的速率  
$$
I = 2m d^2  = 3000 \, \text{kg·m}^2
$$
$$
\omega = \frac{L}{I} = \frac{3900}{3000} = 1.3 \, \text{rad/s}
$$
$$
V = \omega d = 1 6.5 \, \text{m/s}
$$
距离为 5.0m 时：  
$$
d' = 2.5 \, \text{m}, \quad I' = 2m d^2  = 750 \, \text{kg·m}^2
$$
$$
\omega' = \frac{d}{I'} = \frac{3900}{750} = 5.2 \, \text{rad/s}
$$
$$
V' = \omega' \cdot d = 5.2 \times 2.5 = 13 \, \text{m/s}
$$

(3) 细杆中的张力  
$$
T = m\omega^2 d = 4056 \, \text{N}
$$

(4) 运动员做功  
$$
\Delta E_k = E_{k2} - E_{k1} = \frac{1}{2}I'\omega'^2 - \frac{1}{2}I\omega^2
$$
$$
= \frac{1}{2} \times 750 \times (5.2)^2 - \frac{1}{2} \times 3000 \times (1.3)^2 = 7605 \, \text{J}
$$
$$
W = \frac{\Delta E_k}{2} = 3802.5 \, \text{J}
$$



### 4. 质量为 $M$ 的均匀空心圆柱，其内外半径为 $R_1$ 和 $R_2$，求对过中心轴的转动惯量。

<img src="C:\Users\ss\AppData\Roaming\Typora\typora-user-images\image-20251112034118758.png" alt="image-20251112034118758" style="zoom:80%;" />

**解：**
$$
\rho = \frac{M}{V} = \frac{M}{\pi (R_2^2 - R_1^2)H}
$$

外圆柱 $C_2$：
$$
M_2 = \rho V_2 = \rho \pi R_2^2 H = \frac{MR_2^2}{R_2^2 - R_1^2}
$$
$$
I_2 = \frac{1}{2} M_2 R_2^2 = \frac{1}{2} M \frac{R_2^4}{R_2^2 - R_1^2}
$$

内圆柱 $C_1$（挖空部分）：
$$
M_1 = \rho V_1 = \rho \pi R_1^2 H = \frac{MR_1^2}{R_2^2 - R_1^2}
$$
$$
I_1 = \frac{1}{2} M_1 R_1^2 = \frac{1}{2} M \frac{R_1^4}{R_2^2 - R_1^2}
$$

空心圆柱转动惯量：
$$
I = I_2 - I_1 = \frac{1}{2} M \frac{R_2^4 - R_1^4}{R_2^2 - R_1^2} = \frac{1}{2} M (R_1^2 + R_2^2)
$$