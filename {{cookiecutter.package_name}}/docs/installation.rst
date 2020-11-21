
Installation
============

Installation from PyPI
----------------------

``{{cookiecutter.package_name}}`` can be installed normally from the Python Package Index.
Note that you will need write access to your python packages folder. This
means you will have to install as root or with sudo on most linux distributions,
unless you are installing to a virtual environment you can write to.

.. code-block:: console

    $ pip install {{cookiecutter.package_name}}


Installation from Sources
-------------------------

The sources can be downloaded from the project's
`github releases <https://github.com/tendril-framework/{{cookiecutter.package_name}}/releases>`_.
While this is the least convenient method of installation, it does have the
advantage of making the least assumptions about your environment.

You will have to ensure the following dependencies are installed and available
in your python environment by whatever means you usually use.

    - {dependencies}
    
``sudo`` may be necessary if you are not installing into a virtual environment.


.. code-block:: console

    $ python setup.py install


Installation for Development
----------------------------

Installation from the repository is the most convenient installation method
if you intend to modify the code, either for your own use or to contribute to
``{{cookiecutter.package_name}}``. ``sudo`` may be necessary if you are not installing
into a virtual environment.

.. code-block:: console

    $ git clone https://github.com/tendril-framework/{{cookiecutter.package_name}}.git
    $ cd {{cookiecutter.package_name}}
    $ pip install -e .

