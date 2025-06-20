Overview of the Roman Data Challenge for Dark Matter
===============================================

Note: This page is still under construction, and the details of the challenge are still being fleshed out. Any comments/suggestions are welcome, and should be sent to the following:

- alan.huang.1@stonybrook.edu
- b.t.wedig@wustl.edu
- simon.birrer@stonybrook.edu
- tansu@wustl.edu

Although Cold Dark Matter (CDM) is a widely successful model for predicting the large-scale structure of the universe, its shortcomings become apparent when used to predict properties of small-scale structures. Examples include the missing sattellite problem, where CDM predicts more satellite galaxies than observed, the cusp-core problem, where CDM predicts a higher density of dark matter at the center of galaxies than observed, and more. A review of the CDM model's shortcomings is given in ([Perivolaropoulos and Skara, 2022](https://doi.org/10.1016/j.newar.2022.101659)). As a result, other dark matter models have been brought forth to explain these discrepancies, such as warm dark matter and self-interacting dark matter. Thus, we aim to analyze dark matter through strong gravitational lenses, which can allow us to place constraints on these alternative dark matter models.

With the Roman space telescope HLWAS survey launching in May 2027, ([Wedig et al, 2025](https://iopscience.iop.org/article/10.3847/1538-4357/adc24f)) predicts that there will be about 500 detectable strong lenses with sufficient SNR to be susceptible to robust dark matter analysis. Thus, the Roman data challenge aims to achieve the following:

1. Explore and find optimal approaches for strong lensing substructure analysis
2. Assess how much dark matter information will be available in the Roman survey
3. Assess which lenses in the Roman survey will be most promising to perform robust analyses on
4. Incentivise scalable methodology to be able to work on Roman scale data sets
5. Support and maintain a research community focused on substructure studies using Roman

To this end, we have simulated a dataset of 100,000 strong lensing images containing dark matter substructure using the [mejiro](https://github.com/AstroMusers/mejiro) library. Participants of the data challenge will use these images to determine properties of these strong lenses. Participants may also generate their own simulated data using mejiro on the Roman Research Nexus.


Structure of the challenge
---------------------

We outline several quantifiable metrics which the participants can choose to determine:

- Einstein radius of main deflector
- Total Halo Mass enclosed in Einstein radius
- Upper/lower bounds on halo mass
- Upper/lower bounds on number of halos
- Sigma_sub, half mode mass, mean number of halos
- Locating largest/most massive halos
- Given halo locations, determine halo concentration


Timeline of the challenge
-------------------------------------
| Date | Event |
|:----:|:-----:|
| July 2025 | Announce to community via Roman Science Collaboration mailing list,<br>emails of the WFS and PIT PIs, and PhysCos newsletter. <br> Potentially also invite SLSC and DESC teams. |
| July-August 2025 | Onboarding of the teams (setting up team accounts, supporting data access) |
| August 2025 | Submit proposal to organize splinter session at AAS247 in January 2026 <br> of lensing with Roman (including talks by participating teams) |
| Sep 2025 | Data challenge begins|
| August 2026 | Data challenge ends |
| September 2026 | Submit paper on methodology of challenge, baselining of the submissions, <br>and lessons learned |
