========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |requires|
        | |coveralls| |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|


.. |travis| image:: https://api.travis-ci.org/samesense/python-tabcat.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/samesense/python-tabcat

.. |requires| image:: https://requires.io/github/samesense/python-tabcat/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/samesense/python-tabcat/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/samesense/python-tabcat/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/samesense/python-tabcat

.. |codecov| image:: https://codecov.io/github/samesense/python-tabcat/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/samesense/python-tabcat

.. |version| image:: https://img.shields.io/pypi/v/tabcat.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/tabcat

.. |wheel| image:: https://img.shields.io/pypi/wheel/tabcat.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/tabcat

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/tabcat.svg
    :alt: Supported versions
    :target: https://pypi.org/project/tabcat

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/tabcat.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/tabcat

.. |commits-since| image:: https://img.shields.io/github/commits-since/samesense/python-tabcat/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/samesense/python-tabcat/compare/v0.0.0...master



.. end-badges

Concatenate tab files

* Free software: MIT license

Installation
============

::

    pip install tabcat

You can also install the in-development version with::

    pip install https://github.com/samesense/python-tabcat/archive/master.zip


Documentation
=============


1


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
