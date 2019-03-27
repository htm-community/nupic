# <img src="http://numenta.org/87b23beb8a4b7dea7d88099bfb28d182.svg" alt="NuPIC Logo" width=100/> NuPIC

## nupic.py (NuPIC Community Fork)

[![Build Status](https://travis-ci.com/htm-community/nupic.py.svg?branch=master)](https://travis-ci.com/htm-community/nupic.py)

This is a __community fork__ of the The Numenta Platform for Intelligent Computing (**NuPIC**), a machine intelligence platform that implements the [HTM learning algorithms](https://numenta.com/resources/papers-videos-and-more/). HTM is a detailed computational theory of the neocortex. At the core of HTM are time-based continuous learning algorithms that store and recall spatial and temporal patterns. NuPIC is suited to a variety of problems, particularly anomaly detection and prediction of streaming data sources. For questions or discussion, see [our forum](https://discourse.numenta.org/c/nupic/community-fork).

## Installing nupic.py

NuPIC binaries are available for:

- Linux x86 64bit
- OS X 10.9
- OS X 10.10
- Windows 64bit

### Dependencies

The following dependencies are required to install NuPIC on all operating systems.

- [Python 2.7](https://www.python.org/)
- [pip](https://pip.pypa.io/en/stable/installing/)>=8.1.2
- [setuptools](https://setuptools.readthedocs.io)>=25.2.0
- [wheel](http://pythonwheels.com)>=0.29.0
- [numpy](http://www.numpy.org/)
- C++ 11 compiler like [gcc](https://gcc.gnu.org/) (4.8+) or [clang](http://clang.llvm.org/)

Additional OS X requirements:

- [Xcode command line tools](https://developer.apple.com/library/ios/technotes/tn2339/_index.html)

### Install

TODO

### Test

    # From the root of the repo:
    py.test tests/unit

### Installing nupic.py From Source

To install from local source code, run from the repository root:

    pip install .

Use the optional `-e` argument for a developer install.

If you want to build the dependent `nupic.bindings` from source, you should build and install from [`nupic.core`](https://github.com/numenta/nupic.core) prior to installing nupic (since a PyPI release will be installed if `nupic.bindings` isn't yet installed).
