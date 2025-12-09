# Part 1: Investigating the microscopic World

## Resolving small structures

### Examples



:::{admonition} Example
:class: tip
<b>Example: Wavelength of a proton travelling with $v=0.01c$</b>

$$
\begin{align*}
\lambda &= \frac{h}{p} \\
&= \frac{h}{m\times v} \\
&= \frac{6.625 \times 10^{-34}\, m^2 \, kg\, s^{-1}}{1.67 \times 10^{-27} kg \times 3 \times 10^6 \; m\, s^{-1}} = \frac{6.625 \times 10^{-34}\, m^{\cancel{2}}\, \cancel{kg}\, \cancel{s^{-1}}}{1.67 \times 10^{-27} \cancel{kg} \times 3 \times 10^6\, \cancel{m}\, \cancel{s^{-1}}} \\ \\
&= 1.32 \times 10^{-8} m = 132 fm
\end{align*}
$$

:::



### The Geiger Marsden Experiment


```{admonition} Calculation

<b> Scattering angle in the Geiger Marsden Experiment</b>

<img src="rutherfordscattering.png" alt="Vectors in Elastic scattering" width="300"/>

Energy conservation:   $\,\,\,\,\,\,\,\,\,\, \frac{1}{2} m_\alpha {v^2_\alpha} = \frac{1}{2} m_\alpha {v'^2_\alpha} + \frac{1}{2} m_t {v'^2_t}$ <br>
Momentum conservation: $\,\,\, m_\alpha \vec{v_\alpha} = m_\alpha \vec{v'_\alpha} + m_t \vec{v'_t}$ <br>

Energy conservation:<br>
\begin{align*}
\frac{1}{2} m_\alpha {v^2_\alpha} &= \frac{1}{2} m_\alpha {v'^2_\alpha} + \frac{1}{2} m_t {v'^2_t} &\biggr\rvert \div\frac{1}{2} \\
m_\alpha {v^2_\alpha} &=  m_\alpha {v'^2_\alpha} +  m'_t {v'^2_t}  &\biggr\rvert \; \textrm{multiply by  } m_\alpha \\
m^2_\alpha {v^2_\alpha} &=  m^2_\alpha {v'^2_\alpha} +  m_\alpha m_t {v'^2_t} &
\end{align*}


Momentum conservation:<br>
\begin{align*}
m_\alpha \vec{v_\alpha} &= m_\alpha \vec{v'_\alpha} + m'_t \vec{v'_t} \; &\biggr\rvert \; \textrm{square both sides} \\
m^2_\alpha {v^2_\alpha} &= m^2_\alpha {v'^2_\alpha} + m^2_t {v'^2_t} + 2 m_\alpha m_t \vec{v'_\alpha}\cdot \vec{v'_t} \\
\end{align*}

Now set (2) and (3) equal:
\begin{align*}
\cancel{m^2_\alpha {v'^2_\alpha}} +  m_\alpha m_t {v'^2_t} &= \cancel{m^2_\alpha {v'^2_\alpha}} + m^2_t {v'^2_t} + 2 m_\alpha m_t \vec{v'_\alpha}\cdot \vec{v'_t} \\
m_\alpha m_t {v'^2_t} &= m^2_t {v'^2_t} + 2 m_\alpha m_t \vec{v'_\alpha}\cdot \vec{v'_t} \;\;\;\biggr\rvert \; - m^2_t {v'^2_t}, \div m_\alpha m_t  \\
{v'^2_t} \left(1 - \frac{m_t}{m_\alpha}\right) &= 2 \vec{v'_\alpha}\cdot \vec{v'_t} \\
{v'^2_t} \left(1 - \frac{m_t}{m_\alpha}\right) &= 2 {v'_\alpha}{v'_t} \cos\theta \\
\end{align*}


```




$${v'^2_t} \left(1 - \frac{m_t}{m_\alpha}\right) &= {v'_\alpha}{v'_t} \cos\theta \\
$$




```{admonition} Calculation

<b>Resolution / Distance of closest approach in the Geiger Marsden Experiment</b>

The potential energy of the alpha particle with charge $q_\alpha$ at a distance $r$ from the gold nuclei with charge $Q_{\textrm{AU}}$ is:

$$
U = E_\textrm{pot} = \frac{q_\alpha Q_{\textrm{AU}}}{4 \pi \epsilon_0 r}
$$
(see also PHY11006 lecture notes: \textit{5.5 The Potential and Potential Energy of a System of Charges})

The $\alpha$ particles and the gold nuclei repell each other as they are both positively charged. In order to estimate how close they can get, we can compare the kinetic energy of the $\alpha$ particles to the potential energy caused by the charges. The kinetic energy is "used up" in order to overcome the repelling force of the electric field of the nuclei. Thus, the Kinetic energy (at t=0, i.e. when the particle approach from infinity) and potential energy are equal at the "distance of closest approach", the point at which the $\alpha$ particles are the closest to the gold nuclei, before they are deflected away from the nuclei.

The kinetic energy of the $\alpha$ particles in the Geiger Marsden experiment is $E_\textrm{kin} = 5.30$ MeV. The charges of the $\alpha$ particles and the gold nuclei are $q_\alpha = 2$e and $Q_\textrm{AU}=79$e respectively.

$$
\begin{align*}
E_\textrm{kin} &= E_\textrm{pot} \\
E_\textrm{kin} &= \frac{q_\alpha Q_{\textrm{AU}}}{4 \pi \epsilon_0 r} \; &\biggr\rvert \div  E_\textrm{kin} ; \times r     \\
r &= \frac{q_\alpha Q_{\textrm{AU}}}{4 \pi \epsilon_0 E_\textrm{kin}}\\
r &= \frac{2 \times 79 x (1.602 \times 10^{-19})^2 C^2 }{5.30 \times 1.602 \times 10^{-19} x 10^6 J} \times 9\times 10^9 \frac{N m^2}{C^2} = 4.3 \times 10^{-14} m = 43 fm
\end{align*}
$$

The $\alpha$ particles do not come closer than 43 fm to the nucleus - the nucleus therefore is smaller than this! (Compare with the Bohr radius of 0.053 nm which is ~1000 larger)

```



There are two types of fundamental particles: Matter particles (so-called fermions) and force particles (bosons).

#### Fermions: matter particles

The matter particles can be divided again into two classes: leptons and quarks. Leptons are either charged (electron, muon or tau) or neutral (all neutrinos). Quarks have non-integer charge of +2/3 or -1/3.  Every matter particle has an anti-particle with the same mass but opposite charge. This means, there are 24 matter particles within the Standard Model. Fermions can be grouped into so-called generations with the particles in the larger generations having the same properties (such as charge) but a larger mass. For example, the electron, muons and taus have the same charge, interact with the same forces and the same coupling strength but whilst the electron mass is 0.511 MeV, the muon mass is 103 MeV and the tau has a mass of 1777 MeV. 

*Table of Fermions*

