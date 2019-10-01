=======================================
Python Guide for Practicing Wizards
=======================================

########################
Documentation
########################

https://shawnjburke.github.io/py_guide/

The docs are hosted with gitHub Pages, with html in the docs/ folder, powered by reStructured text markup in the
data-source folder.  You can get to the root at `py_quide`.

##########################
Purpose of this Project
##########################

This project implements a Python Project generator.  It's aim is to create a standard framework for Python
projects that includes best practices.  The results should be code that is documented, has an installation
and versioning paradigm in place, and makes it easier for a programmer to do things that are often tedious.

Best practice steps are organized as follows:

* Step 1 - `Install Python`_
* Step 2 - `Install PyCharm`_
* Step 3 - `Python Project Structure`_
* Step 4 - `Documentation Matters`_
* Step 5 - `setup.py`_ for success early in your project

..  _Install Python: `py_guide/python_best_practices/install_python.html
..  _Install Pycharm: `py_guide/python_best_practices/install_Pycharm.html
..  _Python Project Structure: `py_guide/python_best_practices/project_structure.html
..  _Documentation Matters: `py_guide/python_best_practices/project_documentation_matters.html
..  _setup.py: `py_guide/python_best_practices/project_setup.html

############################
Installation
############################

At this time you can't install this module.  At a later version the installation will provide an interface to create
the recommended project structure, documented here.

..  code-block:: Python

    >>> venv/scripts/pip install sjb.pyguide

########################
Version History
########################

* 0.2.5 - Fix missing installation requirements in setup.py such as missing package_data items. Console invoked generator appears functional.

* 0.2.4 - Fix issues with generated project, wheel installation file, not working.  Add several files missing from generated project.

* 0.2.3 - Beta version of project generator.  Creates a Python 3.x project with best practices, including initialized virtual environment.

* 0.2.2 - Adding in incomplete changes for project generator on way to v0.3.0.  Will create directory structure and 1/2 dozen files for the project.  Not complete yet.

* 0.2.1 - Remove revealjs theme which is no longer supported and didn't work right anyway.

* 0.2.0 - Updated a number of package requirements such as sphinx themes to meet compatibility requirements.

* 0.1.0 - First version with semantic versioning schema.  Most of documentation is strong.  Console script to create a project is in an development state.

