You can use conditions in RST text. Then using Sphinx, pass the condition name in when you build HTML.  Then text in that condition is printed, and other conditions are not.

.. only:: Condition A

  Add indented content to be included only in Condition A documentation.

.. only:: Condition B

  Add indented content to be included only in Condition B documentation.

.. only:: Condition C

  Add indented content to be included only in Condition C documentation.
