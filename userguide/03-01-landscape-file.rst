.. _03-01-landscape-file:

**************
Landscape File
**************

Location
========
The default location where the **Automation Kit** will look for the *landscape.yaml* file
is:

.. code-block:: text

    ~/akit/config/landscapes/default-landscape.yaml


Environment Variable
====================
You can specify a different location and name for the *landscape.yaml* by setting the
*AKIT_LANDSCAPE* environment variable like so:

.. code-block:: bash

    AKIT_LANDSCAPE="/home/jenkins/workspace/landscape.yaml"

The **Automation Kit** does support expanding the *~* user and *$VARIABLE* environment
variables in the specific path.


Commandline Option
==================
The name and location of the *landscape.yaml* configuration file can also be specific
on the commandline.


Description
===========

Environment Section
-------------------


Pod Section
-----------

Devices Sub-Section
+++++++++++++++++++

Power Sub-Section
+++++++++++++++++

Serial Sub-Section
++++++++++++++++++


Full Example
------------

.. literalinclude:: examples/landscape.yaml
   :language: yaml

