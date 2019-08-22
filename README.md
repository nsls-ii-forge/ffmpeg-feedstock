About ffmpeg
============

Home: http://www.ffmpeg.org/

Package license: GPL 3

Feedstock license: BSD 3-Clause

Summary: Cross-platform solution to record, convert and stream audio and video.



Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=76&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/ffmpeg-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=76&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/ffmpeg-feedstock?branchName=master&jobName=linux&configuration=linux_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=76&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/ffmpeg-feedstock?branchName=master&jobName=osx&configuration=osx_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_c_compilervs2008cxx_compilervs2008</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=76&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/ffmpeg-feedstock?branchName=master&jobName=win&configuration=win_c_compilervs2008cxx_compilervs2008" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_c_compilervs2015cxx_compilervs2015</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=76&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/ffmpeg-feedstock?branchName=master&jobName=win&configuration=win_c_compilervs2015cxx_compilervs2015" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
![ppc64le disabled](https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg)
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-ffmpeg-green.svg)](https://anaconda.org/nsls2forge/ffmpeg) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/ffmpeg.svg)](https://anaconda.org/nsls2forge/ffmpeg) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/ffmpeg.svg)](https://anaconda.org/nsls2forge/ffmpeg) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/ffmpeg.svg)](https://anaconda.org/nsls2forge/ffmpeg) |

Installing ffmpeg
=================

Installing `ffmpeg` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `ffmpeg` can be installed with:

```
conda install ffmpeg
```

It is possible to list all of the versions of `ffmpeg` available on your platform with:

```
conda search ffmpeg --channel nsls2forge
```




Updating ffmpeg-feedstock
=========================

If you would like to improve the ffmpeg recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/ffmpeg-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@183amir](https://github.com/183amir/)
* [@carlodri](https://github.com/carlodri/)
* [@caspervdw](https://github.com/caspervdw/)
* [@danielballan](https://github.com/danielballan/)
* [@jakirkham](https://github.com/jakirkham/)
* [@ocefpaf](https://github.com/ocefpaf/)
* [@patricksnape](https://github.com/patricksnape/)
* [@sdvillal](https://github.com/sdvillal/)

