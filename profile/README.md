# Rolston Lab

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=28&duration=2800&pause=900&color=0E7490&center=true&vCenter=true&width=980&lines=Perovskite+Photovoltaics+%26+Battery+Reliability;Machine+Learning+for+Energy+Materials;Rolston+Lab+%7C+Arizona+State+University" alt="Rolston Lab animated intro" />
</p>

<p align="center">
  <a href="https://github.com/rolston-lab-asu">
    <img src="https://img.shields.io/badge/GitHub-rolston--lab--asu-111827?style=for-the-badge&logo=github" alt="Rolston Lab GitHub" />
  </a>
  <a href="https://rolston.lab.asu.edu/">
    <img src="https://img.shields.io/badge/Website-rolston.lab.asu.edu-0F766E?style=for-the-badge" alt="Rolston Lab website" />
  </a>
</p>

The Rolston Lab at Arizona State University studies reliability and materials science
challenges in energy technologies, across both photovoltaics and batteries. This organization
holds the lab's open code: measurement and automation tools, data pipelines, and machine
learning work built around our own experimental data.

## Research areas

**Perovskite photovoltaics.** Durability, processing, and characterization of perovskite solar
cells, including automated device measurement and impedance-based diagnostics.

**Lithium-ion batteries.** Degradation and health prediction from cycling and electrochemical
impedance spectroscopy (EIS) data, with an emphasis on reproducible pipelines from raw
instrument files through to trained models.

The two areas share a lot of method. Impedance spectroscopy, accelerated ageing, and the
data-analysis tooling built for one usually transfers to the other.

## Selected projects

| Project | Area | What it is |
|---|---|---|
| [PixelMux](https://github.com/rolston-lab-asu/PixelMux) | Solar | PyQt5 GUI for automated multi-pixel solar cell IV characterization, driving a Keithley 2460 SMU and a Numato 16-channel relay |
| [Perovskite-EIS](https://github.com/rolston-lab-asu/Perovskite-EIS) | Solar | Impedance analysis for perovskite devices |
| [Battery-Data-Visualizer](https://github.com/rolston-lab-asu/Battery-Data-Visualizer) | Battery | Single-file browser viewer for BioLogic EC-Lab `.mpt` exports: impedance plots, per-cycle trends, and Excel export |
| [LIB-EIS-ML](https://github.com/rolston-lab-asu/LIB-EIS-ML) | Battery | Molicel battery degradation prediction using machine learning |
| [BO-for-Energy-material](https://github.com/rolston-lab-asu/BO-for-Energy-material) | Both | Bayesian optimization applied to energy materials |

Other repositories in this organization hold work in progress and forks used by the lab.

## About

- Website: https://rolston.lab.asu.edu/
- GitHub: https://github.com/rolston-lab-asu

Much of this code is in active development and written alongside ongoing experiments, so
interfaces and structure change as projects progress.
