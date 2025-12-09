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
E_\textrm{kin} &= \frac{q_\alpha Q_{\textrm{AU}}}{4 \pi \epsilon_0 r} \;  \;  \;  \;  \; \biggr\rvert \div  E_\textrm{kin} ; \times r     \\
r &= \frac{q_\alpha Q_{\textrm{AU}}}{4 \pi \epsilon_0 E_\textrm{kin}}\\
 &= \frac{2 \times 79 \times (1.602 \times 10^{-19})^2 C^2 }{5.30 \times 1.602 \times 10^{-19} x 10^6 J} \times 9\times 10^9 \frac{N m^2}{C^2}\\
&= 4.3 \times 10^{-14} m \\ &= 43 fm
\end{align*}
$$

The $\alpha$ particles do not come closer than 43 fm to the nucleus - the nucleus therefore is smaller than this! (Compare with the Bohr radius of 0.053 nm which is ~1000 larger)

```


### Units

Particle physics uses a specific system of units which is designed to make calculations easier - This is in contrast to the system of units that is normally used within physics, the International System of Units (SI) which is metric and what you have been dealing with so far (and in future too).

Energy is generally measured in electron-Volt (eV). An electron volt is defined as the amount of kinetic energy gained by a single electron after being accelerated from rest through an electric potential difference of 1 Volt in vacuum:

$$ E_{\textrm{kin}} = q \times V $$

where $E_{\textrm{kin}}$ is the kinetic energy of the electron, $q$ is its charge and $V$ is the voltage (or voltage difference) with which it is accelerated. CHECK FOR REFERENCE TO 1st YEAR COURSE!
Given this definition, 1 eV $= 1.602 \times 10^{-19}$ J. So to convert from Joule into eV, one has to divide by $ 1.602 \times 10^{-19}$.

:::{admonition} Example
:class: tip
<b>Example: Mass of the Proton</b>

$$
\begin{align*}
m c^2 &= 1.67 \times 10^{-27} kg \times \left( 3 \times 10^8 m/s \right)^2 = 1.5 \times 10^{-9} J \\
1.5 \times 10^{-9} J &= 1.5 \times 10^{-9} / 1.6 \times 10^{-19}\; \textrm{eV} = 939 \;\; \textrm{MeV}
\end{align*}
$$

:::



In the system of units used in particle physics, the speed of light is set to $c=1$ and also $\hbar = 1$. These are so-called 'natural units'. This allows to have the same units for energy, momentum and mass, which simplifies calculations as there is no factors of $c^2$ to numerically take into account.

The barn is a unit of area which is used in cross-sections and integrated luminosity. One barn is equal to 10$^{-28}$ m$^2$ or 10$^{-24}$ cm$^2$. This is a larger area, common are cross-section smaller than mb or nb (millibarns and nanobarns).




### Rutherford scattering






```{admonition} Calculation

<b> Rutherford scattering angle</b>

Let us assume a parallel beam of incident particles A with particle ﬂux density J (with J = dN/dt) that passes through a layer of particles B in rest with density $n_\textrm{B}$. All particles A that pass through an annular with radius $b$ and width d$b$ around an atom B are deflected by the angle $theta \pm \textrm{d}\theta/2$. This assumes a sperically symmetric interaction potential: There is no prefered direction (along the ring with radius $b$). Per second, $ dJ = J dA = dN/dt dA = dN/dt 2\pi b db$ particles A pass through the annular ring. The fraction of all particles A (incident per unit area and per second onto the target) scattered through an interaction with one particle B into the range of deflection angles $\theta \pm \textrm{d}\theta/2 is therefore:

\begin{align*}
\frac{\mathrm{d} J (\theta \pm 1/2 \; \mathrm{d}\theta)}{J} = 2 \pi b \textrm{d}b = 2 \pi b \frac{\textrm{d}b}{\textrm{d} \theta} \textrm{d} \theta
\end{align*}



```












There are two types of fundamental particles: Matter particles (so-called fermions) and force particles (bosons).

#### Fermions: matter particles

The matter particles can be divided again into two classes: leptons and quarks. Leptons are either charged (electron, muon or tau) or neutral (all neutrinos). Quarks have non-integer charge of +2/3 or -1/3.  Every matter particle has an anti-particle with the same mass but opposite charge. This means, there are 24 matter particles within the Standard Model. Fermions can be grouped into so-called generations with the particles in the larger generations having the same properties (such as charge) but a larger mass. For example, the electron, muons and taus have the same charge, interact with the same forces and the same coupling strength but whilst the electron mass is 0.511 MeV, the muon mass is 103 MeV and the tau has a mass of 1777 MeV. 

*Table of Fermions*

