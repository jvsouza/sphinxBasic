About
================================

.. note::

    You must have ersion 2.6.0 or greater and 6.0.0 or greater
    for the instructions below to work. The pyinstaller hook from  2.5.x
    may work with certain versions however support for Pyinstaller
    was not fully stable across all operating systems until2.6.0

You've written your game using and it is a masterpiece! Congrats! Now

.. code-block:: bash

    pyinstaller myscript.py --add-data "images;images"

You can use the ``--add-data`` flag 

.. code-block:: python

    import arcade
    arcade.open_window(400, 400, "My Script")


Troubleshooting
---------------

Use a One-Folder Bundle for Troubleshooting
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you are having problems getting your bundle to work properly,