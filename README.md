# DTTGF : A Delaunay Triangulation based TSP-solver Generalization Framework for Large Scale TSP Instance
The code and appendix of Enhancing Large-scale UAV Route Planing with Global and Local Features via Reinforcement Graph Fusion
## Dependencies

Other Dependencies in environment.yaml

* Python>=3.8
* NumPy
* SciPy
* Jupyter Notebook
* CUDA = 11.3
* [PyTorch](http://pytorch.org/) = 1.10.1
* tqdm
* Matplotlib (optional, only for plotting)

## Usage

First, configure the environment according to the environment.yaml

To install the cython_merge module, run the following command:

```bash
cd utils/WU/cython_merge
python setup.py build_ext --inplace
cd -
```

##Specific steps are given in DTTGF_for_one_stage.ipynb and DTTGF_for_two_stage.ipynb

