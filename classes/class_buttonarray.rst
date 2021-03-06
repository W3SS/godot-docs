.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the doc/base/classes.xml source instead.

.. _class_ButtonArray:

ButtonArray
===========

**Inherits:** :ref:`Control<class_control>` **<** :ref:`CanvasItem<class_canvasitem>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Inherited By:** :ref:`HButtonArray<class_hbuttonarray>`, :ref:`VButtonArray<class_vbuttonarray>`

**Category:** Core

Brief Description
-----------------

Array of Buttons.

Member Functions
----------------

+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| void                         | :ref:`add_button<class_ButtonArray_add_button>`  **(** :ref:`String<class_string>` text  **)**                                                |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| void                         | :ref:`add_icon_button<class_ButtonArray_add_icon_button>`  **(** :ref:`Object<class_object>` icon, :ref:`String<class_string>` text=""  **)** |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| void                         | :ref:`set_button_text<class_ButtonArray_set_button_text>`  **(** :ref:`int<class_int>` button, :ref:`String<class_string>` text  **)**        |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| void                         | :ref:`set_button_icon<class_ButtonArray_set_button_icon>`  **(** :ref:`int<class_int>` button, :ref:`Object<class_object>` icon  **)**        |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_string>`  | :ref:`get_button_text<class_ButtonArray_get_button_text>`  **(** :ref:`int<class_int>` button  **)** const                                    |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_object>`  | :ref:`get_button_icon<class_ButtonArray_get_button_icon>`  **(** :ref:`int<class_int>` button  **)** const                                    |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`        | :ref:`get_button_count<class_ButtonArray_get_button_count>`  **(** **)** const                                                                |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`        | :ref:`get_selected<class_ButtonArray_get_selected>`  **(** **)** const                                                                        |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`        | :ref:`get_hovered<class_ButtonArray_get_hovered>`  **(** **)** const                                                                          |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| void                         | :ref:`set_selected<class_ButtonArray_set_selected>`  **(** :ref:`int<class_int>` button  **)**                                                |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| void                         | :ref:`erase_button<class_ButtonArray_erase_button>`  **(** :ref:`int<class_int>` button  **)**                                                |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| void                         | :ref:`clear<class_ButtonArray_clear>`  **(** **)**                                                                                            |
+------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+

Signals
-------

-  **button_selected**  **(** :ref:`int<class_int>` button  **)**

Numeric Constants
-----------------

- **ALIGN_BEGIN** = **0** --- Align buttons at the beginning.
- **ALIGN_CENTER** = **1** --- Align buttons in the middle.
- **ALIGN_END** = **2** --- Align buttons at the end.
- **ALIGN_FILL** = **3** --- Spread the buttons, but keep them small.
- **ALIGN_EXPAND_FILL** = **4** --- Spread the buttons, but expand them.

Description
-----------

Array of Buttons. A Button array is useful to have an array of buttons laid out vertically or horizontally. Only one can be selected. This is useful for joy pad based interfaces and option menus.

Member Function Description
---------------------------

.. _class_ButtonArray_add_button:

- void  **add_button**  **(** :ref:`String<class_string>` text  **)**

Add a new button.

.. _class_ButtonArray_add_icon_button:

- void  **add_icon_button**  **(** :ref:`Object<class_object>` icon, :ref:`String<class_string>` text=""  **)**

.. _class_ButtonArray_set_button_text:

- void  **set_button_text**  **(** :ref:`int<class_int>` button, :ref:`String<class_string>` text  **)**

.. _class_ButtonArray_set_button_icon:

- void  **set_button_icon**  **(** :ref:`int<class_int>` button, :ref:`Object<class_object>` icon  **)**

Set the icon of an existing button.

.. _class_ButtonArray_get_button_text:

- :ref:`String<class_string>`  **get_button_text**  **(** :ref:`int<class_int>` button  **)** const

Return the text of an existing button.

.. _class_ButtonArray_get_button_icon:

- :ref:`Object<class_object>`  **get_button_icon**  **(** :ref:`int<class_int>` button  **)** const

Return the icon of an existing button.

.. _class_ButtonArray_get_button_count:

- :ref:`int<class_int>`  **get_button_count**  **(** **)** const

Return the amount of buttons in the array.

.. _class_ButtonArray_get_selected:

- :ref:`int<class_int>`  **get_selected**  **(** **)** const

Return the currently selected button in the array.

.. _class_ButtonArray_get_hovered:

- :ref:`int<class_int>`  **get_hovered**  **(** **)** const

Return the currently hovered button in the array.

.. _class_ButtonArray_set_selected:

- void  **set_selected**  **(** :ref:`int<class_int>` button  **)**

Select a button in the array.

.. _class_ButtonArray_erase_button:

- void  **erase_button**  **(** :ref:`int<class_int>` button  **)**

Remove a button in the array, by index.

.. _class_ButtonArray_clear:

- void  **clear**  **(** **)**

Clear the button array.


