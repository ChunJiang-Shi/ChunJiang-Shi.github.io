# Phase shifts in Resonance scattering 
This is my first note by markdown. Here I will write something useful to my future academy research.

## The frame transformation
We define the lab frame
$$
W_L=\sqrt{\vec{p}_1^2+m_\phi^2}+\sqrt{\vec{p}_2^2+m_\phi^2}.
$$

For the center of mass frame,
$$
W_{CM}=2\sqrt{p^{*2}+m_\phi^2}.
$$

The frame transformation follow by Lorentz transformation
$$
\vec{p}^*=\gamma(\vec{p_1}-v\sqrt{\vec{p_1}^2+m_\phi^2}),
$$
where $\vec{v}=\vec{P}/W_L$.
The lab frame total momentum $\vec{P}=\vec{p_1}+\vec{p_2}$, 


Specially,in the $\vec{P}=0$ case, we have the relation between $W$ and $L$,
$$
W_L = W_{CM} = 2\sqrt{m_\phi^2+(\vec{n}2\pi/L)^2}
$$

Besides, with lowest non-zero relative monmentum $P=2\pi/2$, 
$$
W_{CM}^2=W_L^2-\vec{P}^2=[\sqrt{\vec{p_1}+m_\phi^2}+\sqrt{\vec{p_2}+m_\phi^2}]-(2\pi/L)^2
$$
 
## How to calculate the  scattering phase shifts curve
This research program about $J/ \psi \pi$ scattering would be my graduate design, while it is my first research explording by myself and some infomation might be inaccurate.

Near the resonance energy $\sqrt{s}=m_R$, thr scattering amplitude $T(\sqrt{s})$ could be given by Breit Wigner form.
$$
T(\sqrt{s})=\frac{-\sqrt{s} \cdot \Gamma_R(\sqrt{s})}{s-m_R^2+i\sqrt{s}\Gamma_R(\sqrt{s})}
$$

Core formular:
$$
\begin{cases}
    \delta_0(p^*) = -\phi^{\vec{d}}(q) \text{mod}\pi\\
    q=\frac{p^*L}{2\pi}\\
    \tan(-\phi^{\vec{d}}(q))=\frac{\gamma q\pi^{3/2}}{Z_{00}^{\vec{d}}(1;q^2)}\\
    Z_{00}^{\vec{d}}=\frac{1}{\sqrt{4\pi}}\sum_{\vec{r}\in P_{\vec{d}}}(\vec{r}^2-q^2)^{-s}\\
    P_{\vec{d}}=\{ \vec{r}\in R^3| \vec{r} = \gamma^{-1} (\vec{n}+\vec{d}/2),\vec{n}\in Z^3 \}
\end{cases}
$$
