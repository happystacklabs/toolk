<img src="github/logo@2x.png" alt="Toolk Logo" width="149" height="93" />

Toolk
============
![Version](https://img.shields.io/badge/Version-0.0.0-green.svg?style=flat)
![license](https://img.shields.io/github/license/mashape/apistatus.svg)

`Toolk` is a toolkit for iOS to automate tedious tasks like generating boilerplate for Swift projects in Xcode.

## Installation

## Documentation

## Tests and release
If you've cloned this project, and want to install the library (*and all
development dependencies*), the command you'll want to run is::

    $ pip install -e .[test]

If you'd like to run all tests for this project, you would run the following command::

    $ python setup.py test

This will trigger `py.test <http://pytest.org/latest/>`_, along with its popular
`coverage <https://pypi.python.org/pypi/pytest-cov>`_ plugin.

Lastly, if you'd like to cut a new release of this CLI tool, and publish it to
the Python Package Index (`PyPI <https://pypi.python.org/pypi>`_), you can do so
by running::

    $ python3 setup.py sdist

This will build both a source tarball of your CLI tool, as well as a newer wheel
build (*and this will, by default, run on all platforms*).

The ``twine upload dist/*`` command (which requires you to install the `twine
<https://pypi.python.org/pypi/twine>`_ tool) will then securely upload your
new package to PyPI so everyone in the world can use it!
