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

.. |docs| image:: https://readthedocs.org/projects/python-simba/badge/?style=flat
    :target: https://readthedocs.org/projects/python-simba
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/cahya-wirawan/python-simba.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/cahya-wirawan/python-simba

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/cahya-wirawan/python-simba?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/cahya-wirawan/python-simba

.. |requires| image:: https://requires.io/github/cahya-wirawan/python-simba/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/cahya-wirawan/python-simba/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/cahya-wirawan/python-simba/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/cahya-wirawan/python-simba

.. |version| image:: https://img.shields.io/pypi/v/simba.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/simba

.. |commits-since| image:: https://img.shields.io/github/commits-since/cahya-wirawan/python-simba/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/cahya-wirawan/python-simba/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/simba.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/simba

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/simba.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/simba

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/simba.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/simba


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD license

Installation
============

::

    pip install simba

Documentation
=============

https://python-simba.readthedocs.io/

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
