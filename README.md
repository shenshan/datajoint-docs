# DataJoint Technical Reference
This repository contains the source for comprehensive technical reference documentation for the DataJoint framework. 

All DataJoint documentations are presented at [DataJoint documentation website](http://docs.datajoint.io/).
Documentations are generated using [Sphinx](http://www.sphinx-doc.org/en/stable/) with custom rendering theme 
largely based on the [Read The Doc theme](https://github.com/rtfd/sphinx_rtd_theme).

# License
The documentation can be distributed for free use under the [Creative Commons Attribution-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-sa/4.0/).  Any copy or derivation of the documentation must include attribution to "DataJoint contributors" and include the URL reference https://docs.datajoint.io


# Building locally
- Fork and clone the repository to your local machine.
- Install requirements using `pip3 install -r requirements.txt`
- Build the website by running `make site`. This will build and generate the static website in the `_build/html` directory.
- Some structural changes might require you to first clean the output directory by running `make clean` before generating the doc with `make html`.
