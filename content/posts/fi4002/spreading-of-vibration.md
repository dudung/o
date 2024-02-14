+++
title = 'spreading of vibration'
date = 2024-02-14T18:06:00+07:00
draft = false
tags = ['fi4002']
math = true
+++
Collection of information about noise and vibration
<!--more-->

+ slide N/A (on 14-feb)
+ story https://medium.com/p/617655776d61 (on 14-feb)


## source
At position $\vec{r}_s$ there is source of vibration

$$\tag{1}
\psi_s(t) = \sum_{i=1}^N A_i \sin(\omega_i t + \varphi_i)
$$

which is simplified as superposition of $N$ simple harmonic motion of physical quantity $A_i$ with angular frequency $\omega_i$ and initial phase $\varphi_i$, where $A_i$ migth represent difference between variation of air pressure and normal atmospheric pressure

$$\tag{2}
\Delta p = p(t) - p_0
$$

or difference between variation of position of parts of solid body, e.g. the ground, to their equilibrium position

$$\tag{3}
\Delta \vec{r} = \vec{r}(t) - \vec{r}_0.
$$  

Sound waves are accomodated by Eqn (2), while waves on solid are by Eqn (3). The first are longitudinal waves, while the later could be longitudinal and transversal waves.


## wave
Function represents wave from previous source of vibration

$$\tag{4}
\psi({\vec{r}, t}) = \sum_{i=1}^N A_i \sin(\omega_i t + \varphi_i - k_i |\vec{r} - \vec{r}_s|),
$$

where wavenumber is

$$\tag{5}
k = \frac{2\pi}{\lambda}
$$

with wavelength $\lambda$. If $v$ is wave velocity then it is obtained from

$$\tag{6}
v = \frac{\omega}{k}
$$

or

$$\tag{7}
v = \frac{\lambda}{T} = \lambda f.
$$


## intensity
Intensity at vibration source is proportional to square of amplitude

$$\tag{8}
I_s \propto  | A |^2
$$

and at distance $r$ from the source

$$\tag{9}
I(r) = \frac{r_o^2}{r^2} I_s
$$

for sound assuming it is spreading as spherical wave, where $r_o$ is size of the source.


## resonance
When wave arrives at some position $\vec{r}_j$ it will induce vibration on that position which can be considered as sinusoidal driving force with amplitude $F_0$ and frequency $\omega$. Equation of motion at that placew would be

$$\tag{10}
m \frac{d^2 \psi}{dt^2} + b \frac{d\psi}{dt} + k \psi = F_0 \cos (\omega t + \varphi_d)
$$

with damping coefficient $b$, spring constant $k$, and mass $m$. Then it can be obtained that

$$\tag{11}
A_j = \frac{F_0/m}{\sqrt{(\omega_0^2 - \omega^2)^2 + 4\gamma^2
\omega^2}}
$$

is the amplitude at that position, where

$$\tag{12}
\omega_0 = \sqrt\frac{k}{m}
$$

and

$$\tag{13}
\gamma = \frac{b}{2m}.
$$

Then it should be assumed

$$\tag{14}
F_0 \propto \sqrt{I(r)},
$$

to relate this part with previous one.