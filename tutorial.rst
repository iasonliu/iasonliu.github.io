reStructuredText
----------------

SubSection 2.1
==============

SubSection 2.1.1
++++++++++++++++

------------------
Subsection 1.1.1.1
------------------

Links
=====
`Python Docs <https://docs.python.org>`_

.. _Python Docs Links: https://python.org
`Python Docs Links`_

Text Emphasis
=============
*italics*
**bold**
``code``

Literal or Code Blocks
======================
::

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. In viverra convallis
    feugiat. Mauris facilisis dolor placerat massa porta vehicula. Vivamus quis
    posuere quam. Sed semper, libero vel tristique tincidunt, metus diam
    pellentesque dolor, congue dignissim nibh ipsum sed dui.

This text will be formatted as usual, meanwhile::

   This passage will become literal block. Lorem ipsum dolor sit amet,
   consectetur adipiscing elit. In viverra convallis
   feugiat. Mauris facilisis dolor placerat massa porta vehicula. Vivamus quis
   posuere quam. Sed semper, libero vel tristique tincidunt, metus diam
   pellentesque dolor, congue dignissim nibh ipsum sed dui.

.. code:: python

   from datetime import datetime
   print(datetime.now())

Lists
=====
* Bullet list item 1
* Bullet list item 2
	If the list item text is too long, it can go to the next line, like this

1. Numbered list item 1
2. Numbered list item 2

	1. Nested list item 2
	2. Nested list item 2

#. Autonumbered list item
#. Autonumbered list item

Documentation Comments
======================

.. This line will not be redered.

..
	You can have mutilline comments, by adding indented text blocks.
	This line will not be rendered.

	This is still a comment.

Admonition
==========

.. note::
	Careful! Don't go overtime!!

.. attention::
	Attention!!!

.. danger::
    This step is dangerous! Be real sure about it!

.. tip::
	https://docutils.sourceforge.io/docs/ref/rst/directives.html#specific-admonitions

Tables
======

Simple Table
++++++++++++
========  ========  ========
Column A  Column B  Column C
========  ========  ========
row 1A    row 1B    row 1C
row 2A    row 2B    row 2C
========  ========  ========

Grid table
++++++++++

+----------+----------+----------+
| Column A | Column B | Column C |
+==========+==========+==========+
| row 1A   | row 1B   | row 1C   |
+----------+----------+----------+
| row 2A   | row 2B   | row 2C   |
+----------+----------+----------+

CSV table
+++++++++

.. csv-table::
   :header: "Column A", "Column B", "Column C"

   "row 1A", "row 1B", "row 1C"
   "row 2A", "row 2B", "row 2C"


Table of Contents
=================

.. contents::

Rendering Image
===============
.. image:: path_to_image.jpg
