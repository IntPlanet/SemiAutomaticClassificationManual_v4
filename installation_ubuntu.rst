.. _installation_ubuntu:

****************************
Installation in Ubuntu Linux
****************************

.. |br| raw:: html

	<br />

.. _QGIS_installation_ubuntu:
 
QGIS download and installation
------------------------------------------

* Open a terminal and type::

	sudo apt-get update

* Press Enter and type the user password;

* Type in a terminal::

	sudo apt-get install qgis python-matplotlib python-scipy

* Press Enter and wait until the software is downloaded and installed.

Now, QGIS 2 is installed.

.. image:: _static/QGIS_u.jpg

.. _plugin_installation_ubuntu:
 
Semi-Automatic Classification Plugin installation
---------------------------------------------------

* Run QGIS 2;

* From the main menu, select ``Plugins`` > ``Manage and Install Plugins``;

.. image:: _static/install_u.jpg

* From the menu ``All``, select the Semi-Automatic Classification Plugin and click the button ``Install plugin``;

.. image:: _static/plugins.jpg

* The SCP should be automatically activated; however, be sure that the Semi-Automatic Classification Plugin is checked in the menu ``Installed`` (the restart of QGIS could be necessary to complete the SCP installation);

.. image:: _static/plugins_installed.jpg

.. _plugin_configuration_ubuntu:

Configuration of the plugin
---------------------------

Now, the Semi-Automatic Classification Plugin is installed and two docks and a toolbar should be added to QGIS.
Also, a SCP menu is available in the Menu Bar of QGIS. 
It is possible to move the :ref:`toolbar` and the docks according to your needs, as in the following image.
	
.. image:: _static/SemiAutomaticClassificationPlugin.jpg

The configuration of available RAM is recommended in order to reduce the processing time. 
From the :ref:`SCP_menu` select |settings| ``Settings > Processing`` .

.. image:: _static/settings_processing.jpg

In the :ref:`settings_tab`, set the ``Available RAM (MB)`` to a value that should be half of the system RAM. For instance, if your system has 2GB of RAM, set the value to 1024MB.

.. |settings| image:: _static/settings.png
	:width: 20pt
	
.. image:: _static/RAMSettings_u.jpg