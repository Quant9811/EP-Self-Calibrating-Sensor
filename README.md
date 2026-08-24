# Self-Calibrating Exceptional-Point Sensing with Ensemble Quantum Reservoirs

Reproducible implementation and numerical results for a self-calibrating
exceptional-point (EP) sensing framework that combines ensemble quantum
reservoir computing, Fisher-information-guided interrogation, device-domain
evaluation, dynamic tracking, and closed-loop stabilization.

## Overview

Exceptional-point sensors can exhibit strong nonlinear responses to small
perturbations, but practical estimation is affected by measurement noise,
device-parameter uncertainty, operating-point drift, and the distinction
between spectral sensitivity and statistically achievable precision.

This repository contains the numerical implementation and final frozen
experimental record associated with the manuscript:

> Self-Calibrating Exceptional-Point Sensing with Ensemble Quantum Reservoir
> Estimation and Fisher-Optimized Interrogation

The framework combines:

- time-resolved measurement of a non-Hermitian exceptional-point sensor;
- quantum reservoir computing (QRC) as a fixed nonlinear temporal feature map;
- an ensemble of independently initialized quantum reservoirs;
- a classical ridge-regression readout for estimating the perturbation
  parameter and exceptional-point displacement;
- Fisher-D-optimal probe selection with nuisance-parameter elimination;
- out-of-distribution evaluation under device-domain variation;
- dynamic exceptional-point tracking;
- closed-loop stabilization using the estimated operating-point displacement;
- robustness evaluation against photon-budget, detector-noise, and phase-noise
  variations.

The study deliberately does **not** claim a universal quantum advantage over
classical machine-learning methods. The classical reservoir is retained as a
primary reference throughout the evaluation.

 
