.. image:: https://travis-ci.org/shuup/shuup-stripe.svg?branch=master
    :target: https://travis-ci.org/shuup/shuup-stripe
.. image::
   https://codecov.io/gh/shuup/shuup-stripe/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/shuup/shuup-stripe
.. image::
   https://img.shields.io/pypi/v/shuup-stripe.svg
   :alt: PyPI
   :target: https://pypi.org/project/shuup-stripe/

Shuup Stripe Addon
==================

This package implements `Stripe Checkout <https://stripe.com/checkout>`__
for the `Shuup <https://shuup.com/>`__ platform.

Copyright
---------

Copyright (C) 2012-2019 by Shoop Commerce Ltd. <support@shuup.com>

Shuup is International Registered Trademark & Property of Shoop Commerce Ltd.,
Business ID: FI27184225,
Business Address: Iso-Roobertinkatu 20-22, 00120 HELSINKI, Finland.

License
-------

Shuup Stripe addon is published under Open Software License version 3.0 (OSL-3.0).
See the LICENSE file distributed with Shuup.

Running tests
-------------

You can run tests with `py.test <http://pytest.org/>`_.

Requirements for running tests:

* Your virtualenv needs to have Shuup installed.

* Project root must be in the Python path.  This can be done with:

  .. code:: sh

     pip install -e .

* The packages from ``requirements-test.txt`` must be installed.

  .. code:: sh

     pip install -r requirements-test.txt

To run tests, use command:

.. code:: sh

   py.test -v
