

.. _template:

Header 1
=================================

Paragraphs contain text and may contain inline markup: *emphasis*, **strong emphasis**, `interpreted text`, ``inline literals``, 

standalone hyperlinks (http://www.python.org), internal hyperlink `Phyton <http://www.python.org>`_,footnote and citation references ([1]_).


Header 2
------------

Header 3
```````````````
Bullet lists

- This is a bullet list. |copy|

- Bullets can be "*", "+", or "-".

	- this a nested bullet list

	- this a nested bullet list


Enumerated lists

1. This is an enumerated list.

2. Enumerators may be arabic numbers, letters, or roman
   numerals.

.. _tables:

Tablestyle
----------

.. _L1_Tab1:
.. table:: Titolo della prima tabella

   ====================  ==========  ==========
   Header row, column 1  Header 2    Header 3
   ====================  ==========  ==========
   body row 1, column 1  column 2    column 3
   body row 2            Cells may span columns
   ====================  ======================

.. table:: Titolo della seconda tabella

   ============  ===============
   Participants  Time of arrival
   ============  ===============
   John          7:00 pm
   Jack          7:30 pm
   ============  ===============


:numref:`L1_Tab1`

Figures
-----------------

Figure are created using the following code. 
A figure points to a filename and has a caption. 
Optionally, you can add a label and set the width, alignment and other common figure properties. You can make references to a figure using its label as follows: 

.. _L1_Fig1:
.. figure:: /Figure/L1_Fig1.png
   
   Figure must be at least 72 DPI. Original figure must be saved in a dedicated folder to be passed to Sphinx. Rule for for naming figures LectureCode_FigureNumber.png
   
   

bla bla bla :numref:`L1_Fig1`.


Math
-----------------

.. math::
	:label: eq1
	
	(a + b)^2 = a^2 + 2ab + b^2

	(a - b)^2 = a^2 - 2ab + b^2


this is Eq. :eq:`eq1`


Admonitions
===============

admonition
-------------

.. admonition:: Neque porro quisquam

   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mattis commodo eros, quis posuere enim lobortis quis. Nullam ut tempus nibh.


caution
--------

.. caution:: Neque porro quisquam

   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mattis commodo eros, quis posuere enim lobortis quis. Nullam ut tempus nibh.

danger
---------------


.. danger:: Neque porro quisquam

   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mattis commodo eros, quis posuere enim lobortis quis. Nullam ut tempus nibh.

error
---------------

.. error:: Neque porro quisquam

   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mattis commodo eros, quis posuere enim lobortis quis. Nullam ut tempus nibh.


hint
---------------

.. hint:: Neque porro quisquam

   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mattis commodo eros, quis posuere enim lobortis quis. Nullam ut tempus nibh.

important
---------------

.. important:: Neque porro quisquam

   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mattis commodo eros, quis posuere enim lobortis quis. Nullam ut tempus nibh.

note
---------------

.. note:: Neque porro quisquam

   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mattis commodo eros, quis posuere enim lobortis quis. Nullam ut tempus nibh.

tip
---------------

.. tip:: Neque porro quisquam

   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mattis commodo eros, quis posuere enim lobortis quis. Nullam ut tempus nibh.

warning
---------------

.. warning:: Neque porro quisquam

   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mattis commodo eros, quis posuere enim lobortis quis. Nullam ut tempus nibh


References APA style
--------------------------
.. [1] Cohen, W. M., & Levinthal, D. A. (1989). Innovation and learning: the two faces of R & D. *The economic journal*, 99(397), 569-596.

