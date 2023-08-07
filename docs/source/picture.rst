Random Pictures
=====

.. _ducks:

------------

Random Duck Picture Route
=====================================================

Overview
--------

The Random Duck Picture route in Mycelium-API allows you to infuse your applications with a touch of quirkiness by effortlessly fetching random duck pictures. Whether you're looking to add a playful element to your interface or simply want to share the charm of ducks, this route is your gateway to delightful content.

How to Use
----------

To seamlessly integrate the appeal of duck pictures into your application, follow these steps:

1. Send a GET request to the following endpoint:

   .. code-block:: http

      GET /api/pictures/duck

2. The API will respond with a random duck picture's URL, ready to be showcased in your app.

No authorization is required for this route, making it an accessible choice for enhancing your app's visual appeal.

Example
-------

Enhance your application's visual appeal with a whimsical duck picture:

**Request:**

.. code-block:: http

   GET /api/pictures/duck

**Response:**

The API will provide you with the URL of a delightful and random duck picture.

.. code-block:: json

   {
     "url": "https://example.com/random-duck-image.jpg"
   }

Embrace the Quack-tastic Charm!
-------------------------------

Unleash the charm of ducks into your application's experience with the Random Duck Picture route. Whether you're aiming to engage users through delightful visuals or infuse a sense of lightheartedness, this route is your companion to quack-tastic content.
