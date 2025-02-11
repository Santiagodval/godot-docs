:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the AudioEffectAmplify.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_AudioEffectAmplify:

AudioEffectAmplify
==================

**Inherits:** :ref:`AudioEffect<class_AudioEffect>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Adds an amplifying audio effect to an audio bus.

Description
-----------

Increases or decreases the volume being routed through the audio bus.

Tutorials
---------

- :doc:`Audio buses <../tutorials/audio/audio_buses>`

Properties
----------

+---------------------------+---------------------------------------------------------------+---------+
| :ref:`float<class_float>` | :ref:`volume_db<class_AudioEffectAmplify_property_volume_db>` | ``0.0`` |
+---------------------------+---------------------------------------------------------------+---------+

Property Descriptions
---------------------

.. _class_AudioEffectAmplify_property_volume_db:

- :ref:`float<class_float>` **volume_db**

+-----------+----------------------+
| *Default* | ``0.0``              |
+-----------+----------------------+
| *Setter*  | set_volume_db(value) |
+-----------+----------------------+
| *Getter*  | get_volume_db()      |
+-----------+----------------------+

Amount of amplification in decibels. Positive values make the sound louder, negative values make it quieter. Value can range from -80 to 24.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
