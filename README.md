About omniscidb-ext
===================

Home: https://www.omnisci.com/

Package license: Apache-2.0

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/omniscidb-feedstock/blob/master/LICENSE.txt)

Summary: The OmniSci database

Development: https://github.com/omnisci/omniscidb

Documentation: https://www.omnisci.com/docs/latest/

OmniSciDB is an in-memory, column store, SQL relational database
that was designed from the ground up to run on GPUs.

This recipe provides the following packages:
  omniscidb-commong
  CUDA-enabled omniscidb, cpu and cuda builds
  pyomniscdb
  omniscidb embedding library, cpu and cuda builds
  omniscidb-embedded Python extension module


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9937&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/omniscidb-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_c_compiler_version9cuda_compiler_version11.0cxx_compiler_version9</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9937&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/omniscidb-feedstock?branchName=master&jobName=linux&configuration=linux_64_c_compiler_version9cuda_compiler_version11.0cxx_compiler_version9" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_c_compiler_version9cuda_compiler_versionNonecxx_compiler_version9</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9937&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/omniscidb-feedstock?branchName=master&jobName=linux&configuration=linux_64_c_compiler_version9cuda_compiler_versionNonecxx_compiler_version9" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-omniscidb-green.svg)](https://anaconda.org/conda-forge/omniscidb) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/omniscidb.svg)](https://anaconda.org/conda-forge/omniscidb) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/omniscidb.svg)](https://anaconda.org/conda-forge/omniscidb) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/omniscidb.svg)](https://anaconda.org/conda-forge/omniscidb) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-omniscidb--common-green.svg)](https://anaconda.org/conda-forge/omniscidb-common) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/omniscidb-common.svg)](https://anaconda.org/conda-forge/omniscidb-common) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/omniscidb-common.svg)](https://anaconda.org/conda-forge/omniscidb-common) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/omniscidb-common.svg)](https://anaconda.org/conda-forge/omniscidb-common) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-omniscidbe-green.svg)](https://anaconda.org/conda-forge/omniscidbe) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/omniscidbe.svg)](https://anaconda.org/conda-forge/omniscidbe) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/omniscidbe.svg)](https://anaconda.org/conda-forge/omniscidbe) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/omniscidbe.svg)](https://anaconda.org/conda-forge/omniscidbe) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pyomniscidb-green.svg)](https://anaconda.org/conda-forge/pyomniscidb) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/pyomniscidb.svg)](https://anaconda.org/conda-forge/pyomniscidb) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/pyomniscidb.svg)](https://anaconda.org/conda-forge/pyomniscidb) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/pyomniscidb.svg)](https://anaconda.org/conda-forge/pyomniscidb) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pyomniscidbe-green.svg)](https://anaconda.org/conda-forge/pyomniscidbe) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/pyomniscidbe.svg)](https://anaconda.org/conda-forge/pyomniscidbe) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/pyomniscidbe.svg)](https://anaconda.org/conda-forge/pyomniscidbe) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/pyomniscidbe.svg)](https://anaconda.org/conda-forge/pyomniscidbe) |

Installing omniscidb-ext
========================

Installing `omniscidb-ext` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `omniscidb, omniscidb-common, omniscidbe, pyomniscidb, pyomniscidbe` can be installed with:

```
conda install omniscidb omniscidb-common omniscidbe pyomniscidb pyomniscidbe
```

It is possible to list all of the versions of `omniscidb` available on your platform with:

```
conda search omniscidb --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating omniscidb-ext-feedstock
================================

If you would like to improve the omniscidb-ext recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/omniscidb-ext-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@andrewseidl](https://github.com/andrewseidl/)
* [@jclay](https://github.com/jclay/)
* [@pearu](https://github.com/pearu/)
* [@xmnlab](https://github.com/xmnlab/)

