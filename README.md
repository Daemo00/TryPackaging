Experiments with Python packages.

Based on https://packaging.python.org/en/latest/tutorials/packaging-projects/.

The distributed package is [packaging_tutorial](packaging_tutorial).

[build-requirements.txt](build-requirements.txt) is for creating the virtual environment used to build and upload the package,
it is used byt the GitHub action that builds and publishes the package.

[requirements.txt](requirements.txt) is for creating the virtual environment used to try the uploaded package.

Any commit here starting with `[REL]` creates a release of the package.
