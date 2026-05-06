About libmetatensor-torch-feedstock
===================================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/libmetatensor-torch-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/metatensor/metatensor

Package license: BSD-3-Clause

Summary: TorchScript/C++ bindings to metatensor

Documentation: https://docs.metatensor.org

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22404&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libmetatensor-torch-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22404&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libmetatensor-torch-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22404&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libmetatensor-torch-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22404&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libmetatensor-torch-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22404&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libmetatensor-torch-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22404&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/libmetatensor-torch-feedstock?branchName=main&jobName=win&configuration=win%20win_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-libmetatensor--torch-green.svg)](https://anaconda.org/metatensor/libmetatensor-torch) | [![Conda Downloads](https://img.shields.io/conda/dn/metatensor/libmetatensor-torch.svg)](https://anaconda.org/metatensor/libmetatensor-torch) | [![Conda Version](https://img.shields.io/conda/vn/metatensor/libmetatensor-torch.svg)](https://anaconda.org/metatensor/libmetatensor-torch) | [![Conda Platforms](https://img.shields.io/conda/pn/metatensor/libmetatensor-torch.svg)](https://anaconda.org/metatensor/libmetatensor-torch) |

Installing libmetatensor-torch
==============================

Installing `libmetatensor-torch` from the `metatensor` channel can be achieved by adding `metatensor` to your channels with:

```
conda config --add channels metatensor
conda config --set channel_priority strict
```

Once the `metatensor` channel has been enabled, `libmetatensor-torch` can be installed with `conda`:

```
conda install libmetatensor-torch
```

or with `mamba`:

```
mamba install libmetatensor-torch
```

It is possible to list all of the versions of `libmetatensor-torch` available on your platform with `conda`:

```
conda search libmetatensor-torch --channel metatensor
```

or with `mamba`:

```
mamba search libmetatensor-torch --channel metatensor
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search libmetatensor-torch --channel metatensor

# List packages depending on `libmetatensor-torch`:
mamba repoquery whoneeds libmetatensor-torch --channel metatensor

# List dependencies of `libmetatensor-torch`:
mamba repoquery depends libmetatensor-torch --channel metatensor
```




Updating libmetatensor-torch-feedstock
======================================

If you would like to improve the libmetatensor-torch recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`metatensor` channel, whereupon the built conda packages will be available for
everybody to install and use from the `metatensor` channel.
Note that all branches in the conda-forge/libmetatensor-torch-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@HaoZeke](https://github.com/HaoZeke/)
* [@Luthaf](https://github.com/Luthaf/)
* [@PicoCentauri](https://github.com/PicoCentauri/)

