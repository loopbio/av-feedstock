About av
========

Home: https://github.com/mikeboers/PyAV/

Package license: BSD 3-Clause

Feedstock license: BSD 3-Clause

Summary: Pythonic bindings for FFmpeg.

PyAV is a Pythonic binding for FFmpeg or Libav. We aim to provide all of
the power and control of the underlying library, but manage the gritty
details as much as possible.


Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/loopbio/av-feedstock/master.svg?label=Linux)](https://circleci.com/gh/loopbio/av-feedstock)
![OSX disabled](https://img.shields.io/badge/OSX-disabled-lightgrey.svg)
![Windows disabled](https://img.shields.io/badge/Windows-disabled-lightgrey.svg)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-av-green.svg)](https://anaconda.org/loopbio/av) | [![Conda Downloads](https://img.shields.io/conda/dn/loopbio/av.svg)](https://anaconda.org/loopbio/av) | [![Conda Version](https://img.shields.io/conda/vn/loopbio/av.svg)](https://anaconda.org/loopbio/av) | [![Conda Platforms](https://img.shields.io/conda/pn/loopbio/av.svg)](https://anaconda.org/loopbio/av) |

Installing av
=============

Installing `av` from the `loopbio` channel can be achieved by adding `loopbio` to your channels with:

```
conda config --add channels loopbio
```

Once the `loopbio` channel has been enabled, `av` can be installed with:

```
conda install av
```

It is possible to list all of the versions of `av` available on your platform with:

```
conda search av --channel loopbio
```




Updating av-feedstock
=====================

If you would like to improve the av recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`loopbio` channel, whereupon the built conda packages will be available for
everybody to install and use from the `loopbio` channel.
Note that all branches in the loopbio/av-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.
