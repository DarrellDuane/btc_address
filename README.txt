  $Id$
Description
-----------
This module provides a Bitcoin Address field type for CCK.

Features:
---------
* Validation of Bitcoin Address

Prerequisites
-------------
* The btc_address.module requires the content.module and 
  libraries.module to be installed.

* The btc_address.module needs to have the Bitcoin-PHP library installed.
  - Make the sites/all/libraries directory if needed, cd to this directory.
  - Do a git clone of this library by typing:  
           git clone https://github.com/mikegogulski/bitcoin-php.git
  - bitcoin.inc and the incldues/ & tests/ directories will now be in sites/all/libraries/bitcoin-php/src.

* The Bitcoin libary needs to have bcmath enabled for PHP.  
  As root on your server, run:
     Fedora:   yum -y install php-bcmath
     Ubuntu/Debian:  ??

Then restart apache.

Installation
------------
To install, copy the btc_address directory and all its contents to your modules
directory.

Configuration
-------------
To enable this module, visit administer -> modules, and enable Bitcoin Address.

Bugs/Features/Patches:
----------------------
If you want to report bugs, feature requests, or submit a patch, please do so
at the project page on the Drupal web site.
http://drupal.org/project/btc_address once the project has been established.

To Do List:
----------
* Add Ajax based icon indicating valid or invalid address at address paste time.
* Add an optional field to hold a description of the Bitcoin address.
* Interface directly with bitcoind via JSON query

Author
------
Darrell Duane (http://duane.com)

If you use this module, find it useful, and want to send the author
a thank you note, then use the Feedback/Contact page at the URL above.

Bitcoin donations to 1NS99gkP5p6TL6RL3y6atAMp6vXpLseyog are greatly appreciated;
Taking the time to send even BTC 0.01 or BTC 0.05 means a whole lot!

The author can also be contacted for paid customizations of this
and other modules.
