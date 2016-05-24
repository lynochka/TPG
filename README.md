# What is here?

I made tthis repository as a simple interactive of a truncated plurigaussian model (TPG)
It is created as ipython notebook.

The TPG includes 
* two two-dimensional Gaussian random fields (GRFs);
* covariance function and the ranges that are user-defined;
* a truncation map (TM) defined on a regular grid with equiprobable gridcells
  + number of gridcells that is user-defined,
  + set of categories that is user-defined,
  + categories assigned to the gridcells randomly, controled by a random seed;
* a random realization of the TPG model, controled by a random seed:
  + size field is user-defined.

I believe that the implementation and the figures are useful to get familiar with the TPG model notions and parameters.

# What to do with it?

First of all, you can just access [the notebook file simpleExampleTPG.ipynb](https://github.com/lynochka/TPG/blob/master/simpleExampleTPG.ipynb) and look at the comments, figure and code.

Second, if you want to play with it, but do not have ipython notebook installed on your computer, no worries.
Simply
* load the notebook file (or if you are familiar with git, you could "clone" the repository to a local folder with
```{r, engine='bash'}
git clone https://github.com/lynochka/TPG
```
* then open [the browser version](https://try.jupyter.org/) of [the Jupyter Project ](https://jupyter.org/)
* upload the notebook from your local computer,
* choose `Cell` -> `Run All`,
* or run and change notebook cells one-by-one (`Ctrl` + `Enter`) as you like.

If you are familar with ipython-notebook, then you know what to do.

# How to reference?

If you decide to use parts of the code or reference the example please use:

Author: Alina Astrakova
Source: https://github.com/lynochka/TPG

  
