debootstrap_ creates a Debian base system from scratch,
without requiring the availability of *dpkg* or *APT*.
It does this by downloading ``.deb`` files from a mirror site,
and carefully unpacking them into a directory
which can eventually be chrooted into. 

.. _debootstrap:
   http://packages.debian.org/unstable/deboostrap

**demoostrap** is a crazy debootstrap variant that works offline.
Instead of downloading package from a mirror,
it re-uses packages from the host system.

.. vim:tw=72
