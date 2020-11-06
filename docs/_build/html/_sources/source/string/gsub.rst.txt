string.gsub
===========

``string, number string.gsub( string string, string pattern, string replacement, number maxReplaces = nil )``

.. list-table::
   :header-rows: 1
   :widths: 2 2 4

   * - Type
     - Argument
     - Description

   * - string
     - string
     - String which should be modified.

   * - string
     - pattern
     - The pattern that defines what should be matched and eventually be replaced.

   * - string
     - replacement
     - In case of a string the matched sequence will be replaced with it. In case of a table, the matched sequence will be used as key and the table will tested for the key, if a value exists it will be used as replacement. In case of a function all matches will be passed as parameters to the function, the return value(s) of the function will then be used as replacement.
	 
This functions main purpose is to replace certain character sequences in a string using

*******
Example
*******

Replaces "hello" with "hi" in the string "hello there!"

.. code-block:: lua

	string.gsub("hello there!", "hello", "hi")