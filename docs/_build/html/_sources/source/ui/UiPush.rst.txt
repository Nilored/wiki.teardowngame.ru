UiPush
======

``UiPush()``

Declares a user interface object.

.. note::
	It must be closed with :ref:`UiPop`
	
*******
Example
*******

.. code-block:: lua

	UiPush()
		UiTranslate(0, 0)
		UiColor(0, 0, 0, 0.7)
		UiRect(UiWidth(), UiHeight())
		UiTranslate(50, 50)
		UiColor(1, 1, 1, 1)
		UiAlign("top left")
		UiFont("font/bold.ttf", 26)
		UiText("Hello World!")
	UiPop()
