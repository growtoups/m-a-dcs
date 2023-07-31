Usage
=====

.. _keyauth:

Key Authentication
------------

 To access the protected routes, you need to include the API key in the request headers. The API key should be included in the "Authorization" header as follows:
 
A cool bit of code::

{ "Authorization": "Bearer YOUR_API_KEY" }

.. code-block:: rst

   A bit of **rst** which should be *highlighted* properly.
Replace **YOUR_API_KEY** with the API key you obtained during registration or login.

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

