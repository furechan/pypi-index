# Example Python Package Server

This is a GitHub pages site, that serves an example PyPi Server.

Based on https://github.com/ceddlyburge/python-package-server

Index located at https://furechan.github.io/pypi-index/

Direc reference
    pip install "simple-hatch @ git+https://github.com/furechan/simple-hatch"
    pip install "simple-hatch @ git+https://github.com/furechan/simple-hatch#egg=simple-hatch-0.0.0"

Using with pip
    pip install --extra-index-url https://furechan.github.io/pypi-index/ simple-hatch

Chech index
    curl https://furechan.github.io/pypi-index/simple-hatch
