|Header|
========

.. |Header| raw:: html

        <h1 style="margin-top: 0; margin-bottom: 0;">
                <a href=".." style="text-decoration:none;">
                        <img style="vertical-align:middle" src="https://www.diffpy.org/_static/diffpy_logo_header.png" width="100">
                        <!--maybe use https://github.com/diffpy.png ?-->
                        <span>diffpy.utils</span>
                </a>
        </h1>
   
|PyPi| |Forge| |PythonVersion| |Tracking| |PR|

|Test| |CI| |Codecov| |Black| |DOI| 

.. |Black| image:: https://img.shields.io/badge/code_style-black-black
        :target: https://github.com/psf/black
   
.. |CI| image:: https://github.com/diffpy/diffpy.utils/actions/workflows/main.yml/badge.svg
        :target: https://github.com/diffpy/diffpy.utils/actions/workflows/main.yml

.. |Codecov| image:: https://codecov.io/gh/diffpy/diffpy.utils/branch/main/graph/badge.svg
        :target: https://codecov.io/gh/diffpy/diffpy.utils
   
.. |DOI| image:: https://img.shields.io/badge/TO_ADD_DOI-need_a_doi_%3F-red
        :target: https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content
   
.. |Forge| image:: https://img.shields.io/conda/vn/conda-forge/diffpy.utils
        :target: https://anaconda.org/conda-forge/diffpy.utils

.. |PR| image:: https://img.shields.io/badge/PR-Welcome-29ab47ff
        :target: https://github.com/diffpy/diffpy.utils/blob/main/CONTRIBUTING.rst

.. |PyPi| image:: https://img.shields.io/pypi/v/diffpy.utils
        :target: https://pypi.org/project/diffpy.utils/
   
.. |PythonVersion| image:: https://img.shields.io/pypi/pyversions/diffpy.utils
        :target: https://pypi.org/project/diffpy.utils/

.. |Test| image:: https://img.shields.io/badge/TO_ADD_TEST-need_a_test.yml_%3F-red
        :target: https://github.com/matplotlib/matplotlib/blob/main/.github/workflows/tests.yml

.. |Tracking| image:: https://img.shields.io/badge/issue_tracking-github-blue
        :target: https://github.com/diffpy/diffpy.utils/issues

Smaller shared functions for use by other diffpy packages.

* LONGER DESCRIPTION HERE

For more information about the diffpy.utils library, see the users manual at https://diffpy.github.io/diffpy.utils.

INSTALLATION
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
        pip install diffpy.utils

If you prefer to install from sources, after installing the dependencies, obtain the source archive from
`GitHub <https://github.com/diffpy/diffpy.utils/>`_. Once installed, ``cd`` into your ``diffpy.utils`` directory
and run the following ::

        pip install .

To check the installation integrity, if the following passes all checks, you are good! ::

        pip install -r https://raw.githubusercontent.com/diffpy/diffpy.utils/main/requirements/test.txt
        python -m diffpy.utils.tests.run

DEVELOPMENT
-----------

diffpy.utils is an open-source software... ADD MORE

Feel free to fork the project and contribute. To install diffpy.utils
in a development mode, with its sources being directly used by Python
rather than copied to a package directory, use the following in the root
directory ::

        pip install -e .

Note that... ANYTHING ELSE


CONTACTS
--------

For more information on diffpy.utils please visit the project web-page

* ADD LINK TO WEB-PAGE

or email Prof. Simon Billinge at sb2896@columbia.edu.
