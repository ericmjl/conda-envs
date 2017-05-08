# conda-envs
My conda environment YAML files

## TL;DR "how to use"

### Initial Install

```bash
$ wget https://raw.githubusercontent.com/ericmjl/conda-envs/master/{env_name}.yml -O environment.yml
$ conda env crate -f environment.yml
$ source activate {env_name}
```

### Update

```bash
$ wget https://raw.githubusercontent.com/ericmjl/conda-envs/master/{env_name}.yml -O environment.yml
$ conda env update -f environment.yml  # this is where the update magic happens
$ source activate {env_name}
```

## Purpose

This repository exists because I sometimes share environments across projects. Keeping multiple environment specs in sync is a hassle. This is my hack for keeping things in sync.
