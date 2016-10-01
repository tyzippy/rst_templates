Tables
##############

Tables are tagged using ``.. list-table::``

Each table has the number of columns and their associated relative widths
indicated in a width tag.

For proper formatting, the asterisk indicating each row must align vertically,
and the hyphens indicating each column must also align. Empty cells must be
accounted for, so that each column in a row is always marked, even if there is
no content in the table cell.

Use the following as a table template.

.. list-table::
   :widths: 25 25 50
   :header-rows: 1

   * - Heading row 1, column 1
     - Heading row 1, column 2
     - Heading row 1, column 3
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3
   * - Row 3, column 1
     - Row 3, column 2
     - Row 3, column 3


.. include:: ../includes.txt
