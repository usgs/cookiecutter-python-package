Contributing
============

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

You can contribute in many ways:

Types of Contributions
----------------------

Report Bugs
~~~~~~~~~~~

Report bugs to Jeremiah Lant at jlant@usgs.gov or on the issues page of
the respective online repository where cookiecutter-python-package is hosted.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

Fix Bugs
~~~~~~~~

Look through the issues page of the respective online repository where cookiecutter-python-package is hosted for bugs.
Anything tagged with "bug" is open to whoever wants to implement it.

Implement Features
~~~~~~~~~~~~~~~~~~

Look through the issues page of the respective online repository where cookiecutter-python-package is hosted for features.
Anything tagged with "feature" is open to whoever wants to implement it.

Write Documentation
~~~~~~~~~~~~~~~~~~~

cookiecutter-python-package could always use more documentation, whether as part of the
official cookiecutter-python-package docs or in docstrings.

Submit Feedback
~~~~~~~~~~~~~~~

The best way to send feedback is to file an issue at jlant@usgs.gov or on the issues page of
the respective online repository where cookiecutter-python-package is hosted.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Remember that this is a volunteer-driven project, and that contributions
  are welcome :)

Get Started!
------------

Ready to contribute? Here's how to set up `cookiecutter-python-package` for local development.

1. Fork the `cookiecutter-python-package` repo.
2. Clone your fork locally::

    $ git clone <remote url to your forked version of cookiecutter-python-package>

3. Install your local copy into a virtual environment using virtualenv_ or conda_.
If you have virtualenvwrapper_ installed, this is how you set up your fork for local development::

    $ mkvirtualenv cookiecutter-python-package
    $ cd cookiecutter-python-package/
    $ python setup.py develop

If you have conda_ installed, this is how you set up your fork for local development on Linux or Mac OS X::

    $ conda create --name cookiecutter-python-package
    $ source activate cookiecutter-python-package
    $ cd <your-path-to-cookiecutter-python-package-project/
    $ python setup.py develop

If you have conda_ installed, this is how you set up your fork for local development on Windows::

    > conda create --name cookiecutter-python-package
    > activate cookiecutter-python-package
    > cd <your-path-to-cookiecutter-python-package-project/
    > python setup.py develop

4. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature

   Now you can make your changes locally.

5. When you're done making changes, check that your changes pass flake8_ and the tests, including testing other Python versions with tox_::

    $ flake8 cookiecutter-python-package tests
    $ py.test
    $ tox

   To get flake8 and tox, just pip install them into your virtualenv.

6. Commit your changes and push your branch to the respective online repository where cookiecutter-python-package is hosted::

    $ git add .
    $ git commit -m "Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature

7. Submit a pull request through the respective online repository website where cookiecutter-python-package is hosted.

Pull Request Guidelines
-----------------------

Before you submit a pull request, check that it meets these guidelines:

1. The pull request should include tests.
2. If the pull request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in README.rst.
3. The pull request should work for Python 2.6, 2.7, 3.3, and 3.4.

Tips
----

To run a subset of tests::

    $ py.test tests/test_<your-awesome-module>.py


.. _virtualenv: https://virtualenv.pypa.io/en/latest/
.. _conda: http://conda.pydata.org/
.. _virtualenvwrapper: http://virtualenvwrapper.readthedocs.io/en/latest/
.. _flake8: https://flake8.readthedocs.io/en/latest/
.. _tox: http://tox.readthedocs.io/en/latest/
