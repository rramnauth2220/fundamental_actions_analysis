3D Mind Model Visualization
===========================

This repository has code for visual analyses of the 3D Mind Model by [Thornton & Tamir, 2020]. The data folder includes the 3D value for many mental states.

### References
Thornton, M. A., & Tamir, D. I. (2020). People represent mental states in terms of rationality, social impact, and valence: Validating the 3d Mind Model. Cortex.

## Setup
The code is written in Python 3. To install dependencies:

```bash
$ cd 3dmindmodelvis # this repository
$ python3 -m venv venv # create virtual environment for this project
$ source venv
(venv) $ pip install -r requirements.txt
```

The main script is a Python notebook: `visualize_3d_model.ipynb`. To run the notebook, first
run jupyter notebook:

```bash
(venv) $ jupyter notebook
```

Then open the visualize_3d_model.ipynb in your browser.

