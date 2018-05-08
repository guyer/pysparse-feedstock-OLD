About pysparse
==============


Home: http://pysparse.sourceforge.net

Package license: BSD-2-Clause

Feedstock license: BSD 3-Clause

Summary: Fast sparse matrix library for Python

Pysparse is a fast sparse matrix library for Python. It provides
several sparse matrix storage formats and conversion methods. It also
implements a number of iterative solvers, preconditioners, and
interfaces to efficient factorization packages. Both low-level and
high-level interfaces are available, each with different strengths.


Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/conda-forge/pysparse-feedstock.svg?style=shield)](https://circleci.com/gh/conda-forge/pysparse-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/pysparse-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/pysparse-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/pysparse-feedstock?svg=True)](https://ci.appveyor.com/project/conda-forge/pysparse-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/guyer/pysparse/badges/version.svg)](https://anaconda.org/guyer/pysparse)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/guyer/pysparse/badges/downloads.svg)](https://anaconda.org/guyer/pysparse)

Installing pysparse
===================

Installing `pysparse` from the `guyer` channel can be achieved by adding `guyer` to your channels with:

```
conda config --add channels guyer
```

Once the `guyer` channel has been enabled, `pysparse` can be installed with:

```
conda install pysparse
```

It is possible to list all of the versions of `pysparse` available on your platform with:

```
conda search pysparse --channel guyer
```




Updating pysparse-feedstock
===========================

If you would like to improve the pysparse recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`guyer` channel, whereupon the built conda packages will be available for
everybody to install and use from the `guyer` channel.
Note that all branches in the conda-forge/pysparse-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.