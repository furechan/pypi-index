# Static Pypi Server Example

This is a GitHub pages site, that serves as a static PyPi index.

Based on https://github.com/ceddlyburge/python-package-server

Index located at https://furechan.github.io/pypi-index/

The index contains a reference to a single package
- simple-hatch https://github.com/furechan/simple-hatch

## Install via direct reference

    pip install "simple-hatch @ git+https://github.com/furechan/simple-hatch#egg=simple-hatch-0.0.0"

## Install using index

    pip install --extra-index-url https://furechan.github.io/pypi-index/ simple-hatch

## Check index

    curl https://furechan.github.io/pypi-index/simple-hatch/


## Links
- https://packaging.python.org/en/latest/specifications/simple-repository-api/
- https://peps.python.org/pep-0503/#normalized-names


# Related projects and Resources
- https://github.com/ceddlyburge/python-package-server
- https://github.com/astariul/github-hosted-pypi
- https://www.bomberbot.com/python/leveraging-github-as-a-pypi-server-an-in-depth-guide/

