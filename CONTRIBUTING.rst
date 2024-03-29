.. highlight:: shell

============
Contributing
============

Contributions are welcome, and they are greatly appreciated! Every little bit
helps, and credit will always be given.

You can contribute in many ways:

Types of Contributions
----------------------

Report Bugs
~~~~~~~~~~~

Report bugs at https://github.com/tch521/python-TAMER/issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

Fix Bugs
~~~~~~~~

Look through the Github issues for bugs. Anything tagged with "bug" and "help
wanted" is open to whoever wants to implement it.

Implement Features
~~~~~~~~~~~~~~~~~~

Look through the Github issues for features. Anything tagged with "enhancement"
and "help wanted" is open to whoever wants to implement it.

Write Documentation
~~~~~~~~~~~~~~~~~~~

We could always use more documentation, whether as part of the
official docs, in docstrings, or even on the web in blog posts,
articles, and such.

Submit Feedback
~~~~~~~~~~~~~~~

The best way to send feedback is to file an issue at https://github.com/tch521/python-TAMER/issues.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Remember that this is a volunteer-driven project, and that contributions
  are welcome :)

Get Started!
------------

**NOTE**: the details below come from a template and are not valid at this early stage of development.

Ready to contribute? Here's how to set up `python_tamer` for local development.

1. Clone `python_tamer` repo from Github.

    $ git clone https://github.com/tch521/python-TAMER.git

2. Install dependencies into a virtualenv. Assuming you have pipenv installed, this is how you set up your fork for local development::

    $ cd python_tamer
    $ pipenv install --dev
    $ pipenv shell

3. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature

   Now you can make your changes locally.

4. When you're done making changes, check that your changes pass pylint and the
   tests, including testing other Python versions with tox::

    $ pylint python_tamer
    $ pytest
    $ tox

5. Commit your changes and push your branch to Github::

    $ git add <files to add>
    $ git commit -m "Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature

6. Submit a merge request through the Github website.

Merge Request Guidelines
------------------------

Before you submit a merge request, check that it meets these guidelines:

1. The merge request should include tests.
2. If the merge request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in README.rst.
3. The merge request should work for Python 3.7 (or greater). Check
   https://github.com/tch521/python-TAMER
   and make sure that the tests pass for all supported Python versions.
