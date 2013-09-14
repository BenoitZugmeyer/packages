========
packages
========

This repository contains some ArchLinux packages I had to customize in order to
work with my system.


chromium-nightly
================

This is a mix between the official `chromium`_ (x86_64, core) and the AUR
`chromium-browser-bin`_ packages. It is based on the official PKGBUILD but uses
the precompiled version of chromium.

Changes:
--------

* Binary file and directory are changed from "chromium" to "chromium-nightly",
  so it does not conflict with the extra/chromium package

* Updated PKGBUILD to be close to the extra/chromium package. Benefits:

  * Fixes the "chromium-nightly -h" option

  * Don't change the default browser each time it is installed


linux
=====

This is a fork of the official `linux`_ (x86_64, core) package.

Changes:
--------

* Disable the alsa usb mixer code, in order to make my speakers working again
  (thanks, George_!)


xorg-launch-helper
==================

This is a fork of the AUR `xorg-launch-helper`_ package.

Changes:
--------

* Use a newer version of sources, so configuration does not fail.


.. _chromium-browser-bin: https://aur.archlinux.org/packages/chromium-browser-bin/
.. _chromium: https://www.archlinux.org/packages/extra/x86_64/chromium/
.. _linux: https://www.archlinux.org/packages/core/x86_64/linux/
.. _George: http://article.gmane.org/gmane.linux.alsa.user/37231
.. _xorg-launch-helper: https://aur.archlinux.org/packages/xorg-launch-helper/
