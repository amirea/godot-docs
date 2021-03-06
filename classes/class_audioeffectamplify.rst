.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the AudioEffectAmplify.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_AudioEffectAmplify:

AudioEffectAmplify
==================

**Inherits:** :ref:`AudioEffect<class_audioeffect>` **<** :ref:`Resource<class_resource>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

Adds a Amplify audio effect to an Audio bus.

Increases or decreases the volume of the selected audio bus.

Member Functions
----------------

+----------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_volume_db<class_AudioEffectAmplify_get_volume_db>` **(** **)** const                            |
+----------------------------+-----------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_volume_db<class_AudioEffectAmplify_set_volume_db>` **(** :ref:`float<class_float>` volume **)** |
+----------------------------+-----------------------------------------------------------------------------------------------------------+

Member Variables
----------------

  .. _class_AudioEffectAmplify_volume_db:

- :ref:`float<class_float>` **volume_db** - Amount of amplification. Positive values make the sound louder, negative values make it quieter. Value can range from -80 to 24. Default value: ``0``.


Description
-----------

Increases or decreases the volume being routed through the audio bus.

Member Function Description
---------------------------

.. _class_AudioEffectAmplify_get_volume_db:

- :ref:`float<class_float>` **get_volume_db** **(** **)** const

.. _class_AudioEffectAmplify_set_volume_db:

- void **set_volume_db** **(** :ref:`float<class_float>` volume **)**


