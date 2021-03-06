# Two challenge problems for horizontal Brownian motion of the Hopf fibration

In [this notebook](hopf-random-walk.ipynb) we set forth a challenge problem for the 
[Math in the Black Forest](https://www.stochastik.uni-freiburg.de/professoren/philipp-harms/shapeworkshop) workshop.
The notebook also serves as an introduction to the Hopf fibration, the simulation of stochastic flows, and the geometry associated with Riemannian submersions. A nice little animation for the non-uniform and uniform random walks is [available here](https://raw.githubusercontent.com/kmodin/hopf-random-walk/master/double-walk.mp4).

The original motivation comes from a corresponding (much more complicated) infinite-dimensional problem, related to stochastic gradient flows on shape space.

## Installation

To run the notebook you need recent versions of `numpy`, `scipy`, `matplotlib`, and `numba`. 
In addition, you need the [quaternion module](https://github.com/moble/quaternion). 
If you are using `conda` it is easily installed with
```
conda install -c conda-forge quaternion
``` 
or for `pip` users
```
pip install --user numpy numpy-quaternion
```