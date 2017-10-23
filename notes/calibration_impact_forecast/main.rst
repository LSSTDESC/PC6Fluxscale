.. figure:: ./texmf/logos/header.png
  :name: header
  :target: ./texmf/logos/header.png
  :align: center

========================================================================
StarDICE run 3: simulation and performance forecasts
========================================================================

*Marc Betoule*

A very brief description of your paper, for the folder's README. (Once you've typed this, you'll be asked for three more items:  the project repo name, a serial number (just choose 0000, it'll get changed later), and a short title (that doesn't contain the repo name). These will then be used to set the paper's folder name, for you to accept or modify. Finally, you'll be asked to choose your Note's format, from [tex/apj/mnras/prl/prd/ipynb/md/rst]. You can always change your mind later, and it's easy to convert a tex Note into a journal paper with the start_paper make command.

.. |date| date::
This Note was generated on: |date|


Introduction
============

Write your introduction here!

Method
======

Write about your methods here! Or change the sections to whatever you want!

Results
=======

Write about your results here! Or don't!

Conclusions
===========

Write about your conclusions here. You have drawn some, right?




========================================================
Appendix: LSST DESC Notes ``reStructuredText`` Reference
========================================================

You can delete all of this whenever you're ready.


Introduction
============
This is a template ```reStructuredText`` <http://docs.lsst.codes/en/latest/development/docs/rst_styleguide.html>`_ LSST DESC Note, for you to adapt for your own work.


Sectioning
==========
As you can see above, your content can easily be divided into sections. You can also make subsections, as follows.

A Subsection
------------
You can even have subsubsections, like this:

A Subsubsection
^^^^^^^^^^^^^^^
See? This is a subsubsection.

Another Subsubsection
^^^^^^^^^^^^^^^^^^^^^
And so is this.

Another Subsection
------------------
And so on.


Math
====

You can typeset mathematics using latex commands like this:

.. math::

  \langle f(k) \rangle = \frac{ \sum_{t=0}^{N}f(t,k) }{N}

While this does not render on GitHub, it should get `picked up by Sphinx <http://www.sphinx-doc.org/en/stable/ext/math.html>`_ later and will be available for you to re-use in future latex documents.


Code
====
You can show code in blocks like this:

.. code-block:: python

  print "Hello World"

or this:

.. code-block:: bash

  echo "Hello World"

Inline mentions of code ``objects`` can be made using pairs of backquotes.


Figures
=======
To add figures, add the required image file (PNG, SVG or JPG preferred) to the ``figures`` subdirectory in your Note's folder. Here's an example:

.. figure:: ./figures/desc-logo.png
  :name: fig-logo
  :target: ./figures/desc-logo.png
  :width: 200px
  :align: center

  This is the figure caption: above we have the LSST DESC logo, in PNG format.

And then the text continues. Note that GitHub ignores the image sizing commands when presenting `reStructuredText <https://developer.lsst.io/docs/rst_styleguide.html>`_ format documents; sphinx might not.

Tables
======

Tables can be fiddly in `reStructuredText`. A good place to start is an online table generator like [this one](http://www.tablesgenerator.com/text_tables). Then, you'll need some patience. For more on table formatting, see `this cheatsheet <https://github.com/ralsina/rst-cheatsheet/blob/master/rst-cheatsheet.rst>`_.

+-------+-------+----------------+-----+
|   A   |   B   |      C         |  D  |
+-------+-------+----------------+-----+
| (deg) | (kpc) | ($M_{\odot}$)  |     |
+-------+-------+----------------+-----+
|  0.4  |  3.4  |  $10^{12.2}$   | R,S |
+-------+-------+----------------+-----+
|  9.6  |  8.2  |  $10^{10.4}$   |  S  |
+-------+-------+----------------+-----+


References
==========
You can cite papers (or anything else) by providing hyperlinks. For example, you might have been impressed by the DESC White Paper `(LSST Dark Energy Science Collaboration 2012) <http://arxiv.org/abs/1211.0310>`_.  It should be possible to convert these links to latex citations automatically later.


Further Resources
=================

LSST DESC notes are styled after LSST technotes `(Sick 2016) <https://sqr-000.lsst.io/>`_. You can also `view the restructured text
of (Sick 2016) <https://github.com/lsst-sqre/sqr-000/blob/master/index.rst>`_.
Another nice example of an LSST technote is `(Wood-Vasey 2016) <http://dmtn-008.lsst.io/>`_ - again, the restructured text is
visible `here <https://github.com/lsst-dm/dmtn-008/blob/master/index.rst>`_.

For a guide to ``reStructuredText`` writing, please see the `LSST DM reST Style Suide <https://developer.lsst.io/docs/rst_styleguide.html>`_. There are many other ``reStructuredText`` resources on the web, such as `this cheatsheet <https://github.com/ralsina/rst-cheatsheet/blob/master/rst-cheatsheet.rst>`_.
