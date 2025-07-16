=========
Photutils
=========

|PyPI Version| |Conda Version| |PyPI Downloads| |Astropy|

|CI Status| |Codecov Status| |Latest RTD Status|

This is a fork of photutils that allows for parallel evaluation of
ellipse isophotes. To compile, you must have a library like OpenMP
installed and set the appropriate flags; for example:
`CFLAGS="${CFLAGS} -fopenmp" LDFLAGS="${LDFLAGS} -lomp" pip install .`
There does not yet appear to be a simple way to enable parallel compilation
with pyproject.toml.

Photutils is a Python library that provides commonly-used tools
and key functionality for detecting and performing photometry of
astronomical sources. Tools are provided for background estimation,
star finding, source detection and extraction, aperture photometry,
PSF photometry, image segmentation, centroids, radial profiles,
and elliptical isophote fitting. It is a `coordinated package
<https://www.astropy.org/affiliated/index.html>`_ of `Astropy`_ and
integrates well with other Astropy packages, making it a powerful tool
for astronomical image analysis.

Please see the `online documentation
<https://photutils.readthedocs.io>`_ for `installation instructions
<https://photutils.readthedocs.io/en/stable/getting_started/install.html>`_ and usage
information.


Citing Photutils
----------------

|Zenodo|

If you use Photutils for a project that leads to a publication,
whether directly or as a dependency of another package, please include
the following acknowledgment::

    This research made use of Photutils, an Astropy package for
    detection and photometry of astronomical sources (Bradley et al.
    <YEAR>).

where (Bradley et al. <YEAR>) is a citation to the `Zenodo record
<https://doi.org/10.5281/zenodo.596036>`_ of the Photutils
version that was used. We also encourage citations in the
main text wherever appropriate. Please see the `CITATION
<https://github.com/astropy/photutils/blob/main/photutils/CITATION.rst>`_
file for details and an example BibTeX entry.


License
-------

Photutils is licensed under a 3-clause BSD license.  Please see the
`LICENSE
<https://github.com/astropy/photutils/blob/main/LICENSE.rst>`_ file
for details.


.. |PyPI Version| image::  https://img.shields.io/pypi/v/photutils.svg?logo=pypi&logoColor=white&label=PyPI
    :target: https://pypi.org/project/photutils/
    :alt: PyPI Latest Release

.. |Conda Version| image:: https://img.shields.io/conda/vn/conda-forge/photutils
    :target: https://anaconda.org/conda-forge/photutils
    :alt: Conda Latest Release

.. |PyPI Downloads| image:: https://img.shields.io/pypi/dm/photutils?label=PyPI%20Downloads
    :target: https://pypistats.org/packages/photutils
    :alt: PyPI Downloads

.. |Astropy| image:: https://img.shields.io/badge/powered%20by-AstroPy-orange.svg?style=flat
    :target: https://www.astropy.org/
    :alt: Powered by Astropy

.. |Zenodo| image:: https://zenodo.org/badge/2640766.svg
    :target: https://zenodo.org/doi/10.5281/zenodo.596036
    :alt: Zenodo Latest DOI

.. |CI Status| image:: https://github.com/astropy/photutils/workflows/CI%20Tests/badge.svg#
    :target: https://github.com/astropy/photutils/actions
    :alt: CI Status

.. |Codecov Status| image:: https://img.shields.io/codecov/c/github/astropy/photutils?logo=codecov
    :target: https://codecov.io/gh/astropy/photutils
    :alt: Coverage Status

.. |Stable RTD Status| image:: https://img.shields.io/readthedocs/photutils/latest.svg?logo=read%20the%20docs&logoColor=white&label=Docs&version=stable
    :target: https://photutils.readthedocs.io/en/stable/
    :alt: Stable Documentation Status

.. |Latest RTD Status| image:: https://img.shields.io/readthedocs/photutils/latest.svg?logo=read%20the%20docs&logoColor=white&label=Docs&version=latest
    :target: https://photutils.readthedocs.io/en/latest/
    :alt: Latest Documentation Status

.. _Astropy: https://www.astropy.org/
