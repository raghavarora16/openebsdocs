.. doctut documentation master file, created by
   sphinx-quickstart on Thu Feb 23 11:28:26 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

OpenEbs documentation
==============================
***************
Overview
***************

Introduction to OpenEBS
=============================

OpenEBS is a storage platform, written in GoLang, to deliver persistent block storage for container eco system. The storage itself is containerized through a storage POD concept called VSM or "Virtual Storage Machine". VSMs are scheduled and managed using an orchestrator engine called "Maya". VSMs are fully isolated user space storage engines that present the block storage at the front end through iSCSI, NBD or TCMU protocol and consume raw storage from a local OpenEBS host or remote storage.


		
Guide
^^^^^^^


.. toctree::
   :maxdepth: 2
   
   Overview.rst
   Prepare_your_system.rst
   installations.rst
   



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
