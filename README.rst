threadless-corpus
==========

This is a collection of images I scraped from the `Threadless T-shirt
web site`_ to use in benchmarking object recognition algorithms and
implementations.

The ``pattern`` directory contains training images while ``worn``
contains test images.  Corresponding training and test images have the
same name, e.g. ``1016.jpg``.

There are 951 test/training image pairs in this corpus.


Sample Images
-------------

==================================================================================  ===============================================================================
Training Image                                                                      Test Image
==================================================================================  ===============================================================================
.. image:: http://github.com/wiseman/threadless-corpus/raw/master/pattern/1016.jpg  .. image:: http://github.com/wiseman/threadless-corpus/raw/master/worn/1016.jpg

.. image:: http://github.com/wiseman/threadless-corpus/raw/master/pattern/1055.jpg  .. image:: http://github.com/wiseman/threadless-corpus/raw/master/worn/1055.jpg

.. image:: http://github.com/wiseman/threadless-corpus/raw/master/pattern/399.jpg   .. image:: http://github.com/wiseman/threadless-corpus/raw/master/worn/399.jpg

.. image:: http://github.com/wiseman/threadless-corpus/raw/master/pattern/458.jpg   .. image:: http://github.com/wiseman/threadless-corpus/raw/master/worn/458.jpg

.. image:: http://github.com/wiseman/threadless-corpus/raw/master/pattern/657.jpg   .. image:: http://github.com/wiseman/threadless-corpus/raw/master/worn/657.jpg
==================================================================================  ===============================================================================


Example Match
-------------

Here's an example of finding matching features in two images using `Rob Hess' SIFT code`_:

.. image:: http://github.com/wiseman/threadless-corpus/raw/master/sample-match-904.jpg


.. _Threadless T-shirt web site: http://threadless.com/
.. _Rob Hess' SIFT code: http://web.engr.oregonstate.edu/~hess/
