========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-ngoimg/badge/?style=flat
    :target: https://readthedocs.org/projects/python-ngoimg
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/Numengo/python-ngoimg.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/Numengo/python-ngoimg

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/Numengo/python-ngoimg?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/Numengo/python-ngoimg

.. |requires| image:: https://requires.io/github/Numengo/python-ngoimg/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/Numengo/python-ngoimg/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/Numengo/python-ngoimg/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/Numengo/python-ngoimg

.. |version| image:: https://img.shields.io/pypi/v/ngoimg.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/ngoimg

.. |commits-since| image:: https://img.shields.io/github/commits-since/Numengo/python-ngoimg/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/Numengo/python-ngoimg/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/ngoimg.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/ngoimg

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/ngoimg.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/ngoimg

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/ngoimg.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/ngoimg


.. end-badges

image utilities

* Free software: GNU General Public License v3

Installation
============

::

    pip install ngoimg

Documentation
=============

https://python-ngoimg.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
