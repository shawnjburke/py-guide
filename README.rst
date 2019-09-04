=======================================
Python Guide for Practicing Wizards
=======================================

########################
Documentation
########################

https://shawnjburke.github.io/py_guide/

########################
Version History
########################

* 0.2.2 - Adding in incomplete changes for project generator on way to v0.3.0.  Will create directory
    structure and 1/2 dozen files for the project.  Not complete yet.

* 0.2.1 - Remove revealjs theme which is no longer supported and didn't work right anyway.

* 0.2.0 - Updated a number of package requirements such as sphinx themes to meet compatibility requirements.

* 0.1.0 - First version with semantic versioning schema.  Most of documentation is strong.  Console script to
    create a project is in an development state.

##########################
Purpose of this Project
##########################

This project is intended to be a guide on getting started with Python.  It's intended to establish a best
practice structure that can be used as a beginning state for a python project.  Stepping through all the steps
should yield a new Python project, using a set of best practices and coding standards, which can apply across all
types of Python projects.

The docs are hosted with gitHub Pages, with html in the docs/ folder, powered by reStructured text markup in the
data-source folder.  You can get to the root at `py_quide`.

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

************************************
What we have tried to think through
************************************

Project Structure - as an old programmer having a standard way to do any coding language, is just something I find
 efficient.  In addition to thinking like a developer I've worked in release management, IT, being the boss, and I
 tend to approach things in a wholistic fashion.  It doesn't matter how cool your code is if you can't install and
 maintain it.

Documentation is important - if I have a structure that is already setup for how to document, leveraging in line code
syntax, then developers are more likely to make use of it.  This is good, because documentation is not for you, but
for the coder left maintaining your app, when you've moved on to your new fancy job (because of this awesome app you
just made).

Documentation themes - while creating parts of the project on Sphinx, I wanted to compare the themes.  I couldn't find
one resource for that.  Therefore I created it here in this project.  You can see the same documentation generated
into several different themes.

Releasing - I have found releasing is an after thought.  This often results in things like finding out your project
structure isn't conducive to packaging your release.  Or thinking through where you store your version number as it's
used in several files (normally).

GitHub friendly - we did thins like make docs the html directory of information for compatibility with GitHub.  It is so widely
used that while Sphinx normally makes docs a source directory, it's configuration allowed for change, where GitHub
(circa 2018-2019) would not.

Test Inspired Development - I came from the TDD days and I liked it.  When you have a reusable set of tests you get
build stability, reliability, the ability to come back to your own code and not break it, the ability for other people
to work on your code (so you can go write something newer and cooler).

############################
Installation
############################

At this time you can't install this module.  At a later version the installation will provide an interface to create
the recommended project structure, documented here.

..  code-block:: Python

    >>> some_future_time --todo=create_installer

##################################################
What makes this different from other frameworks?
##################################################

It's my opinion.
It's not a framework.  It hopes to generate a template project to make being "standard" better.
It attempts to not be specific to a type of project.  Web projects or console apps can benefit from this.
There is no team behind this.  Just me.
