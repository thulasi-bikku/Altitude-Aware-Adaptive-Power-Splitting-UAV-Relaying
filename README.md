# Altitude-Aware-Adaptive-Power-Splitting-UAV-Relaying
Simulation code and numerical analysis for altitude-aware adaptive power splitting with opportunistic user scheduling in energy-harvesting UAV relaying over mixed α–κ–μ and Rayleigh fading channels. Includes outage probability, throughput, average bit error rate, diversity-order analysis, altitude optimization, and Monte Carlo validation.
# Altitude-Aware Adaptive Power Splitting for Energy-Harvesting UAV Relaying

## Overview
This repository accompanies the research paper titled **“Altitude-Aware Adaptive Power Splitting with Opportunistic User Scheduling for Energy-Harvesting UAV Relaying over Mixed α–κ–μ and Rayleigh Fading Channels.”**

The study investigates a dual-hop decode-and-forward (DF) unmanned aerial vehicle (UAV) relay that harvests radio-frequency energy using adaptive power splitting and serves the ground user with the strongest instantaneous channel.

## Main Features
- Adaptive power-splitting optimization under a saturating energy-harvesting model.
- Opportunistic scheduling of multiple ground users.
- Air-to-ground channel modeling using elevation-dependent α–κ–μ fading.
- Rayleigh fading for the relay-to-user links.
- Outage probability and diversity-order analysis.
- Ergodic and delay-limited throughput evaluation.
- Average bit error rate (ABER) analysis.
- UAV altitude optimization for outage minimization.
- Monte Carlo simulations for validating analytical results.
- Benchmark comparisons with fixed power splitting, time-switching relaying, random user selection, and an ideal linear harvester.

## Simulation Parameters
The default configuration uses four ground users, an energy-conversion efficiency of 0.75, a saturation-power fraction of 0.03, and a target data rate of 1 bps/Hz. The default UAV altitude is 100 m, with an altitude search interval of 20–300 m.

Additional channel and system parameters are provided in Table 1 of the accompanying manuscript.

## Reproducibility
The analytical expressions, simulation parameters, and performance results are documented in the manuscript. The repository is intended to provide the implementation used to reproduce the reported numerical results.

## Authors
- Pamarthi Venkatasivarambabu
- Arepalli Gopi
- Thulasi Bikku
- Jeevana Jyothi Pujari
- Vakkalakula Bharath Sreenivasulu
- Jaya Lakshmi Tangirala

## License
A license should be selected by the repository owner before redistribution or reuse of the code.

## Citation
Please cite the associated research paper when using this repository. Add the final publication details here once available.
