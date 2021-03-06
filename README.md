# Visual-Hoax-for-UEFI-Shell

## Goal
Demonstration of how to implement hoax software tools to access
the Intel BayTrail (BYT) platform hardware or data structures directly or
by UEFI API.

The projects are kept small and simple to introduce the UEFI shell
programming using "ANSI C", easily and quickly.

## Approach
It is intended to use Visual Studio 2019 as the only development environment.
Furthermore it is intended to use ANSI-C library functions as far as possible.

Doing so, the UEFI Shell applications can be easily debugged
on the Windows development platform, simply by building the sourcecode
as a Win64-executable (change the solution configuration from Efi64 to Win64 ).

## HowTo
https://github.com/KilianKegel/HowTo-setup-an-UEFI-Development-PC#howto-setup-an-uefi-development-pc

## Revision history
https://github.com/KilianKegel/torito-C-Library#revision-history
### 20200204/R154
* Update to torito-C 20200204/R154
* adjust solution configurations
* update copyright
### 20191018/R141
* update Torito C Library https://github.com/KilianKegel/torito-C-Library#20191017r141
### 20190929
* update to Torito C Library ver. R138
* update copyright

### 20190423 - initial revision
* MinnowBlink182 -- LED blink program on MinnowBoard

