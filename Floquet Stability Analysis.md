Floquet multipliers are eigenvalues of the linearized Poincare map. 

>Ref. section 8.7 on Poincare Maps of Steven Strogatz's nonlinear dynamics and chaos.

Take the system. 
$$\begin{aligned}\dot{r} &= r(1-r^2)\\ \dot\theta &=1\end{aligned}$$
Take the section $\theta = 0$ . It can be shown that the Poincare map $r_{k+1} = P(r_k)$ is given by, 
$$r_{k+1} = [1+e^{-4\pi}(r_k^2-1)]^{-1/2}$$
Now linearize $P(r)$ about the fixed point $r_k*$ defined by $r* = P(r*)$ which gives $r*= 1$ . This corresponds to the stable limit cycle of the original dynamical system at $r=1$
Linearize around the fixed point,
$$P(r*+h) = P(r*)+P'(r*)h$$
Where $P'(r*) = e^{-4\pi}$
It means that if we perturb the fixed point by $h$ after one step the perturbation becomes $e^{-4\pi}$h, that is the perturbation grows as $\lambda^kh$ with $\lambda = e^{-4\pi}$ , this is called the Floquet multiplier of the dynamical system.


## Floquet exponent vs Floquet Multiplier

Floquet exponent of the continuous time system, denoted as $\sigma$ is defined by the equation: 
$$\lambda = e^{\sigma T}$$
where $T$ is the time period. 
