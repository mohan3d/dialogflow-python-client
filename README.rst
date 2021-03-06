api.ai: Python SDK for `API.AI <http://api.ai>`_
================================================

.. image:: https://badge.fury.io/py/apiai.svg
    :target: http://badge.fury.io/py/apiai

.. image:: https://travis-ci.org/dialogflow/dialogflow-python-client.svg
    :target: https://travis-ci.org/dialogflow/dialogflow-python-client


Overview
--------

The API.AI Python SDK makes it easy to integrate speech recognition with API.AI natural language processing API. API.AI allows using voice commands and integration with dialog scenarios defined for a particular agent in API.AI.

Prerequsites
------------

Create an `API.AI account <http://api.ai>`_.


Running examples
----------------

1. Find examples from 'examples' path.
2. Insert API key.

.. code-block:: python

    >>> CLIENT_ACCESS_TOKEN = '<YOUR_CLIENT_ACCESS_TOKEN>'
    ...

Features
--------

- Speech Recognition.
- Voice Activity Detection.
- Natural Language Processing.

Installation
------------

To install apiai, simply:

.. code-block:: bash

    $ pip install apiai

or install it from repo:

.. code-block:: bash

    $ pip install git+https://github.com/dialogflow/dialogflow-python-client.git

You might run into problems because some dependencies in your python environment are missing. You need to install numpy (which is available in almost all package managers). For running the examples you also need python audio.

In ubuntu the following will do the job:

.. code-block:: bash

    $ apt-get install python-pyaudio python-numpy
    $ pip install apiai

Documentation
-------------

Documentation is available at http://api.ai.

## How to make contributions?
Please read and follow the steps in the `CONTRIBUTING <https://github.com/dialogflow/dialogflow-python-client/blob/master/CONTRIBUTING.md>`_.

## License
See `LICENSE <https://github.com/dialogflow/dialogflow-python-client/blob/master/LICENSE>`_.

## Terms
Your use of this sample is subject to, and by using or downloading the sample files you agree to comply with, the `Google APIs Terms of Service <https://developers.google.com/terms/>`_.

This is not an official Google product.