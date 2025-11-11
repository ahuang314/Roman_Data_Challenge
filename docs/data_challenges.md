# Data Challenges

To download and work with the datasets, see the [Getting Started](https://roman-data-challenge.readthedocs.io/en/latest/getting_started/#) page. See the [Submissions page](https://roman-data-challenge.readthedocs.io/en/latest/submissions/#) for submission deadlines and details on what and how to submit.

## Simulations

We assume the survey strategy of the Medium Tier of the High Latitude Wide Area Survey (HLWAS) described in the [Roman Observations Time Allocation Committee's Final Report](https://doi.org/10.48550/arXiv.2505.10574) (released in April 2025). The Medium Tier will cover 2415 square degrees in the F106, F129, and F158 filters with 2 passes, 3 dither positions, and 107 second exposures, for an effective exposure time of 642 seconds (in reality, lower due to chip gaps and variable due to the tiling strategy).

For additional details about the software pipeline used to produce these data, see [Wedig et al. 2025](https://iopscience.iop.org/article/10.3847/1538-4357/adc24f).

!!! note
    We only simulate static, galaxy-galaxy strong gravitational lenses. In other words, we do not simulate quasars, group-scale, or cluster-scale systems.

## Rung 0: Tutorial

{% include "rung_descriptions/rung_0.md" %}

## Rung 1: Substructure or No Substructure?

{% include "rung_descriptions/rung_1.md" %}

The substructure added to 50% of the systems is a `pyHalo` realization of CDM subhalos and line-of-sight halos (`pyHalo.PresetModels.cdm.CDM`). `pyHalo` accounts for this addition of mass to the mass model by also including a negative convergence sheet. We give `pyHalo` the main halo mass, lens redshift, and source redshift, but all other parameters are the defaults (as of the `pyHalo` version utilized which can be found in the dataset's metadata).

<!-- The full `mejiro` configuration YAML file used to generate this dataset is included below:

```yaml
{% include "../data/mejiro_configuration/roman_data_challenge_rung_1.yaml" %}
``` -->

## Rung 2: CDM or WDM?

{% include "rung_descriptions/rung_2.md" %}


!!! warning
    The details of this rung are TBD.