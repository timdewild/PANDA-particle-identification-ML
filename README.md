# Particle Classification in the PANDA Experiment using Machine Learning

## Background
The PANDA experiment will study the annihilation of protons with anti-protons to learn how the fundamental building blocks of nature, quarks and gluons, form building blocks of matter such as the proton or neutron. The experiment will use a very high intensity anti-proton beam hitting a fixed proton target. In the resulting $\bar{p}p$ annihilations, radiation is emitted, consisting of various different kind of particles. The setup is composed of different components, all capable of detecting different kinds of particles. 

In this project, we focus on the electromagnetic-calorimeter (EMC). The EMC is designed to measure the scattering angle and energy of high-energetic photons originating from the $\bar{p}p$ interaction point. A schematic of the EMC is shown below. All the rectangular cells correspond crystals. When a photon hits a crystal cell, a secondary shower of photons, electrons and positrons is created covering the adjacent cells, thereby dopisiting energy in those cells as well. The energy deposit in each cell will generate scintillation light that is detected by photodiodes and converted into an electric signal. In short, high-energy photons originating from the $\bar{p}p$ create a secondary shower of radiation that 'fires' up a cluster of neighbouring crystal cells. The properties of these clusters can be used to reconstruct the properties of the incident photon. 

<div align="center">
    <img src="/images/emc_panda.png" alt="Electromagnetic Calorimeter" width="500"/>
</div>
<div align="center">Schematic image of the EMC.</div>

In addition to photons (the signal events), the EMC is also triggered by various background sources. Much of these background events are triggered by neutrons, which generate secondary showers as well, thereby mimicking the photons. One of the challenges is therefore to discriminate between photons events (the signal) and neutron events (the background). 

# Goal
In this project, the goal will be to use machine learning techniques to discriminate between signal and background events. The response of the EMC to photon and neutron events is simulated using Monte Carlo techniques, resulting in two datasets:
1. The `emc_gamma.csv` dataset, containing about 50000 simulated events induced by photons in the momentum range 1-5 GeV/c.
2. The `emc_neutron.csv` dataset, containing about 50000 simulated events induced by neutrons in the same momentum range. 





 two datasets used for this project are:
1. 

