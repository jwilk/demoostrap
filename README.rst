Overview
========

debootstrap_ creates a Debian base system from scratch,
without requiring the availability of *dpkg* or *APT*.
It does this by downloading ``.deb`` files from a mirror site,
and carefully unpacking them into a directory
which can eventually be chrooted into. 

**demoostrap** is a crazy debootstrap variant that works offline.
Instead of downloading packages from a mirror,
it re-uses packages from the host system.

Dependencies
============

* Python 3
* debootstrap_
* dpkg-repack_


.. _debootstrap:
   http://packages.debian.org/unstable/debootstrap
.. _dpkg-repack:
   http://packages.debian.org/unstable/dpkg-repack

.. vim:tw=72
