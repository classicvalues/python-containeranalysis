Python Client for Container Analysis API
========================================

|ga| |pypi| |versions|

`Container Analysis API`_: An implementation of the Grafeas API, which stores, and enables querying
and retrieval of critical metadata about all of your software artifacts.

- `Client Library Documentation`_
- `Product Documentation`_

.. |ga| image:: https://img.shields.io/badge/support-GA-gold.svg
   :target: https://github.com/googleapis/google-cloud-python/blob/main/README.rst#general-availability
.. |pypi| image:: https://img.shields.io/pypi/v/google-cloud-containeranalysis.svg
   :target: https://pypi.org/project/google-cloud-containeranalysis/
.. |versions| image:: https://img.shields.io/pypi/pyversions/google-cloud-containeranalysis.svg
   :target: https://pypi.org/project/google-cloud-containeranalysis/
.. _Container Analysis API: https://cloud.google.com/container-registry/docs/container-analysis
.. _Client Library Documentation: https://cloud.google.com/python/docs/reference/containeranalysis/latest
.. _Product Documentation:  https://cloud.google.com/container-registry/docs/container-analysis

Quick Start
-----------

In order to use this library, you first need to go through the following steps:

1. `Select or create a Cloud Platform project.`_
2. `Enable billing for your project.`_
3. `Enable the Container Analysis API.`_
4. `Setup Authentication.`_

.. _Select or create a Cloud Platform project.: https://console.cloud.google.com/project
.. _Enable billing for your project.: https://cloud.google.com/billing/docs/how-to/modify-project#enable_billing_for_a_project
.. _Enable the Container Analysis API.:  https://cloud.google.com/container-registry/docs/container-analysis
.. _Setup Authentication.: https://googleapis.dev/python/google-api-core/latest/auth.html

Installation
~~~~~~~~~~~~

Install this library in a `virtualenv`_ using pip. `virtualenv`_ is a tool to
create isolated Python environments. The basic problem it addresses is one of
dependencies and versions, and indirectly permissions.

With `virtualenv`_, it's possible to install this library without needing system
install permissions, and without clashing with the installed system
dependencies.

.. _`virtualenv`: https://virtualenv.pypa.io/en/latest/


Supported Python Versions
^^^^^^^^^^^^^^^^^^^^^^^^^
Python >= 3.6

Deprecated Python Versions
^^^^^^^^^^^^^^^^^^^^^^^^^^
Python == 2.7.

The last version of this library compatible with Python 2.7 is google-cloud-containeranalysis==1.0.2.

Mac/Linux
^^^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    source <your-env>/bin/activate
    <your-env>/bin/pip install google-cloud-containeranalysis


Windows
^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    <your-env>\Scripts\activate
    <your-env>\Scripts\pip.exe install google-cloud-containeranalysis

Next Steps
~~~~~~~~~~

-  Read the `Client Library Documentation`_ for Container Analysis API
   API to see other available methods on the client.
-  Read the `Container Analysis API Product documentation`_ to learn
   more about the product and see How-to Guides.
-  View this `repository’s main README`_ to see the full list of Cloud
   APIs that we cover.

.. _Container Analysis API Product documentation:  https://cloud.google.com/container-registry/docs/container-analysis
.. _repository’s main README: https://github.com/googleapis/google-cloud-python/blob/main/README.rst
