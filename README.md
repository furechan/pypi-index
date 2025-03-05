# Static Pypi Server Example

This is a GitHub pages site, that serves a static PyPi index.

Based on https://github.com/ceddlyburge/python-package-server

Index located at https://furechan.github.io/pypi-index/

The index contains a reference to a single package
- https://github.com/furechan/simple-hatch

Install via direct reference

    pip install "simple-hatch @ git+https://github.com/furechan/simple-hatch#egg=simple-hatch-0.0.0"

Install using index

    pip install --extra-index-url https://furechan.github.io/pypi-index/ simple-hatch

Check index

    curl https://furechan.github.io/pypi-index/simple-hatch
