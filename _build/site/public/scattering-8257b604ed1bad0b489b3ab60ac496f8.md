# Part 1: Investigating the microscopic World

## Resolving small structures

Light is a powerful tool for exploring structures, but its wavelength fundamentally limits the resolution achievable. At the end of the 16th century, the microscope was invented to resolve and observe small structures, initially mainly biological samples such as seeds, plants, the eye of a fly and the structure of cork. Hooke, one of the first to use a microscope described the pores inside the cork as ‘cells', the origin of the current use of the word in biology today.

In the classical limit, the smallest detail resolvable by conventional microscopy is approximately half the wavelength (2$\lambda$) of the light used. For visible light, this resolution limit is around 200-250 nanometers (nm), which is sufficient for resolving cells and large organelles, but far too large for atomic or molecular structures.

To resolve smaller structures like single crystals and individual atoms, which have characteristic spacings on the scale of $\approx 0.1$ to $1 \text{ nm}$ (or $1$ to $10 \text{ Angstroms}$), researchers must use "light" with a much shorter wavelength. For this, X-rays are commonly used as these have wavelengths comparable to the interatomic spacing in crystals. This allows for the determination of the atomic structure of crystals down to resolutions of $0.1 \text{ nm}$ or better, effectively resolving the positions of the constituent atoms.

To resolve structures smaller than the size of an atom's position, one must move beyond using light (photons) and instead employ beams of high-energy fundamental particles, such as electrons or other particles. The key principle remains the same as with light: to resolve a feature, the probe's de Broglie wavelength ($\lambda$) must be comparable to or smaller than the feature's size. High-energy electrons can have de Broglie wavelengths of less than $0.004 \text{ nm}$, significantly shorter than the atomic spacing of $\approx 0.1 \text{ nm}$. This extremely small wavelength allows modern electron microscopes to not only resolve the regular positions of atoms in a crystal lattice but also to image individual atoms and distinguish different elements within a material, achieving resolutions approaching $0.05 \text{ nm}$.

:::{admonition} Equation
:class: Warning
<b>The de Broglie wavelength</b>

In SI units (i.e. the international system of units {cite}`SIunits`) the de Broglie wavelength is defined as:
$$
\lambda = \frac{h}{p} \\
$$

Here, $\lambda$ is the wavelength, $h$ is the Planck constant, $p$ is the momentum with $h = 6.626 \times 10^{-34} m^2$ kg/s $=  6.626 \times 10^{-34} J s $
:::

Nuclear and Particle physics requires going to even smaller scales: Electrons and protons are most often used in order to test the structure of matter. Even when accelerated to modest velocities, they can probe features much smaller than atoms.

:::{admonition} Example
:class: tip
<b>Example: Wavelength of a proton travelling with $v=0.01c$</b>

$$
\begin{align*}
\lambda &= \frac{h}{p} \\
&= \frac{h}{m\times v} \\
&= \frac{6.625 \times 10^{-34}\, m^2 \, kg\, s^{-1}}{1.67 \times 10^{-27} kg \times 3 \times 10^6 \; m\, s^{-1}} = \frac{6.625 \times 10^{-34}\, m^{\cancel{2}}\, \cancel{kg}\, \cancel{s^{-1}}}{1.67 \times 10^{-27} \cancel{kg} \times 3 \times 10^6\, \cancel{m}\, \cancel{s^{-1}}} \\ \\
&= 1.32 \times 10^{-13} m = 132 fm
\end{align*}
$$

A Proton with a velocity of 1\% of the speed of light can probe structures more than a magnitude smaller as those accessible with X-Ray microscopes. Protons in
:::

## The Geiger-Marsden experiment

The Geiger-Marsden experiment, also known as the Rutherford experiment, is an experiment conducted in 1909 by Hans Geiger and Ernest Marsden under the guidance of Ernest Rutherford at the University of Manchester. The experiment was part of a series of experiments performed between 1906 and 1913 that investigated the atomic structure.

The experiment involved positively charged $\alpha$ particles (Helium nuclei consisting of two protons and two neutrons) that were guided in a beam at a thin sheet of gold foil. The source of the $\alpha$ particles was radium, as it was one of the most radioacive elements known at that time. Gold was chosen for the foil as it is the most malleable metal and therefore easiest material to manufacture a thin foil with. The deflection of the $\alpha$ particles was measured using a phosphorescent screen surrounding the gold foil. Each particle impacting on the screen produced a tiny flash of light that was detected "by eye": Geiger worked in a darkened laboratory for hours, counting the scintillations using a microscope and noting the results down.

The results showed that most alpha particles passed straight through the foil however some were deflected at large angles of more than 90 degrees and even up to 180 degrees. This disproved the plum pudding model of the atom that had been proposed by Thompson.

Rutherford drew the conclusion that atoms have a small, dense, positively charged nucleus as explained in his 1911 paper{cite}`Rutherford:1911zz` that eventually led to the widespread use of scattering in particle physics to study subatomic matter. The paper was primarily about alpha particle scattering in an era before particle scattering was a primary tool for physics.

In the following we will see how scattering experiments are used as a tool to understand the basic constituents of matter. The Geiger Marsden experiment is used to demonstrate the basic principles of these measurements.


```{admonition} Calculation
:class: Info

<b> Scattering angle in the Geiger Marsden Experiment</b>

From the scattering measured in the experiment, we can deduce something on the relationship of the $\alpha$ particles and the gold atoms (or the scattering centre).

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
{v'^2_t} \left(1 - \frac{m_t}{m_\alpha} \right) &= 2 \vec{v'_\alpha}\cdot \vec{v'_t} \\
{v'^2_t} \left(1 - \frac{m_t}{m_\alpha}\right) &= 2 {v'_\alpha}{v'_t} \cos\theta \\
\end{align*}


```

From the above calculation using energy and momentum conservation, we deduce the following relationship:

$${v'^2_t} \left(1 - \frac{m_t}{m_\alpha}\right) = {v'_\alpha}{v'_t} \cos\theta $$

We can analyse the equation without even knowing much about the concrete values:

Looking at the right-hand side, we find we have the multiplication of two velocities - this product is for sure positive (as there are not negative velocities). The other term on the right-hand side is $\cos\theta$ which is positive between -90$\degree$ and +90$\degree$. However, $\cos\theta$ is negative for any angles larger than 90$\degree$. So the right-hand side takes on a \textit{negative} value for scattering angles larger than 90$\degree$. This of course means, that also the left-hand side needs to be negative in these cases.

Therefore, let's take a look at the left-hand side of the equation. Again, ${v'^2_t}$ will always be positive, so $\left(1 - \frac{m_t}{m_\alpha}\right)$ needs to be negative, i.e. zero is larger than the left-hand side:

$$
\begin{align*}
0&>\left(1 - \frac{m_t}{m_\alpha}\right)\\
\frac{m_t}{m_\alpha} &> 1\\
m_t &> m_\alpha
\end{align*}
$$

This shows that the target mass is larger than that of the $\alpha$ particle. In fact it's much larger by roughly a factor of 40: M(Au) $\sim$ 40 $\times$ M(alpha). This indicates, there is a solid heavy "ball" inside the atom, not a soft distributed mass.

There is more we can learn, again using energy conservation. When the positively charged $\alpha$ particle approaches the also positively charged gold nucleus it experiences a repelling force and as a consequence its kinetic energy gets converted into potential energy until it (equivalent to a ball that is tossed into the air with an initial velocity, its kinetic energy gets converted into potential energy in the gravitational field of the earth until its velocity at its highest point is zero, at which point it turns to be accelerated by the gravitational towards earth).

Using this approach we can estimate the size of an atomic nuclei as we can estimate how close the $\alpha$ particles get towards it.

(sizeofAU)=
```{admonition} Calculation

<b>Distance of closest approach in the Geiger Marsden Experiment</b>

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

The $\alpha$ particles do not come closer than 43 fm to the nucleus - the nucleus therefore is smaller than this! (Compare with the Bohr radius of 0.053 nm which is $\sim$1000 larger)

```

## General Basics of scattering experiments in High energy physics


Particle physics uses a specific system of units which is designed to make calculations easier - This is in contrast to the system of units that is normally used within physics, the International System of Units (SI) ({cite}`SIunits`)  which is metric and what you have been dealing with so far (and in future too).

Energy is generally measured in electron-Volt (eV). An electron volt is defined as the amount of kinetic energy gained by a single electron after being accelerated from rest through an electric potential difference of 1 Volt in vacuum:

$$ E_{\textrm{kin}} = q \cdot V $$

where $E_{\textrm{kin}}$ is the kinetic energy of the electron, $q$ is its charge and $V$ is the voltage (or voltage difference) with which it is accelerated. Given this definition, 1 eV $= 1.602 \times 10^{-19}$ J. So to convert from Joule into eV, one has to divide by $ 1.602 \times 10^{-19}$.

The unit eV is used to not only measure energy but also to measure momentum and mass. In particle physics, the relationship between energy, momentum and mass is derivated using special relativity and can be expressed in this simple formula:

:::{admonition} Equation
:class: Warning
<b>Relativistic relationship between energy, momentum and mass</b>

$$
E^2 = p^2 c^2 + m^2 c^4 \\
$$

Here, $E$ is the energy, $p$ is momentum, $m$ is mass and $c$ is the speed of light. In the case, that the kinetic energy of a particle can be neglected with respect to its mass, $E=mc^2$, the well-known Einstein formula. In cases, where the kinetic energy of a particle excess its mass, we can write $E=pc$. For most of the cases in this course, we will use $E=pc$ unless stated otherwise.
:::

Given the relativistic relationship between energy, momentum and mass, the unit of momentum is eV/$c$, whilst mass is eV/$c^2$


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

It is useful to be mindful of unit prefixes, as these will be used throughout the course and are generally useful for the course of your degree.

| Prefix   | Symbol | Factor             | Power    |
|----------|--------|--------------------|----------|
| tera     | T      | 1,000,000,000,000  | 10$^{12}$|
| giga     | G      | 1,000,000,000      | 10$^{9}$ |
| mega     | M      | 1,000,000          | 10$^{6}$ |
| kilo     | k      | 1,000              | 10$^{3}$ |
| milli    | m      | 0.001              | 10$^{-3}$|
| micro    | μ      | 0.000001           | 10$^{-6}$|
| nano     | n      | 0.000000001        | 10$^{-9}$|
| pico     | p      | 0.000000000001     | 10$^{-12}$   |
| femto    | f      | 0.000000000000001  | 10$^{-15}$   |



## Cross-sections and their measurement


### What is a cross-section?

In the Geiger-Marsden experiment, whilst some $\alpha$ particles are scattered by large angle, others are not deflected at all. As we have seen, from the general considerations, we can determine an upper limit on the [size of the gold atoms](sizeofAU).

For the $\alpha$ particles, that are passing a gold foil, one can define the inclusive (or integral) cross-section as the area $\sigma = \pi r^2$ of the nuclei through which the $\alpha$ particles need to pass to be scattered by an detectable angle $\theta$. This is a generalisable definition: The cross section is used to quantify the effective size or the strength of an interaction with a particle. It does depend on the particle type as the size of the $\alpha$ particle and the gold nuclei play a role.

As we have calculated above, the radius and thus the area of a nuclei are very small ($\sim$ femto metres). Physicists during the second world war decided to invent a new unit for the cross sectional area of nuclei and nuclear reactions, one that would also be a bit more natural in size, and tried to come up with a name. They settled on "barns" (due to the rural background of one of the physicists involved and because some of the cross-sections were as large as a barn). Today barn is used all fields of high-energy physics a unit of area which is used in cross-sections and integrated luminosity.

One barn (abbr. b) is equal to 10$^{-28}$ m$^2$ or 10$^{-24}$ cm$^2$. This is a larger area, common are cross-section smaller than mb or nb (millibarns and nanobarns). Easiest to remember is probably 1 pb = 10$^{-12}$ b = 10$^{-36}$ cm$^2$

### Measurement of cross-sections

How can we determine a cross-section? The easiest way to conceptualize how cross-sections and their measurements work, is to look at inclusive (or integral) cross-section. Figure a) demonstrates the principle of the measurement of an inclusive cross-section. Consider a flux of particles $J = \Delta N / \Delta t$ passes though the a target (in Rutherford: the foil). The particle flux decreases as:

$\Delta J = -J \sigma_{inc} n_b \Delta x = -J \sigma_{inc} N_b$

with J being the flux, $\sigma_{inc}$ the inclusive cross-section, $n_b$ the particle density in the target and $\Delta x$ being the thickness of the target. $n_b \Delta x$ is therefore effectively the number of target particles in the path of the flux (the number of particles passing in a unit of time). Basically you determine the inclusive cross-section by measuring how many particle where scattered out of the beam. This is corresponding to the rate of particles being scattered depending on initial flux, target particles and cross-section.

<img src="inclcrosssection.png" alt="Cross-section measurements" width="500"/>

a) Measurement of the integral cross section $\sigma$. (b) Measurement of the differential cross section d$\sigma$/d$\Omega$ (taken from {cite}`Demtroder:AtomsMoleculesPhotons`)

The differential cross-section is determined as the particles flux scattered into the solid angle $\Delta \Omega$ accepted by the detector. It is demonstrate in Fig b) where a detector detects the flux of particles being scattered into its acceptance and can be expressed as:

$$\frac{\Delta J}{J A} = n_b \Delta x \frac{ d \sigma}{d \Omega} \Delta \Omega$$

with $J$ as the flux, A the area of the detector, $n_b \Delta x$ the number of target particles, $\frac{ d \sigma}{d \Omega}$ the differential cross-section which depends on the interaction potential between the scattering particles A and B. $\frac{\Delta J}{J A}$ is the fraction of incident particles that is scattered into the solid angle $\Delta \Omega$ accepted by the detector.


## The interpretation of the Geiger-Marsden experiment by Rutherford

As seen above, the mass of the nucleus is much larger than the mass of the $\alpha$ particles. So when Rutherford looked into deriving a formula to describe the scattering occuring the Geiger-Marsden experiment, he assumed, there is no energy loss in the collision, that is he ignores the recoil of the target atom. It also seems, that the electrons have no impact on the scattering as the size of the nucleus, the scattering centre is so much smaller than that of the atoms. Under these conditions, the $\alpha$ particle and nucleus interact through a central force, a physical problem studied already by Isaac Newton and that you have covered in {cite}`Y1Mech`. This problem considers a central force that only acts along a line between the particles and where the force varies with the inverse square, like Coulomb force in this case.

As shown in {cite}`Y1Mech`, a potential of the form $V = k/r$ will lead to the following relationship between the scattering angle and the impact parameter $b$:

$$cos \frac{\theta}{2} = \frac{m^2 b}{k}$$

with $\theta$ being the scattering angle (note: {cite}`Y1Mech` this is called $\phi$, but in particle physics this angle is always called $\theta$), $m$ the mass of the $\alpha$ particles, $k$ the parameters of the potential and $b$ the impact parameter or the point of closest approach, which is the vertical distance between the alpha particle's initial trajectory and the nucleus.

While $b$ might be a reasonable quantity to use in astronomical problems (Kepler used the same approach to calculate the movement of celestial bodies), it is not possible to measure $b$ in the Geiger-Marsden experiment. Therefore, the challenge is to find a way to relate the scattering angle to a quantity that can actually be measured in these sorts of scattering experiments and this is what Rutherford did to explain the experiment.

The procedure is the following:

- express the fraction of the flux passing through the band/annular $b$ and deflected by an angle $\theta$

- compare this to the general expression for the differential cross section

- connect it to the expression of the impact parameter derived using angular momentum and the potential ({cite}`Y1Mech`)

<img src="rutherfordscattering2.png" alt="Rutherford setup" width="500"/>

Geometrical layout of the Geiger-Marsden experiment as used by Rutherford (taken from {cite}`Demtroder:AtomsMoleculesPhotons`)


```{admonition} Calculation

<b> Rutherford scattering angle</b>

From geometrical considerations (i.e. just defining the rate of particles scattered into a solid angle without assuming anything more on the geometry) we can see that that:

```{math}
:label: my_label
\begin{align*}
\frac{\Delta J}{J A} = n_G \Delta x \frac{\mathrm{d}\sigma}{\mathrm{d}\Omega} \Delta \Omega \label{diffxsec_general}
\end{align*}
```

```{admonition}
This is the general form of the differental cross-section.

Let us now assume a parallel beam of incident particles $\alpha$ with particle flux density J (with J = dN/dt) that passes through a layer of particles B in rest with density $n_\textrm{G}$. All particles $\alpha$ that pass through an annular with radius $b$ and width d$b$ around an atom G are deflected by the angle $\theta \pm \textrm{d}\theta/2$. This assumes a sperically symmetric interaction potential: There is no prefered direction (along the ring with radius $b$). Per second, $ dJ = J dA = dN/dt dA = dN/dt 2\pi b db$ particles $\alpha$ pass through the annular ring (with A being the area). The fraction of all particles $\alpha$ (incident per unit area and per second onto the target) scattered through an interaction with **one single** particle G into the range of deflection angles $\theta \pm \textrm{d}\theta/2$ is therefore:

\begin{align*}
\frac{\mathrm{d} J (\theta \pm 1/2 \; \mathrm{d}\theta)}{J} = 2 \pi b \textrm{d}b = 2 \pi b \frac{\textrm{d}b}{\textrm{d} \theta} \textrm{d} \theta
\end{align*}

If we place a detector with an area $A_D = R^2 \mathrm{d}\Omega = R^2 \sin\theta \mathrm{d}\theta\mathrm{d}\phi$ in a distance $R$ from the scattering centre G, then this detector receives a fraction of the particles scattered by this one particle G:

\begin{align*}
\frac{\mathrm{d} J (\theta, \phi)}{J} \frac{\textrm{d}\phi}{2\pi} = b \frac{\textrm{d}b}{\textrm{d} \theta} \textrm{d} \theta \textrm{d} \phi
\end{align*}

The fraction of *all* incident particles $\alpha$, scattered by *all* atoms G with density $n_G$ in the volume $V$ = $A \Delta x$ is then:

\begin{align*}
\frac{\mathrm{d} J (\theta, \textrm{d}\Omega)}{J} &= n_G A \Delta x b \frac{\textrm{d}b}{\textrm{d} \theta} \textrm{d} \theta \textrm{d} \phi 
\end{align*}

This is a specific cross-section (in terms of geometry) that takes into account the impact paramter $b$ and the scattering angle $\theta$. We can compared it to  {eq}`my_label` and find:

\begin{align*}
\frac{\mathrm{d} J}{J} &= n_G A \Delta x b \frac{\textrm{d}b}{\textrm{d} \theta} \textrm{d} \theta \textrm{d} \phi \\
&= n_G A \Delta x \frac{\mathrm{d}\sigma}{\mathrm{d}\Omega} \Delta \Omega
\end{align*}

Setting these two equal yields:
\begin{align*}
\cancel{n_G A \Delta x} b \frac{\textrm{d}b}{\textrm{d} \theta} \textrm{d} \theta \textrm{d} \phi & = \cancel{n_G A \Delta x} \frac{\mathrm{d}\sigma}{\mathrm{d}\Omega} \Delta \Omega  &\biggr\rvert \; \textrm{using} \Delta \Omega = \sin \theta \mathrm{d}\theta \mathrm{d}\phi \\
\frac{\textrm{d}b}{\textrm{d} \theta} \textrm{d} \theta \textrm{d} \phi & =  \frac{\mathrm{d}\sigma}{\mathrm{d}\Omega} \sin \theta \mathrm{d}\theta \mathrm{d}\phi 
\end{align*}

This gives a relationship between the differential cross-section and the impact parameter and scattering angle: 

```{math}
:label: my_label2
\begin{align*}
\boxed{\frac{\mathrm{d} \sigma}{\mathrm{d}\Omega} = b \frac{ \mathrm{d} b}{\mathrm{d} \theta} \frac{1}{\sin \theta}}
\end{align*}
```

```{admonition}

Measuring the relative fraction $\frac{\Delta J}{J}$ yields the differential cross section (see {eq}`my_label`) and with it the interaction potential as we have seen that the angle $\theta$ is defined as (see eq. (72) of the mechanics lecture notes):

\begin{align*}
\cot\frac{\theta}{2} = \frac{m v_0^2 b}{k} = \frac{m v_0^2 b}{1} \frac{4 \pi \epsilon_0}{qQ} 
\end{align*}

Note, that the mechanics lecture notes eq. (72) use $\phi$ - this is the same angle, just a different name. For scattering angles, especially in particle physics, the angle is $\theta$, so this is what we use here. We can re-arrage the equation to get the relationship for $b$:

\begin{align*}
\cot\frac{\theta}{2} &= \frac{m v_0^2 b}{1} \frac{4 \pi \epsilon_0}{qQ} \\
b &= cot\frac{\theta}{2} \frac{qQ}{m v_0^2 4 \pi \epsilon_0}
\end{align*}

We from this last equation we can also get $\frac{\mathrm{d}b}{\mathrm{d}\theta}$ by taking the derivative:

\begin{align*}
\frac{\mathrm{d}b}{\mathrm{d}\theta} &= -\frac{1}{\sin^2(\theta/2)} \frac{qQ}{m v_0^2 4 \pi \epsilon_0}
\end{align*}

As $b$ cannot be measured, we eliminated it from from {eq}`my_label2` by inserting the above expression for $b$ and use $\sin(2\theta) = 2 \sin(\theta) \cos(\theta)$:
\begin{align*}
\frac{\mathrm{d} \sigma}{\mathrm{d}\Omega} &= b \frac{ \mathrm{d} b}{\mathrm{d} \theta} \frac{1}{\sin \theta} \\
&= \frac{\cancel{\cos(\theta/2)}}{\sin(\theta/2)}  \frac{qQ}{m v_0^2 4 \pi \epsilon_0} \frac{1}{\sin^2(\theta/2)} \frac{qQ}{m v_0^2 4 \pi \epsilon_0} \frac{1}{2 \sin(\theta/2) \cancel{\cos(\theta/2)}} \\ 
\end{align*}

This finally yields:

\begin{align*}
\boxed{\frac{\mathrm{d} \sigma}{\mathrm{d}\Omega} = \frac{1}{4} \left( \frac{qQ}{m v_0^2 4 \pi \epsilon_0} \right)^2 \frac{1}{\sin^4(\theta/2)} } 
\end{align*}

**This is the formula for Rutherford scattering!!** 

```

This formula analytically describes Rutherford scattering which is the elastic scattering of charged particles by the Coulomb interaction, sometimes also called Coulomb scattering.

## Elastic and inelastic collisions

Rutherford scattering is elastic scattering, but in this module we will also be looking at inelastic scattering so it's important to understand, what the difference is. In a scattering process momentum is conserved but this is not always the case for the kinetic energy and this is where the difference lies.

In elastic collisions, the kinetic energy is conserved in addition to the momentum (e.g. snooker balls, Rutherford scattering). In these cases, you write down an equation for the energies of the particles before and after the collision and a second equation with the momenta of the particles before and after the collision {--} this later calculation can be done vectorially (i.e. under consideration of the angles of the particles). The final momenta depend on the angle of scattering and given $\theta$ we can calculate the velocities of the outgoing particles. If you look at the outcome of scattering experiments such that the Rutherford experiment, and you fix the scattering angle that you are looking at as well as the incident particle energy, you will find peaks in the spectrum of the scattered particle energies.

In inelastic collisions however, the kinetic energy is not conserved (though total energy is conserved!) and is transformed into heat or other mechanical energy (e.g. car crash) or in particle collisions into mass. Effectively, the equation for energy conservation then reads:

$E^\textrm{initial}_\textrm{kin} = E^\textrm{final}_\textrm{kin} + E_\textrm{internal}$

where $E_\textrm{internal}$ describes the energy transformed into heat or the production of another particle. If looking at scattering of particles, you will then see a number of peaks that correspond to different values of $E^\textrm{initial}_\textrm{kin} - E_\textrm{internal}$. The internal energy is expanded for exciting the nuclei or to produce new particles.

## Scattering on nucleons

The scattering experiments did not stop with Rutherford scattering: For very large angles (corresponding to small impact parameters where the electrons are very close to the centre of the atom and thus the nucleus) again deviations from the Rutherford formula were observed.

In these follow up experiments from the original Geiger-Marsden experiment, $\alpha$ particles were scattered of various light nuclei and the experimenters used new materials as sources of $\alpha$ particle which higher energies.

<img src="falloffRutherfordFormula.png" alt="Rutherford scattering: Comparison of data with prediction" width="500"/>

Comparison of Rutherford (or Coulomb) scattering of particles to the measured data (taken from {cite}`Demtroder:AtomsMoleculesPhotons`)

When comparing the number of counts as function of energy of the incoming particle or as function of the angle to the predicted count from the Rutherford Scattering formula, a deviation at high energies and large angles became apparent. Finally, the analysis of these results led to the conclusion that the alpha particle was penetrating the nucleus in these cases. Once probe come closer than radius of nulei, a new short range force, called the nuclear force, becomes important. Scattering calculated based on Coulomb potential is no longer valid. The attractive nuclear force is much stronger.

In the following decades, with the Advent of [particle accelerators](sec_accelerators).

as shown in the following figure. Here, since the incoming energy and the scattering angle are fixed, the energy of the outgoing electrons is fixed as well. In this measurement, there are two peaks visible: The scattering of electrons on electrons (in the atomic shell) and of electrons with a proton or neutron from the nucleus.

<img src="ealastc.png" alt="Elastic Scattering" width="500"/>

Energy spectrum of 15.7 Mev electrons scattered at 30$\degree$ by polystyrene (carbon). The ordinate (y-axis) represents the observed count as a function of an arbitrary energy unit on the x-axis (i.e. in this case the setting on the magnetic analyzer that selects out the energy of the scattered electrons). The
counters have a 3 percent resolution in energy (taken from {cite}`PhysRev.84.626`)


, e.g. as in the following plot, where apart from the elastic scattering peak, there are various other peaks visible that correspond to different excited states of Carbon.

<img src="inelastic.png" alt="Inelastic scattering" width="300"/>

The elastic and inelastic peaks at 187 Mev in carbon at a scattering angle of 80$\degree$. (taken from {cite}`PhysRev.99.1503`)


Analogue to discovering the atomic substructure, scattering experiments were used to discover the proton substructure
1990 Nobel Prize. Friedman, Kendall, Taylor

Further info: https://www.nobelprize.org/prizes/physics/1990/summary/




