# Overview

!!! warning
    The data challenge has not yet started, and this documentation is still under constructions. Any comments/suggestions are welcome, and should be sent to the following:

    - [alan.huang.1@stonybrook.edu](mailto:alan.huang.1@stonybrook.edu)
    - [b.t.wedig@wustl.edu](mailto:b.t.wedig@wustl.edu)
    - [simon.birrer@stonybrook.edu](mailto:simon.birrer@stonybrook.edu)
    - [tansu@wustl.edu](mailto:tansu@wustl.edu)
    - [xhuang22@usfca.edu](mailto:xhuang22@usfca.edu)

The *Roman Space Telescope* is expected to observe $\mathcal{O}(10^5)$ galaxy-galaxy strong gravitational lenses, providing high angular resolution images of galaxy-galaxy strong gravitational lenses that can be used to probe the nature of dark matter at sub-galactic scales ([Daylan and Birrer 2023](https://arxiv.org/abs/2306.12864), [Wedig et al. 2025](https://iopscience.iop.org/article/10.3847/1538-4357/adc24f)).

The **_Roman_ Data Challenge for Dark Matter Substructure with Galaxy-Galaxy Strong Gravitational Lenses** provides realistic simulated *Roman* images of strong lenses with various dark matter substructure populations and challenges the community to test out substructure detection and characterization pipelines. 

We have simulated datasets of *Roman* strong lenses using the [`mejiro`](https://github.com/AstroMusers/mejiro) package ([Wedig et al. 2025](https://iopscience.iop.org/article/10.3847/1538-4357/adc24f)). `mejiro` uses `SLSim` to simulate a population of galaxy-galaxy strong gravitational lenses, then adds substructure populations from `pyHalo` and instrumental effects with `GalSim` and `STPSF`. Participants may also generate their own simulated data using `mejiro` on the Roman Research Nexus by following the instructions on the [Running `mejiro`](running_mejiro.md) page.

This data challenge aims to achieve the following:

1. Explore optimal approaches for strong lensing substructure analysis
2. Assess how much dark matter information will be available in the *Roman* survey
3. Assess which lenses in the *Roman* survey will be most promising to perform robust analyses on
4. Incentivize scalable methodology to be able to work on *Roman*-scale datasets
5. Support and maintain a research community focused on substructure studies using *Roman*

## Background

Although Cold Dark Matter (CDM) is a widely successful model for predicting the large-scale structure of the Universe, its shortcomings become apparent when used to predict properties of small-scale structures. Examples include the missing satellite problem, where CDM predicts more satellite galaxies than observed, the cusp-core problem, where CDM predicts a higher density of dark matter at the center of galaxies than observed, and more ([Perivolaropoulos and Skara 2022](https://doi.org/10.1016/j.newar.2022.101659)). To explain these discrepancies, other dark matter models have been brought forth, such as the warm dark matter and self-interacting dark matter models. Thus, our aim is to analyze dark matter through strong gravitational lenses, which can allow us to place constraints on these alternative dark matter models.

## Structure

### Rung 1: Substructure or No Substructure?

The objective is to determine whether a given system has dark matter substructure or not. Systems with substructure will have subhalos in the dark matter halo of the deflector and line-of-sight halos. Systems without dark matter substructure will simply be smooth mass models.

### Rung 2: CDM or WDM?

This will quantify a pipeline's ability to detect the collective perturbative effect of a population of low-mass subhalos.

### Additional possible paths of inquiry

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
| Fall 2025 | Announce to community via Roman Science Collaboration mailing list,<br>emails of the WFS and PIT PIs, and PhysCos newsletter. <br> Potentially also invite SLSC and DESC teams. |
| Fall 2025 | Onboarding of the teams (setting up team accounts, supporting data access) |
| Fall 2025 | Submit proposal to organize splinter session at AAS247 in January 2026 <br> of lensing with Roman (including talks by participating teams) |
| Fall 2025 | Data challenge begins|
| Fall 2026 | Data challenge ends |
| Fall 2026 | Submit paper on methodology of challenge, baselining of the submissions, <br>and lessons learned |
