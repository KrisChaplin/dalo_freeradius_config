Introduction
============
This is currently one patch file that enables the various features needed for freeradius to play nicely with daloradius.

Usage
=====
after installing freeradius, change into the root directory, for example /etc/freeradius and then run patch:

cd /etc/freeradius
patch -p0 < /path/to/dalo_freeradius_config.patch
