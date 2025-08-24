# Running `mejiro`

## Installation

**mejiro installation instructions are on the mejiro readthedocs**

**any instructions specific to RNN?**

## An Example: (Mini) Rung 1 Dataset

**show a yaml file for a scaled-down version of the config we use to generate the rung 1 dataset**

## Suggestions

The following configuration options may be useful for this challenge:

- `survey.use_real_sources`: When set to `True`, ``SLSim`` uses real galaxies from the COSMOS catalog as sources. When `False`, Sersic profiles are used.
- `subhalos.fraction`: The fraction of systems to add subhalos and line-of-sight halos to, e.g., 0 uses a smooth mass model for all systems, and 0.5 will add substructure realizations to half of the systems.
- `subhalos.los_normalization`: Set this to 1 to generate line-of-sight halos, and 0 to generate only subhalos.
