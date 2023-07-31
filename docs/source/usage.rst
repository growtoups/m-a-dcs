Usage
=====

.. _keyauth:

Key Authentication
------------

 To access the protected routes, you need to include the API key in the request headers. The API key should be included in the "Authorization" header as follows:

{ "Authorization": "Bearer YOUR_API_KEY" }

Replace **YOUR_API_KEY** with the API key you obtained during registration or login.

.. _register
Registration
----------------

To register a new account, send a POST request to the following endpoint:

api.mycelium-ai.com/api/me/register
{
  "username": "your_username",
  "password": "your_password"
}
    

Upon successful registration, you will receive an API key in the response. Please note that there is a monthly quota limit of 25,000 requests. If you require a higher quota, please contact us to discuss the options.

.. _login
Login
----------------

To login to your account and obtain the API key, send a POST request to the following endpoint:

api.mycelium-ai.com/api/me/login
{
  "username": "your_username",
  "password": "your_password"
}
    

