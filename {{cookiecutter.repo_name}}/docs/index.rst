{{ cookiecutter.project_name }} documentation
=====================================================

Welcome in the ``{{ cookiecutter.project_name }}`` documentation.

API documentation
-----------------
.. toctree::
    :maxdepth: 2

    api/modules


Installation
------------
Module is hosted at `PYPI <https://pypi.python.org/pypi/rbottle>`_,
and can be easily installed using
`PIP <http://en.wikipedia.org/wiki/Pip_%28package_manager%29>`_:

::

    sudo pip install {{cookiecutter.repo_name}}

Testing
-------
This project uses `pytest <http://pytest.org>`_ for testing. You can run
the tests from the root of the package using following command::

    $ py.test tests/


Source code
-----------
This project is released as opensource (GPL) and source codes can be found at
GitHub:

- https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
