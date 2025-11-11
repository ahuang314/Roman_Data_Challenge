# Overview

The *Roman Space Telescope* is expected to observe $\mathcal{O}(10^5)$ galaxy-galaxy strong gravitational lenses, providing high angular resolution images of galaxy-galaxy strong gravitational lenses that can be used to probe the nature of dark matter at sub-galactic scales ([Daylan and Birrer 2023](https://arxiv.org/abs/2306.12864), [Wedig et al. 2025](https://iopscience.iop.org/article/10.3847/1538-4357/adc24f)).

The **_Roman_ Data Challenge for Dark Matter Substructure with Galaxy-Galaxy Strong Gravitational Lenses** provides realistic simulated *Roman* images of strong lenses with various dark matter substructure populations and challenges the community to test out substructure detection and characterization pipelines. 

We have simulated datasets of *Roman* strong lenses using the [`mejiro`](https://github.com/AstroMusers/mejiro) package ([Wedig et al. 2025](https://iopscience.iop.org/article/10.3847/1538-4357/adc24f)). `mejiro` uses `SLSim` to simulate a population of galaxy-galaxy strong gravitational lenses, then adds substructure populations from `pyHalo` and instrumental effects with `GalSim` and `STPSF`. Participants may also generate their own simulated data using `mejiro` on the Roman Research Nexus by following the instructions on the [Running `mejiro`](running_mejiro.md) page.

This data challenge aims to achieve the following:

1. Explore optimal approaches for strong lensing substructure analysis
2. Assess how much dark matter information will be available in the *Roman* survey
3. Assess which lenses in the *Roman* survey will be most promising to perform robust analyses on
4. Incentivize scalable methodology to be able to work on *Roman*-scale datasets
5. Support and maintain a research community focused on substructure studies using *Roman*

## Scientific Motivation

Although Cold Dark Matter (CDM) is a widely successful model for predicting the large-scale structure of the Universe, its shortcomings become apparent when used to predict properties of small-scale structures. Examples include the missing satellite problem, where CDM predicts more satellite galaxies than observed, the cusp-core problem, where CDM predicts a higher density of dark matter at the center of galaxies than observed, and more ([Perivolaropoulos and Skara 2022](https://doi.org/10.1016/j.newar.2022.101659)). To explain these discrepancies, other dark matter models have been brought forth, such as the warm dark matter and self-interacting dark matter models. Thus, our aim is to analyze dark matter through strong gravitational lenses, which can allow us to place constraints on these alternative dark matter models.

### Additional Possible Paths of Inquiry

- Einstein radius of main deflector
- Total Halo Mass enclosed in Einstein radius
- Upper/lower bounds on halo mass
- Upper/lower bounds on number of halos
- Sigma_sub, half mode mass, mean number of halos
- Locating largest/most massive halos
- Given halo locations, determine halo concentration

## Timeline

| Date | Event |
|:----:|:-----:|
| November 2025 | Announce to community via Roman Science Collaboration mailing list,<br>emails of the WFS and PIT PIs, and PhysCos newsletter. <br> Potentially also invite SLSC and DESC teams. |
| November 2025 | Rung 0, the trial mini data challenge, begins |
| December 2025 | Rung 0 ends, feedback is incorporated for full data challenge |
| January 2026 | Data challenge begins, starting with Rung 1 |
| Fall 2026 | Data challenge ends |
| Fall 2026 | Submit paper on methodology of challenge, baselining of the submissions, <br>and lessons learned |

## Contact Us

Feedback and questions are welcome, and should be sent to [roman_data_challenge_submissions@stonybrook.edu](mailto:roman_data_challenge_submissions@stonybrook.edu). Additionally, we are active in the #strong-lensing channel in the Roman Space Telescope Slack.
