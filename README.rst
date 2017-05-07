Butla's Python app Cookiecutter
===============================

Cookiecutter_ template for a Python sample application with full test coverage
and Pylint quality control.

Features
--------

* Testing setup with `pytest`_ and `Tox`_.
* Tests separated into unit, integrated and functional categories.
* Expecting full test coverage.
* Tox setup expecting to `measure coverage in out-of-process functional tests`.
* Enforcing code quality with `Pylint`_.

Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet::

    pip3 install --user cookiecutter

Generate the project from template::

    cookiecutter gh:butla/cookiecutter-pyapp-butla

Then:

* run ``tox``
* update ``requirements-test.txt`` with frozen dependencies of coverage, pylint, and pytest.

Credits
-------

This template was based on `audreyr/cookiecutter-pypackage`_ project template.

.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _measure coverage in out-of-process functional tests: http://coverage.readthedocs.io/en/coverage-4.3.4/subprocess.html
.. _pytest: https://docs.pytest.org/en/latest/
.. _Pylint: https://www.pylint.org/
.. _Tox: http://testrun.org/tox/

