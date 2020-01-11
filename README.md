# Quickcam Messenger & Communicate driver for Linux Patches

## Preamble

The Quickcam Messenger & Communicate driver for Linux is the only driver
that sufficiently supports the following Logitech devices:
  * Quickcam Messenger      (046D:08F0)
  * Quickcam Messenger Plus (046D:08F6)
  * Quickcam Communicate    (046D:08F5)

The original driver is written by Christian Magnusson <mag@mag.cx> and can
be found at http://home.mag.cx/messenger/

## About

This document describes the content of the folder in which it is found. The
folder content consists of patches for the qc-usb-messenger distribution.

## Purpose

These patches are only small fixes that enable the compile of the original
driver on newer than 2.6.28 linux kernels. Not all kernels are supported
though. Official support from the original driver author seems to lack
since May 2008.

## License

The patches are with the same license as the original driver - GNU's
General Public License.

## Usage

Usage of these patches is at your own risk. There is no any guarantee that
they will work for you, thought they work for me. The testing of the patches
is done on Slackware Linux 12.0 or above.

