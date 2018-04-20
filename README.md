# Metabolic Modeling Tutorials

This repository contains a few tutorials on metabolic modeling. To run the examples please follow the installation instructions first.

### Installation

To run these tutorials you need a Python 2.7 environment. If you don't have one already, you can install [miniconda](https://conda.io/miniconda.html). 

Once python is setup, you will need to install the [IBM CPLEX Solver](https://www.ibm.com/de-en/marketplace/ibm-ilog-cplex) (recommended version 12.7). Please note that you need to get an academic license from IBM.

After installing CPLEX, you need to install the CPLEX python API as follows:

```
cd (your cplex dir)/cplex/python/2.7/(your architecture)/
python setup.py install
```

Now you need to install the [framed](http://framed.readthedocs.io/en/latest/) library for metabolic modeling:

```
pip install framed
```

If you want to run the model reconstruction tutorial you will also need to install [CarveMe](http://carveme.readthedocs.io/en/latest/):

```
pip install carveme
carveme_init
```

And your job is done.

### Credits and License

Daniel Machado, European Molecular Biology Laboratory, 2018

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.