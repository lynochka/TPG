# What is here?

I made tthis repository as a simple interactive of a truncated plurigaussian model (TPG)
It is created as ipython notebook.

The TPG includes 
*two Gaussian random fields (GRFs):
*covariance function and the ranges are user-defined
*a truncation map (TM) defined on a regular grid with equiprobable gridcells
  +number of gridcells is user-defined,
  +set of categories is user-defined.
*a realization of the set TPG model:
  +field-size is used-defined.

I believe that the implementation and the figures are useful to get familiar with the TPG model notions and parameters.

# What to do with it?

First of all, you can just access [it](https://github.com/lynochka/TPG/blob/master/simpleExampleTPG.ipynb) and look at the code, comments and figure.

Second, if you want to play with it, but do not have ipython notebook installed on your computer, no worries.
Simply
*load the notebook file (or "clone" 
*
```{r, engine='bash'}
git clone https://github.com/lynochka/TPG
```
*if you are familiar with git),
*then open [the browser version](https://try.jupyter.org/) of [the Jupyter Project ](https://jupyter.org/)
*upload the notebook from your local computer,
*choose `Cell` -> `Run All`,
*or run and change notebook cells one-by-one (`Ctrl` + `Enter`) as you like.



  
