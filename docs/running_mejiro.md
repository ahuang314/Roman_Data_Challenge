# Generating Datasets

!!! note
    It is not expected that participants will need to generate their own datasets to participate in this data challenge. If you would like a specific dataset generated for your science case, you can follow the instructions here or get in touch with us at [roman_data_challenge_submissions@stonybrook.edu](mailto:roman_data_challenge_submissions@stonybrook.edu).

For participants who would like to generate their own datasets, these instructions walk through how to install and run `mejiro`, the simulation package used to generate the challenge datasets.

## Installation

Follow the installation instructions on the [`mejiro` Read the Docs](https://mejiro.readthedocs.io/en/latest/getting_started/installation.html). Note that both the `roman-technical-information` setup and `STPSF` setup are required for this data challenge.

## Pipeline Execution

Once `mejiro` is installed, prepare a configuration file. The easiest way to do this will be to create a copy of one of the challenge yaml files and edit it. At minimum, the following attributes *must* be updated:

- `data_dir`: the directory where all output data should be written. Note that `mejiro` can produce 10s of GBs for large (>100 sq. deg.) simulated surveys.
- `pipeline_label`: the directory within `data_dir` where the data for the current configuration will be written.
- `survey.catalog_source_kwargs.catalog_path`: if real sources will be used, this must be set to the directory where the catalog is. For more details, see the `SLSim` documentation of the `slsim.Sources.SourceTypes.catalog_source.CatalogSource` class which the `catalog_source_kwargs` are passed through to.

Then, the pipeline can be executed by running the `execute_pipeline.sh` bash script:

```bash
bash execute_pipeline.sh
```

## An Example: (Mini) Rung 1 Dataset

The following `mejiro` configuration file can be used to simulate 1 sq. deg. of the Medium Tier of the HLWAS.

```yaml
{% include "../data/mejiro_configuration/example.yaml" %}
```

## Suggestions

The following configuration options may be useful for this challenge:

- `survey.use_real_sources`: When set to `True`, ``SLSim`` uses real galaxies from the COSMOS catalog as sources. When `False`, Sersic profiles are used.
- `subhalos.fraction`: The fraction of systems to add subhalos and line-of-sight halos to, e.g., 0 uses a smooth mass model for all systems, and 0.5 will add substructure realizations to half of the systems.
- `subhalos.los_normalization`: Set this to 1 to generate line-of-sight halos, and 0 to generate only subhalos.
