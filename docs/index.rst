.. TransBlock documentation master file, created by
   sphinx-quickstart on Sat Dec 19 15:46:33 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to TransBlock's documentation!
======================================

===============
Getting Started
===============


===========
Constructor
===========

To create a TransBlock Instance, use the new BlockGenerator() function

>> const blockInstance = new BlockGenerator();

==========
Properties
==========

.. list-table:: Options
   :widths: 20 10 20 50
   :header-rows: 1

   * - Property
     - Default
     - Type
     - Description
   * - block
     - 'div'
     - DOM element
     - The container for the entire block.
   * - itemList
     - 'div'
     - DOM element
     - The list containing all elements inside the collection.
   * - buttonPrevious
     - 'i'
     - DOM element
     - The button that can be clicked to move back to the previous element in the collection.
   * - buttonNext
     - 'i'
     - DOM element
     - The button that can be clicked to move back to the next element in the collection.
   * - width
     - 800
     - integer
     - The width of the block container
   * - height
     - 500
     - integer
     - The height of the block container
   * - timing
     - 4
     - integer
     - The display time for each element in the collection when the itemList is being iterated.
   * - counter
     - \
     - integer
     - The index of the current element that is on display
   * - elements
     - []
     - Array
     - The list of elements add to the container
   * - hovered_flag
     - false
     - boolean
     - The status whether the block object is being hovered over.

=======
Methods
=======

.. automodule:: blockInstance
  :members:


.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
