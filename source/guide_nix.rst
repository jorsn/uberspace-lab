.. highlight:: console

.. author:: Johannes Rosenberger <uberlab@jorsn.eu>

.. categorize your guide! refer to the current list of tags: https://lab.uberspace.de/tags
.. tag:: package-management
.. tag:: configuration-management

.. sidebar:: About

  .. image:: _static/images/loremipsum.png
      :align: center

##########
Loremipsum
##########

.. tag_list::

Nix_ is **TODO**

It can only be installed via proot_ in an uberspace, since it stores everything in ``/nix``.

home-manager_ is a nix expression and a cli executable to manage and configure your home-directory with nix.

----

.. note:: For this guide you should be familiar with the basic concepts of

  * :manual:`supervisord <daemons-supervisord>`

License
=======

All relevant legal information can be found here

  * TODO: Nix license
  * TODO: proot license
  * TODO: home-manager license
  * TODO: license of my own nix expressions

Prerequisites
=============


Installation
============

Get Proot
---------

Get Nix
-------

Configuration
=============

Enter Nix Env
-------------

Configure Nix
-------------

Setup home-manager
------------------

Use ubernix modules
-------------------

Enable supervisord services
---------------------------

(Finishing installation)
======================

Point your browser to URL and create a user account.

Best practices
==============

* Nix-Installed files are only accessible to processes started from within the Nix-proot!

Security
--------

Change all default passwords. Look at folder permissions. Don't get hacked!

Tuning
======

* Consider what to manage in Nix/proot and what outside


Other Documentation / Sources
=============================

* NixOS Wiki
* NixOS Manual
* Nixpkgs Manual
* Nix Manual
* Nix Discourse
* Source Code!!!
* (corresponding wiki page!)

Updates
=======

.. note:: Check the update feed_ regularly to stay informed about the newest version.


.. _Nix: https://nixos.org/nix/
.. _proot: https://proot-me.github.io/
.. _home-manager: https://github.com/rycee/home-manager/
.. _feed: https://github.com/lorem/ipsum/releases.atom

----

Tested with Loremipsum 1.22.1, Uberspace 7.1.1

.. author_list::

