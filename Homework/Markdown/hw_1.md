# <center>普通物理I <center>

## <center> 第一次作业<center>8

g=9.8m/s

### 1. 将一质量为 $m_1$ 的三角形劈，放在光滑的水平桌面上，另一质量为 $m_2$ 的立方体木块，沿三角形劈的光滑斜面自由下滑，如图所示. 求：

(1) 劈 $m_1$ 相对地面的加速度和木块 $m_2$ 相对劈的加速度；

(2) 欲使木块与劈之间无相对滑动，应该沿水平方向给劈多大的作用力？

![image-20251027034115708](C:\Users\ss\AppData\Roaming\Typora\typora-user-images\image-20251027034115708.png)

**解：**(1)

$m_2$ 在 $x$ 方向：$N \sin \theta = m_2 a_{2x}$

$m_2$ 在 $y$ 方向：$m_2 g - N \cos \theta = m_2 a_{2y}$

$m_1$ 在 $x$ 方向：$N \sin \theta = m_1 a_{1x}$

$\frac{a_{2y}}{a_{1x}} = \tan \theta$

解得：$a_{1x} = \frac{m_2 g \sin \theta \cos \theta}{m_1 + m_2 \sin^2 \theta}$  方向水平向右

$a_{2x} = \frac{m_1 g \sin \theta \cos \theta}{m_1 + m_2 \sin^2 \theta}$

$a_{2y} = \frac{(m_1 + m_2) g \sin^2 \theta}{m_1 + m_2 \sin^2 \theta}$

$a_相=\frac{(m_1 + m_2) g \sin \theta}{m_1 + m_2 \sin^2 \theta}$  方向与水平呈$\theta$角度斜向左下方



(2)

$\begin{cases} 
m_2 \text{在 } x \text{ 方向：} N \sin \theta = m_2 a_{2x} \\ 
m_2 \text{在 } y \text{ 方向：} m_2 g = N \cos \theta \\ 
m_1 \text{在 } x \text{ 方向：} F - N \sin \theta = m_1 a_{1x} 
\end{cases}$

解得 $F = (m_1 + m_2) g \tan \theta$



### 2. 从一个半径为 $R$ 的均匀薄板上挖去一个直径为 $R$ 的圆板，所形成的圆洞中心在距原薄板中心 $R/2$ 处，所剩薄板的质量为 $m$. 求此时薄板对于通过原中心而与板面垂直的轴的转动惯量. 

![image-20251027034132657](C:\Users\ss\AppData\Roaming\Typora\typora-user-images\image-20251027034132657.png)

**解：**$J_R = \frac{1}{2} \cdot \frac{4m}{3} R^2 = \frac{2}{3} mR^2$

$J_r = \frac{1}{2} \cdot \frac{m}{3} \left( \frac{R}{2} \right)^2 + \frac{m}{3} \left( \frac{R}{2} \right)^2$
$= \frac{1}{24} mR^2 + \frac{1}{12} mR^2 = \frac{1}{8} mR^2$

$J_{\text{剩}} = \left( \frac{2}{3} - \frac{1}{8} \right) mR^2$
$= \frac{16}{24} mR^2 - \frac{3}{24} mR^2 = \frac{13}{24} mR^2$



### 3. 一根均匀米尺（长度 $1\text{m}$），在 $60\text{cm}$ 刻度处被钉到墙上，且可以在竖直平面内自由转动. 先用手使米尺保持水平，然后释放. 求刚释放时米尺的角加速度和米尺到竖直位置时的角速度各是多大？

**解：**

刚释放：$M = J \beta$

$0.6m \times 0.3l \cdot g - 0.4m \times 0.2l \cdot g = \left( \frac{1}{12} ml^2 + m \cdot dl^2 \right) \beta$

$\beta = \frac{15}{14} \frac{g}{l} = 10.5 \, \text{rad/s}^2$

竖直：$mg \cdot 0.1l = \frac{1}{2} J \omega^2$

$\omega = \sqrt{\frac{0.2 mgl}{J}}$

$= \sqrt{\frac{0.2 gl}{\frac{1}{12} l^2 + 0.01 l^2}} = 4.6 \, \text{rad/s}$



### 4. 宇宙飞船中有三个宇航员绕着船舱环形内壁按同一方向跑动以产生人造重力. 

（1）如果想使人造重力等于他们在地面上时受到的自然重力，那么他们跑动的速率应多大？设他们的质心运动半径为 $2. 5\text{m}$，人体当质点处理. 

（2）如果飞船最初未动，当宇航员按上面速率跑动时，飞船将以多大角速度旋转？设每个宇航员的质量为 $70\text{kg}$，飞船船体对于其纵轴的转动惯量为 $3 \times 10^5  \text{kg} \cdot \text{m}^2$. 

（3）要使飞船转过 $30^\circ$，宇航员需要跑几圈？

**解：**

(1) $mg = m \frac{v^2}{r}$  
$v = \sqrt{gr} = 5.0 \, \text{m/s}$

(2)  
$3mvr = J\omega$  
$\omega = \frac{3mvr}{J} = 8.75 \times 10^{-3} \, \text{rad/s}$

(3)  
$t = \frac{\theta}{\omega}$  
$n = \frac{v \cdot \frac{\theta}{\omega}}{2\pi r} = \frac{v\theta}{2\pi r\omega} = 19$