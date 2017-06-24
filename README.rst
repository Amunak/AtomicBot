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
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/AtomicBot/badge/?style=flat
    :target: https://readthedocs.org/projects/AtomicBot
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/Amunak/AtomicBot.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/Amunak/AtomicBot

.. |requires| image:: https://requires.io/github/Amunak/AtomicBot/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/Amunak/AtomicBot/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/Amunak/AtomicBot/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/Amunak/AtomicBot

.. |version| image:: https://img.shields.io/pypi/v/atomicbot.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/atomicbot

.. |commits-since| image:: https://img.shields.io/github/commits-since/Amunak/AtomicBot/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/Amunak/AtomicBot/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/atomicbot.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/atomicbot

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/atomicbot.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/atomicbot

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/atomicbot.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/atomicbot


.. end-badges

An Atom / RSS bot that posts to Reddit.

* Free software: BSD license

Installation
============

::

    pip install atomicbot

Documentation
=============

https://AtomicBot.readthedocs.io/

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
