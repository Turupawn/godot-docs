.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the VideoPlayer.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_VideoPlayer:

VideoPlayer
===========

**Inherits:** :ref:`Control<class_control>` **<** :ref:`CanvasItem<class_canvasitem>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

Control for playing video streams.

Member Functions
----------------

+--------------------------------+-----------------------------------------------------------------------------+
| :ref:`String<class_string>`    | :ref:`get_stream_name<class_VideoPlayer_get_stream_name>` **(** **)** const |
+--------------------------------+-----------------------------------------------------------------------------+
| :ref:`Texture<class_texture>`  | :ref:`get_video_texture<class_VideoPlayer_get_video_texture>` **(** **)**   |
+--------------------------------+-----------------------------------------------------------------------------+
| :ref:`bool<class_bool>`        | :ref:`is_playing<class_VideoPlayer_is_playing>` **(** **)** const           |
+--------------------------------+-----------------------------------------------------------------------------+
| void                           | :ref:`play<class_VideoPlayer_play>` **(** **)**                             |
+--------------------------------+-----------------------------------------------------------------------------+
| void                           | :ref:`stop<class_VideoPlayer_stop>` **(** **)**                             |
+--------------------------------+-----------------------------------------------------------------------------+

Signals
-------

.. _class_VideoPlayer_finished:

- **finished** **(** **)**

Emitted when playback is finished.


Member Variables
----------------

  .. _class_VideoPlayer_audio_track:

- :ref:`int<class_int>` **audio_track** - The embedded audio track to play.

  .. _class_VideoPlayer_autoplay:

- :ref:`bool<class_bool>` **autoplay** - If ``true`` playback starts when the scene loads. Default value: ``false``.

  .. _class_VideoPlayer_buffering_msec:

- :ref:`int<class_int>` **buffering_msec** - Amount of time in milliseconds to store in buffer while playing.

  .. _class_VideoPlayer_bus:

- :ref:`String<class_string>` **bus** - Audio bus to use for sound playback.

  .. _class_VideoPlayer_expand:

- :ref:`bool<class_bool>` **expand** - If ``true`` the video scales to the control size. Default value: ``true``.

  .. _class_VideoPlayer_paused:

- :ref:`bool<class_bool>` **paused** - If ``true`` the video is paused.

  .. _class_VideoPlayer_stream:

- :ref:`VideoStream<class_videostream>` **stream**

  .. _class_VideoPlayer_stream_position:

- :ref:`float<class_float>` **stream_position** - The current position of the stream, in seconds.

  .. _class_VideoPlayer_volume:

- :ref:`float<class_float>` **volume** - Audio volume as a linear value.

  .. _class_VideoPlayer_volume_db:

- :ref:`float<class_float>` **volume_db** - Audio volume in dB.


Description
-----------

Control node for playing video streams. Supported formats are WebM and OGV Theora.

Member Function Description
---------------------------

.. _class_VideoPlayer_get_stream_name:

- :ref:`String<class_string>` **get_stream_name** **(** **)** const

Returns the video stream's name.

.. _class_VideoPlayer_get_video_texture:

- :ref:`Texture<class_texture>` **get_video_texture** **(** **)**

Returns the current frame as a :ref:`Texture<class_texture>`.

.. _class_VideoPlayer_is_playing:

- :ref:`bool<class_bool>` **is_playing** **(** **)** const

Returns ``true`` if the video is playing.

.. _class_VideoPlayer_play:

- void **play** **(** **)**

Starts the video playback.

.. _class_VideoPlayer_stop:

- void **stop** **(** **)**

Stops the video playback.


