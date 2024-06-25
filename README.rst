|Icon| `diffpy.utils <https://diffpy.github.io/diffpy.utils>`_
=========================================================

.. |Icon| image:: https://avatars.githubusercontent.com/diffpy
        :target: https://diffpy.github.io/diffpy.utils
        :height: 100px
   
|PyPi| |Forge| |PythonVersion| |PR|

|CI| |Codecov| |Black| |Tracking|

.. |Black| image:: https://img.shields.io/badge/code_style-black-black
        :target: https://github.com/psf/black
   
.. |CI| image:: https://github.com/diffpy/diffpy.utils/actions/workflows/main.yml/badge.svg
        :target: https://github.com/diffpy/diffpy.utils/actions/workflows/main.yml

.. |Codecov| image:: https://codecov.io/gh/diffpy/diffpy.utils/branch/main/graph/badge.svg
        :target: https://codecov.io/gh/diffpy/diffpy.utils
   
.. |Forge| image:: https://img.shields.io/conda/vn/conda-forge/diffpy.utils
        :target: https://anaconda.org/conda-forge/diffpy.utils

.. |PR| image:: https://img.shields.io/badge/PR-Welcome-29ab47ff
        :target: https://github.com/diffpy/diffpy.utils/blob/main/CONTRIBUTING.rst

.. |PyPi| image:: https://img.shields.io/pypi/v/diffpy.utils
        :target: https://pypi.org/project/diffpy.utils/
   
.. |PythonVersion| image:: https://img.shields.io/pypi/pyversions/diffpy.utils
        :target: https://pypi.org/project/diffpy.utils/

.. |Tracking| image:: https://img.shields.io/badge/issue_tracking-github-blue
        :target: https://github.com/diffpy/diffpy.utils/issues

Smaller shared functions for use by other diffpy packages.

* LONGER DESCRIPTION HERE

For more information about the diffpy.utils library, see the `users manual <https://diffpy.github.io/diffpy.utils>`_.

Installation
------------

The preferred method is to use `Miniconda Python
<https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html>`_
and install from the "conda-forge" channel of Conda packages.

To add "conda-forge" to the conda channels, run the following in a terminal. ::

        conda config --add channels conda-forge

We want to install our packages in a suitable conda environment.
The following creates and activates a new environment named ``diffpy.utils`` ::

        conda create -n diffpy.utils python=3
        conda activate diffpy.utils

Then, to fully install ``diffpy.utils`` in our active environment, run ::

        conda install diffpy.utils

Another option is to use ``pip`` to download and install the latest release from
`Python Package Index <https://pypi.python.org>`_.
To install using ``pip`` into your ``diffpy.utils`` environment, we will also have to install dependencies ::

        pip install -r https://raw.githubusercontent.com/diffpy/diffpy.utils/main/requirements/run.txt

and then install the package ::

        pip install diffpy.utils

If you prefer to install from sources, after installing the dependencies, obtain the source archive from
`GitHub <https://github.com/diffpy/diffpy.utils/>`_. Once installed, ``cd`` into your ``diffpy.utils`` directory
and run the following ::

        pip install .

Support and Contribute
----------------------

`Diffpy user group <https://groups.google.com/g/diffpy-users>`_ is the discussion forum for general questions and discussions about the use of diffpy.utils. You can join the diffpy.utils users community by joining the Google group. The diffpy.utils project welcomes your expertise and enthusiasm!

If you see a bug or want to request a feature, please `report it as an issue <https://github.com/diffpy/diffpy.utils/issues>`_ and/or `submit a fix as a PR <https://github.com/diffpy/diffpy.utils/pulls>`_. You can also post it to the `Diffpy user group <https://groups.google.com/g/diffpy-users>`_. 

Feel free to fork the project and contribute. To install diffpy.utils
in a development mode, with its sources being directly used by Python
rather than copied to a package directory, use the following in the root
directory ::

        pip install -e .

Improvements and fixes are always appreciated.

To learn more about how to successfully get involved and contributing to diffpy.utils, please see our `Contributing guide <https://github.com/diffpy/diffpy.utils/blob/main/CONTRIBUTING.rst>`_ and `Code of Conduct <https://github.com/diffpy/diffpy.utils/blob/main/CODE_OF_CONDUCT.rst>`_.

Contact and Citation
--------------------

For more information on diffpy.utils please visit the project `web-page <https://diffpy.github.io/>`_ or email Prof. Simon Billinge at sb2896@columbia.edu.

If you use diffpy.utils in a scientific publication, we would appreciate `citations <LINK HERE>`_.  

.. ADD LINK IN <LINK HERE> and delete [ADD LINK]
