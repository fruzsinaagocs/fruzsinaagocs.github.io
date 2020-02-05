---
layout: page
title: Research
---

## oscode - fast numerical solution of **osc**illatory **o**rdinary **d**ifferential **e**quations

- [paper](https://arxiv.org/pdf/1906.01421.pdf) and [slides](https://fruzsinaagocs.github.io/images/IoA_Wednesday_talk.pdf) from a recent [talk](https://fruzsinaagocs.github.io/events/)
- [open-source code](https://github.com/fruzsinaagocs/oscode) and its
  [documentation](https://oscode.readthedocs.io/en/latest/introduction.html)

`oscode` is a numerical routine that you can call from Python or C++; it is
built to (extremely efficiently) solve equations of the form \\[\label{eq:osc}
\ddot{x} + 2\gamma(t)\dot{x} + \omega^2(t)x = 0, \\] where $\omega(t)$ and
$\gamma(t)$ can be *explicit* functions of time, or just be computed numerically
and given as *arrays*.

In simple terms,`oscode` is faster than conventional solvers (e.g. `scipy.odeint.integrate`, or
`Mathematica`'s built-in solver) because it makes use of an analytic
approximation of $x(t)$ to skip over long regions of oscillations. This
approximation is valid when the frequency $\omega(t)$ changes slowly relative to
the timescales of integration, therefore it is worth applying `oscode` when this
condition holds for at least some part of the integration range.

Equations like (\ref{eq:osc}) are common in physics. The one-dimensional
Schroedinger equation has this form, as does the Mukhanov-Sasaki equation, which
allows us to compute *primordial power spectra* of curvature perturbations,
precursors of the anisotropies in the Cosmic Microwave Background (CMB). With `oscode`
it is possivle to compute primordial power spectra much faster, allowing faster
inference of parameters in cosmological models. For example, the spectra below
belong to closed universes with increasing initial curvature - it would take
**$\geq $** **30 minutes** to compute one of these on my laptop with `scipy`, and
takes about **1 s** with `oscode`.

![gif of primordial power spectra](images/spectra.gif)


## Quantum initial conditions for inflation

This *work in progress* investigates different methods to define the ground
state in a curved, non-static spacetime. Some of the well-known methods suffer
from a *gauge dependence*: a non-physical transformation results in the method
giving a physically different solution for the vacuum. This work shows the
physical consequences this gauge-dependence may have on the CMB.
