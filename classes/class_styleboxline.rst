:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the StyleBoxLine.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_StyleBoxLine:

StyleBoxLine
============

**Inherits:** :ref:`StyleBox<class_StyleBox>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

:ref:`StyleBox<class_StyleBox>` that displays a single line.

Description
-----------

:ref:`StyleBox<class_StyleBox>` that displays a single line of a given color and thickness. It can be used to draw things like separators.

Properties
----------

+---------------------------+-----------------------------------------------------------+-----------------------+
| :ref:`Color<class_Color>` | :ref:`color<class_StyleBoxLine_property_color>`           | ``Color(0, 0, 0, 1)`` |
+---------------------------+-----------------------------------------------------------+-----------------------+
| :ref:`float<class_float>` | :ref:`grow_begin<class_StyleBoxLine_property_grow_begin>` | ``1.0``               |
+---------------------------+-----------------------------------------------------------+-----------------------+
| :ref:`float<class_float>` | :ref:`grow_end<class_StyleBoxLine_property_grow_end>`     | ``1.0``               |
+---------------------------+-----------------------------------------------------------+-----------------------+
| :ref:`int<class_int>`     | :ref:`thickness<class_StyleBoxLine_property_thickness>`   | ``1``                 |
+---------------------------+-----------------------------------------------------------+-----------------------+
| :ref:`bool<class_bool>`   | :ref:`vertical<class_StyleBoxLine_property_vertical>`     | ``false``             |
+---------------------------+-----------------------------------------------------------+-----------------------+

Property Descriptions
---------------------

.. _class_StyleBoxLine_property_color:

- :ref:`Color<class_Color>` **color**

+-----------+-----------------------+
| *Default* | ``Color(0, 0, 0, 1)`` |
+-----------+-----------------------+
| *Setter*  | set_color(value)      |
+-----------+-----------------------+
| *Getter*  | get_color()           |
+-----------+-----------------------+

The line's color.

----

.. _class_StyleBoxLine_property_grow_begin:

- :ref:`float<class_float>` **grow_begin**

+-----------+-----------------------+
| *Default* | ``1.0``               |
+-----------+-----------------------+
| *Setter*  | set_grow_begin(value) |
+-----------+-----------------------+
| *Getter*  | get_grow_begin()      |
+-----------+-----------------------+

The number of pixels the line will extend before the ``StyleBoxLine``'s bounds. If set to a negative value, the line will begin inside the ``StyleBoxLine``'s bounds.

----

.. _class_StyleBoxLine_property_grow_end:

- :ref:`float<class_float>` **grow_end**

+-----------+---------------------+
| *Default* | ``1.0``             |
+-----------+---------------------+
| *Setter*  | set_grow_end(value) |
+-----------+---------------------+
| *Getter*  | get_grow_end()      |
+-----------+---------------------+

The number of pixels the line will extend past the ``StyleBoxLine``'s bounds. If set to a negative value, the line will end inside the ``StyleBoxLine``'s bounds.

----

.. _class_StyleBoxLine_property_thickness:

- :ref:`int<class_int>` **thickness**

+-----------+----------------------+
| *Default* | ``1``                |
+-----------+----------------------+
| *Setter*  | set_thickness(value) |
+-----------+----------------------+
| *Getter*  | get_thickness()      |
+-----------+----------------------+

The line's thickness in pixels.

----

.. _class_StyleBoxLine_property_vertical:

- :ref:`bool<class_bool>` **vertical**

+-----------+---------------------+
| *Default* | ``false``           |
+-----------+---------------------+
| *Setter*  | set_vertical(value) |
+-----------+---------------------+
| *Getter*  | is_vertical()       |
+-----------+---------------------+

If ``true``, the line will be vertical. If ``false``, the line will be horizontal.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
