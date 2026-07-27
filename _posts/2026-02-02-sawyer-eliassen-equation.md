---
title: "Sawyer-Eliassen Equation"
date: 2026-02-02
permalink: /posts/2026/02/sawyer-eliassen-equation/
tags:
  - tropical cyclones
  - atmospheric dynamics
  - dynamic meteorology
---

## 1. SE Equation in Quasi-Geostrophic Frontal Dynamics

### 1.1 Quasi-Geostrophic System for Frontal Dynamics

Within a frontal zone, the classical quasi-geostrophic dynamics applicable to the large-scale midlatitude atmosphere is no longer adequate because the kinematic characteristics of along-front and cross-front motions differ substantially. Scale analysis provides a systematic framework for deriving a dynamical system appropriate for frontal regions.

![Schematic of a frontal zone](/images/see-frontal-zone.jpg)

*Figure 1. Schematic of a frontal zone. Red curves denote potential-temperature contours, the region between the blue dashed lines denotes the frontal zone, the blue arrow indicates the cross-front direction, and the purple arrow indicates the along-front direction.*

Let the cross-front length scale be \\(x\sim l\\) and the along-front length scale be \\(y\sim L\\). A typical frontal system satisfies \\(l\ll L\\). Let the corresponding velocity scales be \\(u\sim U\\) and \\(v\sim V\\). To establish the relationship between \\(U\\) and \\(V\\), consider the continuity equation on constant-height surfaces:

$$
\begin{aligned} \frac{\partial u}{\partial x}+\frac{\partial v}{\partial y}+\frac{\partial w}{\partial z}=0, (1.1) \end{aligned}
$$

Substitution of the scale relationships gives

$$
\begin{aligned} \frac{U}{l}\sim\frac{V}{L} \end{aligned}
$$

Because \\(l\ll L\\), it follows that \\(U\ll V\\); the horizontal motion is therefore strongly anisotropic. The relative importance of geostrophic effects in the two directions may be assessed using Rossby numbers. In a classical quasi-geostrophic system, the Rossby number is defined as

$$
\begin{aligned} Ro=\frac{o(\frac{d_hu}{dt})}{o(fv)} \end{aligned}
$$

For frontal dynamics, separate Rossby numbers must be defined for the cross-front and along-front directions:

$$
\begin{aligned} Ro_x=\frac{o(\frac{d_hu}{dt})}{o(fv)} \end{aligned}
$$

$$
\begin{aligned} Ro_y=\frac{o(\frac{d_hv}{dt})}{o(fu)} \end{aligned}
$$

To determine the scaling relationship between the horizontal accelerations, consider the horizontal momentum equations:

$$
\begin{aligned} \frac{du}{dt}=fv-\frac{\partial \Phi}{\partial x}, (1.2a)\\ \frac{dv}{dt}=-fu-\frac{\partial \Phi}{\partial y}, (1.2b)\\ \end{aligned}
$$

$$
\begin{aligned} \frac{d}{dt}=\frac{\partial}{\partial t}+\vec{v}_h\cdot\nabla+w\frac{\partial}{\partial z}=\frac{d_h}{d t}+w\frac{\partial}{\partial z} \end{aligned}
$$

Using the scale relationship between \\(U/l\\) and \\(V/L\\),

$$
\begin{aligned} \frac{d_h u}{dt}=\frac{\partial u}{\partial t}+\vec{v}_h\cdot\nabla u \sim\frac{U^2}{l}+U\frac{U}{l}+V\frac{U}{L}\sim\frac{UV}{L} \end{aligned}
$$

$$
\begin{aligned} \frac{d_h v}{dt}=\frac{\partial v}{\partial t}+\vec{v}_h\cdot\nabla v \sim\frac{V^2}{L}+U\frac{V}{l}+V\frac{V}{L}\sim\frac{UV}{l} \end{aligned}
$$

The directional Rossby numbers are therefore

$$
\begin{aligned} Ro_x=\frac{U}{fL} \end{aligned}, (1.3)
$$

$$
\begin{aligned} Ro_y=\frac{V}{fl} \end{aligned}, (1.4)
$$

Since \\(U\ll V\\) and \\(l\ll L\\), \\(Ro_x\ll Ro_y\\). For characteristic frontal scales, \\(Ro_x\ll 1\\) whereas \\(Ro_y\sim 1\\). The cross-front momentum balance is therefore quasi-geostrophic (cross-front geostrophy), so the along-front wind is nearly geostrophic, \\(v\sim v_g\\). The same result follows directly from scale analysis of Eq. (1.2). By contrast, the along-front momentum balance is not quasi-geostrophic. Consequently, the geostrophic and ageostrophic components of the cross-front wind have comparable magnitudes (cross-front ageostrophic wind), such that \\(u\sim u_g\sim u_a\\).

This analysis demonstrates that the conventional large-scale midlatitude quasi-geostrophic theory is inappropriate for frontal dynamics. A new reduced system must instead be developed from the scaling relationships characteristic of frontal zones.

Because the cross-front momentum balance is quasi-geostrophic, Eq. (1.2a) reduces to

$$
\begin{aligned} fv_g=\frac{\partial \Phi}{\partial x} \end{aligned}, (1.5a)
$$

The along-front momentum balance is not quasi-geostrophic. Nevertheless, using \\(u\sim u_g\sim u_a\\) and \\(v\sim v_g\\), Eq. (1.2b) may be written as

$$
\begin{aligned} \frac{D_gv_g}{Dt}=-fu-\frac{\partial \Phi}{\partial y}, (1.5b)\\ \end{aligned}
$$

$$
\begin{aligned} \frac{D_g}{Dt}=\frac{\partial}{\partial t}+\vec{v}_g\cdot\nabla_h, \\ \end{aligned}
$$

Equation (1.5b) can be simplified further because \\(u_g\\) satisfies geostrophic balance (although \\(u\\) does not), and \\(u_a=u-u_g\\). The geostrophic relation is

$$
\begin{aligned} fu_g=-\frac{\partial \Phi}{\partial y}\\ \end{aligned}
$$

Equation (1.5b) then becomes

$$
\begin{aligned} \frac{D_gv_g}{Dt}=-fu_a, (1.5c)\\ \end{aligned}
$$

On constant-height surfaces, the hydrostatic equation is expressed as

$$
\begin{aligned} \frac{\partial \Phi}{\partial z}=b, (1.6)\\ \end{aligned}
$$

where \\(b\\) denotes buoyancy, defined by

$$
\begin{aligned} b=g\frac{\rho'}{\rho_0}&=g\frac{\theta'}{\theta}=g\frac{\theta_0-\theta}{\theta_0} \end{aligned}
$$

\\(\rho\\) and \\(\theta\\) denote density and potential temperature, respectively, while primed quantities and the subscript \\(0\\) denote perturbation and reference states. In some formulations, buoyancy is written as

$$
\begin{aligned} b=g \big[ \frac{\theta'}{\theta_0}+(\kappa-1)\frac{p'}{p_0}-q' \big] \end{aligned}
$$

where \\(\kappa=0.286\\) and \\(q\\) is the specific humidity.

The buoyancy form of the thermodynamic equation follows from the potential-temperature equation:

$$
\begin{aligned} \frac{D_g \theta}{Dt}=0 \Rightarrow  \frac{D_g b}{Dt}=-N^2w, (1.7) \end{aligned}
$$

Here \\(N^2\\) is the static-stability parameter, defined as

$$
\begin{aligned} N^2=\frac{g}{\theta_0}\frac{d\theta_0}{dz} \end{aligned}
$$

Equation (1.1) may be reduced further to

$$
\begin{aligned} \frac{\partial u_a}{\partial x}+\frac{\partial w}{\partial z}=0,(1.8) \end{aligned}
$$

Equations (1.5a), (1.5c), (1.6), (1.7), and (1.8) constitute the frontal-dynamics system:

$$
\begin{aligned} fv_g=\frac{\partial \Phi}{\partial x}, (1.5a)\\ \frac{D_gv_g}{Dt}=-fu_a, (1.5c) \\ \frac{\partial \Phi}{\partial z}=b, (1.6)\\ \frac{D_g b}{Dt}=-N^2w, (1.7) \\ \frac{\partial u_a}{\partial x}+\frac{\partial w}{\partial z}=0,(1.8) \end{aligned}
$$

### 1.2 Sawyer-Eliassen Equation

Combining the cross-front momentum equation (1.5a) with the hydrostatic equation (1.6) yields the thermal-wind relation for this system:

$$
\begin{aligned} f\frac{\partial v_g}{\partial z}=\frac{\partial }{\partial z}\frac{\partial \Phi}{\partial x}=\frac{\partial }{\partial x}\frac{\partial \Phi}{\partial z}=\frac{\partial b}{\partial x}, (1.9) \end{aligned}
$$

Equation (1.9) is diagnostic. Taking its geostrophic material derivative gives the thermal-wind relation for the evolving system:

$$
\begin{aligned} \frac{D_g}{Dt}\big( f\frac{\partial v_g}{\partial z} \big)=\frac{D_g}{Dt}\big(\frac{\partial b}{\partial x}\big), (1.10) \end{aligned}
$$

The left-hand side represents the dynamical evolution of the system, whereas the right-hand side represents its thermodynamic evolution. Expanding the two sides separately and then equating them gives the following results.

$$
\begin{aligned} \frac{D_g}{Dt}\big( f\frac{\partial v_g}{\partial z} \big)&=\frac{\partial}{\partial t}\big( f\frac{\partial v_g}{\partial z} \big)+u_g\frac{\partial}{\partial x}\big( f\frac{\partial v_g}{\partial z} \big)+v_g\frac{\partial }{\partial y}\big( f\frac{\partial v_g}{\partial z} \big)\\  &=\frac{\partial }{\partial z}\big( f\frac{\partial v_g}{\partial t} \big)+f\frac{\partial}{\partial z} \big( u_g\frac{\partial v_g}{\partial x} \big)-f\frac{\partial u_g}{\partial z}\frac{\partial v_g}{\partial x}+f\frac{\partial}{\partial z} \big( v_g\frac{\partial v_g}{\partial y} \big)-f\frac{\partial v_g}{\partial z}\frac{\partial v_g}{\partial y}\\  &=f\frac{\partial }{\partial z}\big( \frac{\partial v_g}{\partial t} +  u_g\frac{\partial v_g}{\partial x} +  v_g\frac{\partial v_g}{\partial y} \big)-f\frac{\partial u_g}{\partial z}\frac{\partial v_g}{\partial x}-f\frac{\partial v_g}{\partial z}\frac{\partial v_g}{\partial y}\\  &=f\frac{\partial}{\partial z}\big(\frac{D_gv_g}{Dt}\big)-f\frac{\partial u_g}{\partial z}\frac{\partial v_g}{\partial x}-f\frac{\partial v_g}{\partial z}\frac{\partial v_g}{\partial y} \end{aligned}
$$

From Eq. (1.5c),

$$
\begin{aligned}  f\frac{\partial}{\partial z}\big(\frac{D_gv_g}{Dt}\big)=-f^2\frac{\partial u_a}{\partial z}, (1.11)  \end{aligned}
$$

Therefore,

$$
\begin{aligned} \frac{D_g}{Dt}\big( f\frac{\partial v_g}{\partial z} \big)&=-f^2\frac{\partial u_a}{\partial z}-f\frac{\partial u_g}{\partial z}\frac{\partial v_g}{\partial x}-f\frac{\partial v_g}{\partial z}\frac{\partial v_g}{\partial y}, (1.12) \end{aligned}
$$

The right-hand side of Eq. (1.10) can similarly be expanded as

$$
\begin{aligned} \frac{D_g}{Dt}\big( \frac{\partial b}{\partial x} \big)&=-N^2\frac{\partial w}{\partial x}-\frac{\partial u_g}{\partial x}\frac{\partial b}{\partial x}-\frac{\partial v_g}{\partial x}\frac{\partial b}{\partial y}, (1.13) \end{aligned}
$$

The mixed-derivative terms on the right-hand sides of Eqs. (1.12) and (1.13) can be placed in a common form. Using the hydrostatic relation (1.6),

$$
\begin{aligned} \frac{\partial b}{\partial y}=\frac{\partial }{\partial y}\frac{\partial \Phi}{\partial z}=\frac{\partial }{\partial z}\frac{\partial \Phi}{\partial y}=-f\frac{\partial u_g}{\partial z}, (1.14a)\\ \\   \frac{\partial b}{\partial x}=\frac{\partial }{\partial x}\frac{\partial \Phi}{\partial z}=\frac{\partial }{\partial z}\frac{\partial \Phi}{\partial x}=f\frac{\partial v_g}{\partial z},(1.14b) \end{aligned}
$$

For a geostrophic wind, \\(\partial u_g/\partial x+\partial v_g/\partial y=0\\). Substituting Eq. (1.14) into Eq. (1.12) and invoking the nondivergence of the geostrophic wind yields

$$
\begin{aligned} \frac{D_g}{Dt}\big( f\frac{\partial v_g}{\partial z} \big)&=-f^2\frac{\partial u_a}{\partial z}  +\frac{\partial b}{\partial y}\frac{\partial v_g}{\partial x}  +\frac{\partial b}{\partial x}\frac{\partial u_g}{\partial x}, (1.15) \end{aligned}
$$

The cross-derivative terms on the right-hand side of Eq. (1.15) now have the same form as those in Eq. (1.13). Define

$$
\begin{aligned} Q=  -\big(\frac{\partial b}{\partial y}\frac{\partial v_g}{\partial x}  +\frac{\partial b}{\partial x}\frac{\partial u_g}{\partial x}\big), (1.16) \end{aligned}
$$

\\(Q\\) is a purely geostrophic quantity. Equations (1.12) and (1.13) may consequently be written as

$$
\begin{aligned} \frac{D_g}{Dt}\big( f\frac{\partial v_g}{\partial z} \big)&=-f^2\frac{\partial u_a}{\partial z}-Q, (1.17)\\ \\ \frac{D_g}{Dt}\big( \frac{\partial b}{\partial x} \big)&=-N^2\frac{\partial w}{\partial x}+Q, (1.18) \end{aligned}
$$

Because Eq. (1.10) requires the right-hand sides of Eqs. (1.17) and (1.18) to be equal,

$$
\begin{aligned} N^2\frac{\partial w}{\partial x}-f^2\frac{\partial u_a}{\partial z} =2Q, (1.19) \end{aligned}
$$

Equation (1.19) is the omega equation for the frontal-dynamics system. The geostrophic forcing \\(Q\\) induces the ageostrophic response represented by \\(w\\) and \\(u_a\\); that is, geostrophic forcing displaces the system from quasi-geostrophic thermal-wind balance. Equivalently, forcing associated with the primary horizontal circulation induces a cross-front secondary circulation in the vertical plane. This ageostrophic secondary circulation subsequently acts to restore a balanced state.

The continuity equation (1.8) may be written as

$$
\begin{aligned} \frac{\partial u_a}{\partial x}=-\frac{\partial w}{\partial z} \end{aligned}
$$

A streamfunction may therefore be defined by

$$
\begin{aligned} u_a=\frac{\partial \Psi}{\partial z}\\ \\ w=-\frac{\partial \Psi}{\partial x}\\ \end{aligned} 
$$

In the Northern Hemisphere, a positive streamfunction \\(\Psi>0\\) in the \\(x-z\\) plane corresponds to counterclockwise rotation, whereas a negative streamfunction \\(\Psi<0\\) corresponds to clockwise rotation. A positive streamfunction produces ascent on the warm side and descent on the cold side, describing a thermally direct circulation that converts potential energy into kinetic energy. A negative streamfunction produces ascent on the cold side and descent on the warm side, describing a thermally indirect circulation.

![Positive streamfunction in the x-z plane](/images/see-positive-streamfunction.jpg)

*Figure 2. A positive streamfunction in the x-z plane.*

Substitution of the streamfunction into Eq. (1.19) gives

$$
\begin{aligned} N^2\frac{\partial^2 \Psi}{\partial x^2}+f^2\frac{\partial^2 \Psi}{\partial z^2} =-2Q, (1.20) \end{aligned}
$$

Equation (1.20) is the quasi-geostrophic form of the Sawyer-Eliassen equation (SEE).

## 2. SE Equation in Axisymmetric Balanced Hurricane Models

In a tropical cyclone (TC), the strongest motion is the horizontal tangential wind, but the secondary circulation is essential to TC intensification and maintenance. The SEE has therefore been applied to studies of tropical cyclones, particularly intensification and eyewall replacement cycles. For a TC, the governing equations must be expressed in cylindrical coordinates, producing a dynamical system distinct from that used for frontal dynamics.

### 2.1 Incompressible Boussinesq Approximation Theory

Assume an axisymmetric TC flow that satisfies the incompressible Boussinesq approximation, with \\(\partial\bar{\rho}/\partial z=0\\) and \\(N=\mathrm{const}\\). The hydrostatic primitive equations are then

$$
\begin{aligned}  \frac{\partial u}{\partial t}+u\frac{\partial u}{\partial r}+w\frac{\partial u}{\partial z}-C=-\frac{\partial P}{\partial r}+F_r, (2.1)\\  \frac{\partial v}{\partial t}+u\frac{\partial v}{\partial r}+w\frac{\partial v}{\partial z}+\frac{uv}{r}+fu=F_{\lambda}, (2.2)\\  \frac{\partial P}{\partial z}=b , (2.3)\\  \frac{\partial b}{\partial t}+u\frac{\partial b}{\partial r}+w\frac{\partial b}{\partial z}+N^2w=\dot B, (2.4)\\  \frac{\partial ru}{\partial r}+\frac{\partial rw}{\partial z}=0,(2.5)   \end{aligned}
$$

\\(r,\lambda,z\\) are the radial, azimuthal, and vertical coordinates, respectively. The quantity \\(C=v^2/r+fv\\) is the sum of the centrifugal and Coriolis accelerations and is sometimes termed the generalized Coriolis force; \\(P=p/\bar{\rho}\\); and \\(\dot{B},F_r,F_{\lambda}\\) denote diabatic forcing, radial momentum forcing, and tangential momentum forcing, respectively. In cylindrical coordinates, the absolute vertical vorticity is \\(\xi_a=v/r+\partial v/\partial r+f=\eta+f\\), so Eq. (2.2) is commonly written as

$$
\begin{aligned}   \frac{\partial v}{\partial t}+w\frac{\partial v}{\partial z}+u\xi_a=F_{\lambda}, (2.2*)\\  \end{aligned}
$$

To derive Eq. (2.4), begin with the potential-temperature form of the thermodynamic equation:

$$
\begin{aligned}  \frac{d\theta}{dt}=\frac{\theta Q}{c_p T}  \end{aligned}
$$

Here \\(Q\\) is the heat source. Under the Boussinesq approximation, potential temperature is decomposed into a perturbation and a height-dependent basic state, \\(\theta=\theta'+\bar{\theta}\\):

$$
\begin{aligned}  \frac{d\theta'}{dt}+\frac{d\bar\theta}{dt}=(\theta'+\bar\theta)\frac{Q}{c_p T}\\ \Rightarrow \frac{\partial \theta'}{\partial t}+u\frac{\partial \theta'}{\partial r}+w\frac{\partial \theta'}{\partial z}+w\frac{\partial \bar \theta}{\partial z}=(\theta'+\bar\theta)\frac{Q}{c_p T}  \end{aligned}
$$

Using the potential-temperature form of buoyancy, \\(b=(\theta'/\theta_0)g\\), and multiplying by \\(g/\theta_0\\) gives

$$
\begin{aligned}  \frac{\partial b}{\partial t}+u\frac{\partial b}{\partial r}+w\frac{\partial b}{\partial z}+N^2w=\frac{\theta'+\bar\theta}{\theta_0}\frac{gQ}{c_p T}  \end{aligned}
$$

Assuming \\((\theta'+\bar{\theta})/\theta_0\sim1\\), this reduces to

$$
\begin{aligned}  \frac{\partial b}{\partial t}+u\frac{\partial b}{\partial r}+w\frac{\partial b}{\partial z}+N^2w=\frac{gQ}{c_p T}=\dot B  \end{aligned}
$$

The environmental buoyancy frequency is defined as

$$
\begin{aligned}  N^2=\frac{g}{\theta_0}\frac{\partial \bar \theta}{\partial z}  \end{aligned}
$$

Equation (2.3) is equivalent to Eq. (1.6), and Eq. (2.4) is the nonconservative form of Eq. (1.7). Equation (2.5) is also commonly written as

$$
\begin{aligned} \frac{1}{r}\frac{\partial ru}{\partial r}+\frac{\partial w}{\partial z}=0,(2.5)   \end{aligned}
$$

Under strict gradient-wind balance, Eq. (2.1) reduces to

$$
\begin{aligned} C=\frac{\partial P}{\partial r}, (2.6) \end{aligned}
$$

Equation (2.6) has the same form as Eq. (1.5a). Combining the radial momentum balance (2.6) with the hydrostatic equation (2.3) gives the thermal-wind relation for this system:

$$
\begin{aligned} \frac{\partial^2 P}{\partial r \partial z}=\frac{\partial b}{\partial r}&=\frac{\partial C}{\partial z}=\frac{\partial }{\partial z}\big( \frac{v^2}{r}+fv \big)=\big( \frac{2v}{r}+f \big)\frac{\partial v}{\partial z}\\ \\ &\Rightarrow  \frac{\partial b}{\partial r}=\xi\frac{\partial v}{\partial z}=\xi S,(2.7)  \end{aligned}
$$

Here \\(\xi=2v/r+f\\) is twice the absolute angular velocity and is also called the local Coriolis parameter. The quantity \\(S=\partial v/\partial z\\) is the vertical shear of the tangential wind. The continuity equation (2.5) permits introduction of a streamfunction in cylindrical coordinates, whose form differs from that in local Cartesian coordinates:

$$
\begin{aligned}  u=-\frac{1}{r}\frac{\partial \psi}{\partial z}\\ \\ w=\frac{1}{r}\frac{\partial \psi}{\partial r}  \end{aligned}
$$

To obtain a diagnostic relation for the evolving system, take the time derivative of the thermal-wind equation, analogous to Eq. (1.10):

$$
\begin{aligned}  \frac{\partial }{\partial t}\frac{\partial b}{\partial r}=\frac{\partial }{\partial t}\big(\xi\frac{\partial v}{\partial z}\big)=\frac{\partial }{\partial z}\big(\xi\frac{\partial v}{\partial t}\big)  \end{aligned}
$$

This step implicitly uses

$$
\begin{aligned}  \frac{\partial v}{\partial z}\frac{\partial \xi}{\partial t}=\frac{\partial \xi}{\partial z}\frac{\partial v}{\partial t}  \end{aligned}
$$

Using Eqs. (2.2*) and (2.4), the two sides of the evolving thermal-wind relation may be expanded as

$$
\begin{aligned}  \frac{\partial }{\partial z}\big(\xi\frac{\partial v}{\partial t}\big)=\frac{\partial }{\partial z}\big[\xi \big( -w\frac{\partial v}{\partial z}-u\xi_a+F_{\lambda} \big) \big]  \end{aligned}
$$

$$
\begin{aligned}  \frac{\partial }{\partial t}\frac{\partial b}{\partial r}  =\frac{\partial }{\partial r}\frac{\partial b}{\partial t}  =\frac{\partial }{\partial r}\big( -u\frac{\partial b}{\partial r}-w\frac{\partial b}{\partial z}-N^2w+\dot B \big)  \end{aligned}
$$

$$
\begin{aligned}  \Rightarrow \frac{\partial }{\partial z}\big[\xi \big( -w\frac{\partial v}{\partial z}-u\xi_a+F_{\lambda} \big) \big]  =\frac{\partial }{\partial r}\big(-u\frac{\partial b}{\partial r}-w\frac{\partial b}{\partial z}-N^2w+\dot B \big)\\ \\ \Rightarrow \frac{\partial }{\partial z}\big[\xi \big( -\frac{1}{r}\frac{\partial \psi}{\partial r}S+\frac{1}{r}\frac{\partial \psi}{\partial z}\xi_a+F_{\lambda} \big) \big]  =\frac{\partial }{\partial r}\big(\frac{1}{r}\frac{\partial \psi}{\partial z}\frac{\partial b}{\partial r}-\frac{1}{r}\frac{\partial \psi}{\partial r}\frac{\partial b}{\partial z}-N^2\frac{1}{r}\frac{\partial \psi}{\partial r}+\dot B \big)\\ \\  \Rightarrow \frac{\partial }{\partial r}\big[\big( \frac{\partial b}{\partial z}+N^2 \big)\frac{1}{r}\frac{\partial \psi}{\partial r} - \frac{1}{r}\frac{\partial \psi}{\partial z}\frac{\partial b}{\partial r} \big]  +  \frac{\partial }{\partial z}\big( \frac{\xi\xi_a}{r}\frac{\partial \psi}{\partial z} - \frac{\xi S}{r}\frac{\partial \psi}{\partial r} \big)  = \frac{\partial \dot B}{\partial r}-\frac{\partial }{\partial z}\big( F_{\lambda} \xi \big)  \end{aligned}
$$

Using Eq. (2.7) to replace \\(\partial b/\partial r=\xi S\\) gives

$$
\begin{aligned}  \frac{\partial }{\partial r}\big[\big( \frac{\partial b}{\partial z}+N^2 \big)\frac{1}{r}\frac{\partial \psi}{\partial r} - \frac{\xi S}{r}\frac{\partial \psi}{\partial z} \big]  +  \frac{\partial }{\partial z}\big( \frac{\xi\xi_a}{r}\frac{\partial \psi}{\partial z} - \frac{\xi S}{r}\frac{\partial \psi}{\partial r} \big)  = \frac{\partial \dot B}{\partial r}-\frac{\partial }{\partial z}\big( F_{\lambda} \xi \big), (2.8)  \end{aligned}
$$

Equation (2.8) is the Sawyer-Eliassen equation in axisymmetric balance theory.

Consider the buoyancy-frequency term \\(\partial b/\partial z\\) in Eq. (2.8). Using the density form of buoyancy, \\(b=-(\rho'/\rho_0)g\\),

$$
\begin{aligned}  \frac{\partial b}{\partial z}=-\frac{g}{\rho_0}\frac{\partial \rho'}{\partial z} =\frac{g}{\theta_0}\frac{\partial \theta'}{\partial z} \end{aligned}
$$

The quantity above may be interpreted as the perturbation buoyancy frequency. Combining the environmental and perturbation contributions defines

$$
\begin{aligned} N_{total}^2=N^2+ \frac{\partial b}{\partial z} =\frac{g}{\theta_0}\big(\frac{\partial \bar \theta}{\partial z}+ \frac{\partial \theta'}{\partial z}\big)=\frac{g}{\theta_0}\frac{\partial  \theta}{\partial z} \end{aligned}
$$

where \\(N_{\mathrm{total}}^2\\) is the total static stability.

Define \\(A=N_{\mathrm{total}}^2\\) as static stability, \\(B=-\xi S\\) as baroclinicity (cf. the thermal-wind relation 2.7), and \\(C=\xi\xi_a=I^2\\) as inertial stability. Equation (2.8) then becomes

$$
\begin{aligned}  \frac{\partial }{\partial r}\big(\frac{A}{r}\frac{\partial \psi}{\partial r} + \frac{B}{r}\frac{\partial \psi}{\partial z} \big)  +  \frac{\partial }{\partial z}\big( \frac{C}{r}\frac{\partial \psi}{\partial z} + \frac{B}{r}\frac{\partial \psi}{\partial r} \big)  = \frac{g}{c_p T}\frac{\partial Q}{\partial r}-\frac{\partial }{\partial z}\big( F_{\lambda} \xi \big), (2.8*)  \end{aligned}
$$

A further expansion gives

$$
\begin{aligned}   A\frac{\partial^2\psi}{\partial r^2}+2B\frac{\partial^2\psi}{\partial r\partial z}+C\frac{\partial^2\psi}{\partial z^2}-\frac{A}{r}\frac{\partial\psi}{\partial r}-\frac{B}{r}\frac{\partial\psi}{\partial z}-\frac{C}{r}\frac{\partial \psi}{\partial z}=Forcing  , (2.8**)  \end{aligned}
$$

### 2.2 General Form of Axisymmetric Balance Theory

For a deep convective atmospheric system, the Boussinesq approximation is overly restrictive and removes important information from the original system. We therefore derive the general form of axisymmetric balance theory and its SEE while assuming only gradient-wind and hydrostatic balance:

$$
\begin{aligned}  C=\frac{1}{\rho}\frac{\partial p}{\partial r}, (2.9)\\    \\ \frac{\partial p}{\partial z}=-\rho g , (2.10)\\ \end{aligned}
$$

Eliminating pressure \\(p\\) while allowing \\(\partial\rho/\partial z\ne0\\) yields the thermal-wind relation

$$
\begin{aligned} g\frac{\partial }{\partial r}ln\rho+C\frac{\partial }{\partial z}ln\rho=-\xi\frac{\partial v}{\partial z} , (2.11)\\   \end{aligned}
$$

Define \\(\chi=1/\theta\\). Noting that \\(\partial\ln\theta=\partial\ln\rho\\) and \\(\partial C/\partial z=\xi(\partial v/\partial z)\\), the preceding equation becomes

$$
\begin{aligned} g\frac{\partial \chi}{\partial r}+\frac{\partial (\chi C)}{\partial z}=0,(2.12)\\   \end{aligned}
$$

The potential-temperature form of the thermodynamic equation is

$$
\begin{aligned} \frac{d\theta}{dt}=Q\\   \end{aligned}
$$

Substituting \\(\chi\\) and expanding gives the thermodynamic equation

$$
\begin{aligned} \frac{\partial\chi}{\partial t}+u\frac{\partial\chi}{\partial r}+w\frac{\partial \chi}{\partial z}=-\chi^2 Q,(2.13)\\   \end{aligned}
$$

Next, derive the continuity equation for a steady density field, \\(\partial\rho/\partial t=0\\). The divergence in cylindrical coordinates is

$$
\begin{aligned}  \nabla\cdot\vec{A}=\frac{1}{r}\frac{\partial }{\partial r}(rA_r)+\frac{1}{r}\frac{\partial A_\theta}{\partial \theta}+\frac{\partial A_z}{\partial z} \\   \end{aligned}
$$

Substitution of \\(\vec{A}=\rho\vec{V}\\) gives

$$
\begin{aligned}  \nabla\cdot\rho\vec{V}=\frac{1}{r}\frac{\partial }{\partial r}(r\rho u)+\frac{1}{r}\frac{\partial(\rho v)}{\partial \theta}+\frac{\partial (\rho w)}{\partial z} \\   \end{aligned}
$$

Since \\(\partial r/\partial z=0\\), the axisymmetric continuity equation becomes

$$
\begin{aligned}  \frac{\partial }{\partial r}(\rho ru)+\frac{\partial }{\partial z}(\rho rw)=0,(2.14) \\   \end{aligned}
$$

Equation (2.14) permits definition of the mass streamfunction:

$$
\begin{aligned}  u=-\frac{1}{r\rho}\frac{\partial \psi}{\partial z}\\ \\ w=\frac{1}{r\rho}\frac{\partial \psi}{\partial r}  \end{aligned}
$$

The SEE follows from the thermal-wind equation (2.12), the thermodynamic equation (2.13), the mass streamfunction implied by continuity (2.14), and the tangential momentum equation (2.2*). Taking the time derivative of Eq. (2.12) gives

$$
\begin{aligned} g\frac{\partial }{\partial r}\frac{\partial \chi}{\partial t}+\frac{\partial }{\partial z}\frac{\partial }{\partial t}(\chi C)=0\\  \Rightarrow g\frac{\partial }{\partial r}\frac{\partial \chi}{\partial t}+\frac{\partial }{\partial z}\big(C\frac{\partial \chi}{\partial t}+\chi\frac{\partial C}{\partial t} \big)=0\\  \Rightarrow g\frac{\partial }{\partial r}\frac{\partial \chi}{\partial t}+\frac{\partial }{\partial z}\big(C\frac{\partial \chi}{\partial t}+\chi\xi\frac{\partial v}{\partial t} \big)=0\\ \end{aligned}
$$

Substitution of Eqs. (2.13) and (2.2*) yields

$$
\begin{aligned}  g\frac{\partial }{\partial r}\big(-u\frac{\partial\chi}{\partial r}-w\frac{\partial \chi}{\partial z}-\chi^2 Q\big)+\frac{\partial }{\partial z}\big[C\big(-u\frac{\partial\chi}{\partial r}-w\frac{\partial \chi}{\partial z}-\chi^2 Q\big)+\chi\xi\big(-w\frac{\partial v}{\partial z}-u\xi_a-F_{\lambda}\big) \big]=0\\ \end{aligned}
$$

Using Eq. (2.12) in the form

$$
\begin{aligned} g\frac{\partial \chi}{\partial r}=-\frac{\partial (\chi C)}{\partial z}\\   \end{aligned}
$$

and substituting the mass streamfunction gives

$$
\begin{aligned}   \frac{\partial }{\partial r}\big[ -g \frac{\partial \chi}{\partial z}\frac{1}{\rho r}\frac{\partial \psi}{\partial r}-\frac{\partial }{\partial z}(\chi C)\frac{1}{\rho r}\frac{\partial \psi}{\partial z} \big]& +\frac{\partial }{\partial z}\big[ \big(\xi\chi(\eta+f)+C\frac{\partial \chi}{\partial r} \big)\frac{1}{\rho r}\frac{\partial \psi}{\partial z}-\frac{\partial }{\partial z}(\chi C)\frac{1}{\rho r}\frac{\partial \psi}{\partial r} \big]\\ &=g\frac{\partial }{\partial r}(\chi^2 Q)+\frac{\partial }{\partial z}(C\chi^2 Q)-\frac{\partial }{\partial z}(\chi \xi F_{\lambda}) ,(2.15) \\ \end{aligned}
$$

Equation (2.15) is the Sawyer-Eliassen equation for the general form of axisymmetric balance theory.
