==================
modprobe-blacklist
==================
Blacklist specific modules using modprobe.d/blacklist.conf.

In order to use set DIB_MODPROBE_BLACKLIST to the name of your
module. To disable multiple modules you can set DIB_MODPROBE_BLACKLIST
to a list of string separated by spaces.

Example:

  export DIB_MODPROBE_BLACKLIST="igb"

.. note::
   This element has been deprecated and replaced by the modprobe element, that
   covers 100% the modprobe-blacklist functionality.
