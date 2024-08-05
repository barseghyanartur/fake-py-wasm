============
fake-py-wasm
============
.. _fake.py: https://github.com/barseghyanartur/fake.py
.. _online-demo: https://fake-py-wasm.vercel.app/
.. _Pyodide: https://pyodide.org/en/stable/

`Pyodide`_ based WASM frontend for `fake.py`_ Python package. Check the `online-demo`_.

Running locally
===============
Open the index.html file in your favourite browser.

Usage examples
==============

.. code-block:: python

    from fake import FAKER

    name = FAKER.name()
    email = FAKER.email()
    country = FAKER.country()
    sentence = FAKER.sentence()
    png = FAKER.png()

    print(name)
    print(email)
    print(country)
    print(sentence)
    print(png)

Writing documentation
=====================

Keep the following hierarchy.

.. code-block:: text

    =====
    title
    =====

    header
    ======

    sub-header
    ----------

    sub-sub-header
    ~~~~~~~~~~~~~~

    sub-sub-sub-header
    ^^^^^^^^^^^^^^^^^^

    sub-sub-sub-sub-header
    ++++++++++++++++++++++

    sub-sub-sub-sub-sub-header
    **************************

License
=======
MIT

Support
=======
For security issues contact me at the e-mail given in the `Author`_ section.

For overall issues, go to `GitHub <https://github.com/barseghyanartur/fake-py-wasm/issues>`_.

Author
======
Artur Barseghyan <artur.barseghyan@gmail.com>
