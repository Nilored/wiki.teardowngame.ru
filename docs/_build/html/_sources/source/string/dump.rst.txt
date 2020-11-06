string.dump
===========

``string string.dump( function func, boolean stripDebugInfo = false )``

.. list-table::
   :header-rows: 1
   :widths: 2 2 4

   * - Type
     - Argument
     - Description

   * - function
     - func
     - The function to get the bytecode of

   * - boolean
     - stripDebugInfo = false
     - True to strip the debug data, false to keep it
	 
Returns the binary bytecode of the given function.

.. note::
	This does not work with functions created in C/C++. An error will be thrown if it is
