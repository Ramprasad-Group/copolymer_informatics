# Copolymer informatics with multi-task neural networks

# IMPORTANT NOTE: The code and data shared here is available for academic non-commercial use only

This is the code for the paper "Copolymer Informatics with Multitask Deep Neural Networks" published at [Macromolecules](https://doi.org/10.1021/acs.macromol.1c00728) (or [Arxiv](https://arxiv.org/abs/2103.14174)). It has two notebooks: The cross-validation models are trained in `cv_model.ipynb` and the meta learner is training in `meta_learner.ipynb`. The meta learner is deployed at https://polymergenome.org.


## Install

1. Poetry must be installed 

```bash
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python
```

2. Clone project (SSH key must be added to your GitHub settings)
```bash
git clone git@github.com:Ramprasad-Group/copolymer_informatics.git
cd copolymer_informatics
```

3. Install environment

```bash
poetry config virtualenvs.in-project true
poetry install
```

## How to use

Make sure the correct environment is selected and the library path is set.

[cv_model.ipynb](copolymer_informatics/cv_model.ipynb) - Train the cross-validation models

[meta_learner.ipynb](copolymer_informatics/meta_learner.ipynb) - Train the meta learner
