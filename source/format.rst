Supported Formats
=================

DocumentValidator supports two types of input format, "Plain text" and "Wiki format".


Plain text
-----------

Plain text just supoorts a set of paragraphs. Paragraphs are separated by two new lines. For example the following article has two paragraph.

.. code-block:: text

  This is a first paragraph. This paragraph is for the introduction of this article.
  I will introduce the central issue discussed throughout the article.

  Second paragraph describe the details of the issue and show the solution.

Wiki format
-------------

DocumentValidator supports the fraction of Wiki syntacs. The followings the supported elements of Wiki syntacs.

Headings
~~~~~~~~~

For making a heading, we add a line starts with a "h[1234]. ". The digits after h represents levels of the heding (section).


Inline Formatting
~~~~~~~~~~~~~~~~~~~

DocumentValidator supports the following inline formatting.

Bold
^^^^^

.. code-block:: text

  **this is a Bold sentence.**

Italic
^^^^^^^

.. code-block:: text

  //this is a italic syntacs.//

Unerline
^^^^^^^^^

.. code-block:: text

  __this is a underlined syntacs.__

Strikethrough
^^^^^^^^^^^^^^

.. code-block:: text

  --this is a strikethrough syntacs.--

Links
~~~~~

Links elements are included in the Wiki formatted documents.

Lists
~~~~~

Bulleted Lists
^^^^^^^^^^^^^^^

To make a bullted list, start a line with a "asterrisks". The number of asterrisks represents the indents of the list. 

.. code-block:: text

  * List
  * List
  ** Sub List

Numbered List
^^^^^^^^^^^^^^

If you want to add numbered lists, use "sharp" insted of asterisks in Bulleted Lists.

Comments
~~~~~~~~

To add a comment to the wiki source, add [!-- ... --] block.
The followings are a sample of comment.

.. code-block:: text

   [!--
     This is a comment.
   --]



Paragraphs
~~~~~~~~~~

Paragraphs are separated by two new lines the syntacs are the samme as plain text.