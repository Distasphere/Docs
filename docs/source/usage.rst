Using Flexy-payments
====================

This section explains how to use **Flexy-payments** to send, receive, and manage payments across different integrated channels.

1. Logging into the Platform
----------------------------

---

2. Making a Payment
-------------------

From a User Account
~~~~~~~~~~~~~~~~~~~

Example API Call
~~~~~~~~~~~~~~~~

.. code-block:: bash

   POST /api/v1/payments
   Content-Type: application/json

   {
     "amount": 15000,
     "currency": "XOF",
     "recipient": "+227 XY zz zz zz"
   }
