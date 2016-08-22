---
layout: post
title:  "Celestial mechanics"
date:   2016-06-27
excerpt: "Fundamentals of celestial mechanics disscussing 2 and 3 body problem and langrangian points"
tag:
comments: false
category: Resources
---
<center><h1>2 - Body Problem</h1></center>
If vectors are written without vector notation it represents the magnitude of the vector.<br>
<hr>Time Derivatives are represented by a “.” above them <br>
$$\dot{\vec{r}}=\frac{d \vec{r}}{dt}$$<br>
$$\ddot{\vec{r}}=\frac{d^2 \vec{r}}{dt^2} $$
<hr>

<br>Now, Equation of Motion
<br> $$\vec{F_1}=m_1 \dot{\vec{r_1}} ̇ ……(1)$$
<br> $$\vec{F_1}=\frac{Gm_1 m_2} {|r_{21} |^2}\hat{r_{21}}=\frac{Gm_1 m_2} {|r_{21} |^3}\vec{r_{21}}=-\left(\frac{Gm_1 m_2}{|r_{12}|^3}\right)\vec{r_{12}}$$
<br> Putting this value in (1) gives<br>
$$\ddot{\vec{r_1}}=-\left(\frac{Gm_2}{r_{12}^3} \right)\vec{r_{12}}……(2)$$
<br> Similarly<br>
$$\ddot{\vec{r_2}}=-\left(\frac{Gm_1}{r_{21}^3} \right)\vec{r_{21}}……(3)$$
<br> From (2) and (3)<br>
$$m_1 \ddot{\vec{r_1}}+m_2 \ddot{\vec{r_2}}=0$$
<br> Double Integrating<br>
$$m_1 \vec{r_1}+m_2\vec {r_2}=ct+d$$
<p>If we divide by $$m_1+m_2$$ we get $$r_{CM}$$ Since it is a linear function of t we can say that C.O.M. travels in a straight line.</p><br>
Subtracting (3) from (2). We get position vector of first body w.r.t. second body.<br>
$$\ddot{\vec{r_{12} }}=\ddot{\vec{r_1}}-\ddot{\vec{r_2}}=-\left(\frac{G}{r_{12}^3}\right)\left(m_2 \vec{r_{12}}-m_1 \vec{r_{21}}\right)$$
<br> Represent $$\vec{r_{12}}=-\vec{r_{21}}=\vec{r}$$ , $$|r_{12}|=r$$ and $$μ=G(m_1+m_2)$$ <br>
$$⇒\ddot{\vec{r}}+\frac{μ}{r^3}  \vec{r}=0$$
<hr>
<br><br>
Take cross product with $$\vec{r}$$ .
<br> Gives
<br> $$\ddot{\vec{r}}\times{\vec{r}}=0$$
<br> Also $$\frac{d}{dr}\left(\dot{\vec{r}}×\vec{r}\right)=\ddot{\vec{r}}\times\vec{r}$$ .
<br> Therefore Angular momentum per unit mass is constant i.e. $$\dot{\vec{r}}\times\vec{r}=h$$ 
<br> Where $$h$$ is a constant. Also Motion is planar since orbital plane is fixed. Polar coordinates can be used.
<br> Some Points
<br> $$\vec{r}={r} \hat{r}$$
$$\dot{\vec{r}}=\dot{r}\hat{r}+{r}\dot{\hat{r}}$$
$$\dot{\hat{r}}=\dot{θ}\hat{θ} $$ $$\dot{\hat{θ}}=-\dot{θ}\hat{r}$$
<br> This gives
$$\dot{\vec{r}}=\dot{r}\hat{r}+{r}\dot{\theta}\hat{θ}$$
<br> $$\ddot{\vec{r}}=\left(\ddot{r}-r\dot{θ}^2 \right)\hat{r}+\left(2\dot{r}\dot{θ}+r\ddot{θ}\right) \hat{θ}$$
<br> Now putting in above derived equation
<br>$$\ddot{\vec{r}}+\frac{\mu\hat{r}}{r^2}=0$$
<br> $$\ddot{\vec{r}}=-\left(\frac{\mu}{r^2}\right)\hat{r}$$
<br> $$\left(\ddot{r}-r\dot{θ}^2 \right)\hat{r}+\left(2\dot{r}\dot{θ}+r\ddot{θ}\right)\hat{θ}=-\left(\frac{\mu}{r^2}\right)\hat{r}$$
<br> Comparing
<br> $$\ddot{r}-r\dot{θ}^2 =-\left(\frac{\mu}{r^2}\right)......(4)$$
<br> $$2\dot{r}\dot{θ}+r\ddot{θ}=0......(5)$$
<br> in (5), Multiply both sides by $$r$$
<br>$$2r\dot{r}\dot{θ}+r^2\ddot{θ}=0$$
<br>$$\frac{d(r^2\dot{\theta})}{dt}=0$$
<br>$$r^2\dot{\theta}=h$$
<br>$$h$$ is same constant that we got earlier. Just writing it in different way.<br>
Now for (4)<br>
Substitute $$r=1/u$$
<br> $$\dot{r}=\frac{-1}{u^2}\cdot\dot{\theta}\left(\frac{du}{d\theta}\right)$$
<br> $$\dot{r}=-r^2\dot{\theta}\left(\frac{du}{d\theta}\right)$$
<br> from earlier $$r^2\dot{\theta}=h$$
<br> $$\dot{r}=-h\left(\frac{du}{d\theta}\right)$$
<br> $$\Rightarrow\ddot{r}=-h\dot{\theta}\left(\frac{d^2u}{d{\theta}^2}\right)$$
<br> Now (4) becomes
<br> $$h\dot{\theta}\left(\frac{d^2u}{d{\theta}^2}\right)-\frac{{\dot{\theta}}^2}{u}=-\mu u^2$$
<br> Simplyfying and using $$\dot{\theta}=u^2h$$. We get
<br> $$\frac{d^2u}{d\theta^2}+u=\frac{\mu}{h^2}$$
<br> Solving This gives
<br> $$u=\frac{\mu}{h^2}\left(1+cos(\theta-\overline{\omega})\right)$$
<br> $$\Rightarrow r=\frac{\frac{h^2}{\mu}}{1+cos(\theta-\overline{\omega})}$$
<br> $$\Rightarrow r=\frac{p}{1+{e}\cdot cos(\theta-{\omega})}=\frac{p}{1+{e}\cdot cos f}$$
<br> Here $$e$$ is eccentricity, $$f$$ is true anamoly or angle measured from major axis from closest distance of approach (Pericentre).
<br> $$p=\frac{h^2}{\mu}$$, 
<br> $$p$$ represents Semi-Latus Rectum of the orbit. 
<br> Centre is position of sun/star.
<br><center>======================image=======================</center><br>
<p> Planets have elliptical orbits because all other paths lead planets to be thrown away.</p>

 

| Eccentricity | Shape | Semi-Latus Rectum |
|:--------|:-------:|--------:|
| 0   | Circle   |  $$\frac{h^2}{\mu}$$  |
|  $$0\lt e\lt 1$$  | Ellipse   |  $$a(1-e^2)$$  |
|----
|  $$0\lt e\lt 1$$  | Parabola   |  $$2q$$  |
|  $$e\gt 1$$  | Hyperbola   |  $$a(e^2-1)$$  |
|=====
|    |    | 
 
 

<h3> Energy Relations determining orbit</h3>



|:--------|:-------:|--------:|
|$$T.E. \gt 0$$ |&nbsp;&nbsp;&nbsp;Hyperbola | &nbsp;&nbsp;&nbsp;Unbound >|
|$$T.E. = 0$$ |&nbsp;&nbsp;&nbsp;Parabola |&nbsp;&nbsp;&nbsp;Unbound |
|$$T.E. \lt 0$$ |&nbsp;&nbsp;&nbsp;Circle/Ellipse |&nbsp;&nbsp;&nbsp;Bound |
 
 <hr>

<h3>Analysis for Ellipse</h3>$$r_p=a(1-e)$$$$r_a=a(1+e)$$
<h4>Parametric Equation</h4>$$r=\frac{a(1-e^2)}{1+e\cdot \cos{f}}$$$$x=r\cos{f}$$$$y=r\sin{f}$$
<br> Area of ellipse 
$$A=\pi ab$ &amp $\frac{d}{dt}(A)=\frac{1}{2}h$$. if $$T$$ is orbital period.
<br> $$\Rightarrow \frac{\pi ab}{T}=\frac{1}{2}h$$
<br> Also
<br> $$a(1-e^2)=\frac{h^2}{\mu}$$$$h^2=a\mu(1-e^2)$$
<br> From above equations. We get
<br> $$\frac{4\pi^2a^2b^2}{T^2}=a\mu (1-e^2)$$$$\Rightarrow T^2=\left(\frac{4\pi^2}{\mu}\right)a^3$$
<br> This proves Kepler's 3<sup>rd</sup> Law in elliptical orbit and hence can be extended to other orbital shapes.
<br> Let $$m_s$$ and $$m_p$$ denote mass of sun and planet respectively.$$T^2=\left(\frac{4\pi^2}{G(m_s+m_p)}\right)a^3$$ 
<br> Also $m_s+m_p\approx m_s$. So for mass of sun.
<br> $$\Rightarrow m_s\approx \frac{4\pi^2a^3}{GT^2}$$
<hr>
<br> Starting again with our earlier derived equation
<br> $$\ddot{\vec{r}}+\frac{μ}{r^3}  \vec{r}=0$$ Take dot product with $$\dot{\vec{r}}$$
<br> $$\ddot{\vec{r}}\cdot\dot{\vec{r}}+\frac{\mu\vec{r}\cdot\dot{\vec{r}}}{r^3}=0$$
<br> Substituting $$\vec{r}={r} \hat{r}$ and $\dot{\vec{r}}=\dot{r}\hat{r}+{r}\dot{\theta}\hat{θ}$$
<br> $$\ddot{\vec{r}}\cdot\dot{\vec{r}}+\frac{\mu\left({r} \hat{r}\right)\cdot\left(\dot{r}\hat{r}+{r}\dot{\theta}\hat{θ}\right)}{r^3}=0$$
<br> $$\ddot{\vec{r}}\cdot\dot{\vec{r}}+\frac{\mu\dot{r}}{r^2}=0$$  This v can be written as
<br> $$\frac{d}{dt}\left(\frac{1}{2}|\dot{\vec{r}}|^2-\frac{\mu}{r}\right)=0$$
<br> <center>Now $$\dot{\vec{r}}=v$$ </center>
<br> $$\frac{d}{dt}\left(\frac{v^2}{2}-\frac{\mu}{r}\right)=0$$
<br> $$\Rightarrow \frac{v^2}{2}-\frac{\mu}{r}=c$$
<center> Total Energy is constant </center><hr>


Now finding that constant
<br> We know $h$ (Angular Momentum) and Energy are constant at apicentre and pericentre
<br>$$\Rightarrow h=r_av_a=r_pv_p$$. This gives $$v_p=\frac{r_a}{r_p} v_a$$
<br> $$\frac{v_a^2}{2}-\frac{\mu}{r_a}=\frac{v_p^2}{2}-\frac{\mu}{r_p}$$<center> Energy Conservation</center>
<br> $$\frac{v_a^2}{2}\left(\frac{r_a^2}{r_p^2}-1\right)=\mu\left(\frac{1}{r_p}-\frac{1}{r_a}\right)$$
<br> $$\frac{v_a^2}{2}=\frac{\mu}{r_p+r_a}\left(\frac{r_p}{r_a}\right)$$
<center>Now $$2a=r_p+r_a$$</center>
$$\frac{v_a^2}{2}=\frac{\mu}{2a}\left(\frac{2a-r_a}{r_a}\right)=\frac{\mu}{r_a}\left(1-\frac{r_a}{2a}\right)$$
<br> $$Total\space Energy = \frac{v_a^2}{2}+\frac{\mu}{r_a}=\frac{\mu}{2a}$$
<h4>Velocity in elliptical orbit</h4>
$$\frac{v^2}{2}+\frac{\mu}{r}=\frac{\mu}{2a}$$
<br> $$v^2=\mu\left(\frac{2}{r}-\frac{1}{a}\right)$$
<br> $$v=\sqrt{\mu\left(\frac{2}{r}-\frac{1}{a}\right)}$$
<br> Mean motion $$(n)=\frac{2\pi}{T}$$. We get
<br> $$\mu=a^3n^2$$. Putting this value we get
<br> $$v_p=na\sqrt{\frac{1+e}{1-e}}$$
<br> $$v_a=na\sqrt{\frac{1-e}{1+e}}$$
<h4>Energy for Ellipse</h4>
$$T.E.=-\frac{\mu}{2a}$$
<h4>Energy for Parabola</h4>
$$T.E.=0$$
<h4>Energy for Hyperbola</h4>
$$T.E.=\frac{\mu}{2a}$$
<hr><hr>














<center><h1>3 - Body Problem</h1></center>
Analysis of 3 Body problem is not very simple due to addition of various variables due to 3<sup>rd</sup> body.<br>
3 body problem can't be solved completely.
<h2> Restricted 3 Body problem</h2>
Let one of the masses is infinitesimal small. $$m_3\approx 0$$<br>
Now we have to solve equations only for $$m_3$$. Because for $$m_1$$ & $$m_2$$, it is like 2 body problem
<br> $$m_3\ddot{\vec{r_3}}=-\frac{Gm_1m_3\vec{r_{31}}}{r_{31}^3}-\frac{Gm_2m_3\vec{r_{32}}}{r_{32}^3}$$
<br> $$\ddot{\vec{r_3}}=-\frac{Gm_1\vec{r_{31}}}{r_{31}^3}-\frac{Gm_2\vec{r_{32}}}{r_{32}^3}$$
<br> Using Cartesian Coordinates
<br> $$\ddot{x}=-\frac{Gm_1(x-x_1)}{\sqrt{(x-x_1)^2+(y-y_1)^2+(z-z_1)^2}}$$
<br> $$\ddot{y}=-\frac{Gm_1(y-y_1)}{\sqrt{(x-x_1)^2+(y-y_1)^2+(z-z_1)^2}}$$
<br> $$\ddot{z}=-\frac{Gm_1(z-z_1)}{\sqrt{(x-x_1)^2+(y-y_1)^2+(z-z_1)^2}}$$
<hr><h2> Circular Restricted 3 body problem</h2>
Suppose that the first two masses, $$m_1$$ and $$m_2$$, execute circular orbits about their common center of mass.
<center><a href="http://farside.ph.utexas.edu/teaching/336k/Newtonhtml/img2483.png"><img src="http://farside.ph.utexas.edu/teaching/336k/Newtonhtml/img2483.png"></a></center>

Let us define a Cartesian coordinate system  $$(\xi,\,\eta,\,\zeta)$$ in an inertial reference frame whose origin coincides with the center of mass, $$C$$, of the two orbiting masses. Let the orbital plane of these masses coincide with the $$\xi$-$\eta$$ plane, and let them both lie on the $$\xi$$-axis at time $$t=0$$--see Figure. Suppose that $$R$$ is the constant distance between the two orbiting masses, $$r_1$$ the constant distance between mass $$m_1$$ and the origin, and $$r_2$$ the constant distance between mass $$m_2$$ and the origin. Moreover, let $$\omega$$ be the constant orbital angular velocity.

$$\begin{pmatrix}x\\y\\z\\\end{pmatrix}=\begin{pmatrix}\cos{\omega t}&&-\sin{\omega t}&&0\\\sin{\omega t}&&\cos{\omega t}&&0\\0&&0&&1\end{pmatrix}\begin{pmatrix}\xi\\\eta\\\zeta\end{pmatrix}$$
<br> Differentiate it twice put it in cartesian equations of motion of $m_3$. We get
<br> $$\ddot{\xi}-2\omega\eta=\frac{\partial\Bbb{U}}{\partial\xi}\cdots\cdots(7)$$
<br> $$\ddot{\eta}+2\omega\xi=\frac{\partial\Bbb{U}}{\partial\eta}\cdots\cdots(8)$$
<br> $$\ddot{\zeta}=\frac{\partial\Bbb{U}}{\partial\zeta}\cdots\cdots(9)$$
<br> <center>$$(7)\times\dot{\xi}+(8)\times\dot{\eta}+(9)\times\dot{\zeta}$$</center>
<br> $$\dot{\xi}\ddot{\xi}+\dot{\eta}\ddot{\eta}+\dot{\zeta}\ddot{\zeta}=\dot{\xi}\frac{\partial\Bbb{U}}{\partial\xi}+\dot{\eta}\frac{\partial\Bbb{U}}{\partial\eta}+\dot{\zeta}\frac{\partial\Bbb{U}}{\partial\zeta}\cdots\cdots(10)$$
<br> if $$\Bbb{U}=\Bbb{U}(\xi,\,\eta,\,\zeta)$$
<br> $$\Rightarrow \frac{d\Bbb{U}}{dt}=\frac{\partial\Bbb{U}}{\partial\xi}\cdot\frac{\partial\xi}{\partial t}+\frac{\partial\Bbb{U}}{\partial\eta}\cdot\frac{\partial\eta}{\partial t}+\frac{\partial\Bbb{U}}{\partial\zeta}\cdot\frac{\partial\zeta}{\partial t}$$
<br> It is R.H.S. of $$(10)$$. Also
<br> $$\frac{d}{dt}{\dot{\xi}}^2=2\dot{\xi}\ddot{\xi}$$
<br> eqn $(10)$ becomes
<br> $$\frac{1}{2}\frac{d}{dt}({\dot{\xi}}^2+{\dot{\eta}}^2+{\dot{\zeta}}^2)=\frac{d\Bbb{U}}{dt}$$
<br> We know ${\dot{\xi}}^2+{\dot{\eta}}^2+{\dot{\zeta}}^2=v^2$. 
<br> By Jacobi Integral <a href="http://farside.ph.utexas.edu/teaching/336k/Newtonhtml/node121.html">(External Link) - For Extra Information</a>
<br> $$v^2=2\Bbb{U}-C$$
<br> For $$v^2\ge 0$, $2\Bbb{U}\ge C$$. This gives 
<br> $$\Bbb{U}=\frac{\omega^2}{2}(\xi^2+\eta^2)+\frac{\mu_1}{r_1}+\frac{\mu_2}{r_2}$$
<br> If I term is large
<br> $$\xi^2+\eta^2\ge \frac{2C}{\omega^2}$$
<br> Path would be enclosing $$m_1$$ and $$m_2$$. On changing $$C$$ we get different Lagrangian Points
<hr><hr>
<center><h2> LAGRANGIAN POINTS </h2></center>
<center> <a href="https://en.wikipedia.org/wiki/Lagrangian_point">Wikipedia Article</a></center>
<p>In celestial mechanics, the Lagrangian points; also Lagrange points, L-points, or libration points) are positions in an orbital configuration of two large bodies where a small object affected only by gravity can maintain a <b>stable position</b> relative to the two large bodies. The Lagrange points mark positions where the combined gravitational pull of the two large masses provides precisely the centripetal force required to orbit with them. There are five such points, labeled L1 to L5, all in the orbital plane of the two large bodies. The first three are on the line connecting the two large bodies and the last two, L4 and L5, each form an equilateral triangle with the two large bodies. The two latter points are stable, which implies that objects can orbit around them in a rotating coordinate system tied to the two large bodies.L1, L2, L3 are unstable</p>
<center><a href="http://spaceguard.rm.iasf.cnr.it/NScience/neo/images/ast-lagr-points.gif"><img src="http://spaceguard.rm.iasf.cnr.it/NScience/neo/images/ast-lagr-points.gif"></a></center>

<p>We have considered $$m_2 \ll m_1$$</p>
<center>
<figure>
<img src="{{ site.baseurl }}/assets/img/resources/langrangian-table.PNG">
</figure>
 </center>
<hr>






