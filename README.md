Medusa
======
 
Medusa is an approach to detect size-`k` modules of objects that, taken together, appear most significant to another set of objects. 

Medusa operates on large-scale collections of heterogeneous data sets and explicitly distinguishes between diverse data semantics. It builds on [collective matrix factorization](http://dx.doi.org/10.1109/TPAMI.2014.2343973) to derive different semantics, and it formulates the growing of the modules as a submodular optimization program. Medusa is flexible in choosing or combining the semantic meanings, and provides theoretical guarantees about the detection quality. 

This repository contains supplementary material for *Jumping across biomedical contexts using compressive data fusion* by Marinka Zitnik and Blaz Zupan.
 
 
Dependencies
------------
The required dependencies to build the software are `Numpy >= 1.8`, `SciPy >= 0.10`.


Usage
-----

[synthetic.py](synthetic.py) - Demonstrates Medusa on synthetic semantics.
    
See also [scikit-fusion](http://github.com/marinkaz/scikit-fusion), our module
for data fusion using collective latent factor models. 


Install
-------
To install in your home directory, use

    python setup.py install --user

To install for all users on Unix/Linux

    python setup.py build
    sudo python setup.py install

To install in development mode

    python setup.py develop


Citing
------

    @article{Zitnik2016,
      title     = {Jumping across biomedical contexts using compressive data fusion},
      author    = {Zitnik, Marinka and Zupan, Blaz},
      journal   = {},
      volume    = {},
      number    = {},
      pages     = {},
      year      = {},
      publisher = {}
    }
    
    
License
-------
Medusa is licensed under the GPLv2.