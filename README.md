README FOR JPGRAPH 4.0.2
=========================

This package contains the JpGraph PHP library version 4.0.2

The library is Copyright (C) 2000-2010 Asial Corporatoin and
released under dual license QPL 1.0 for open source and educational
use and JpGraph Professional License for commercial use. 

Please see full license details at 
http://jpgraph.net/pro/
http://jpgraph.net/download/


Requirements:
-------------
Miminum:
* PHP 5.1.0 or higher 
* GD 2.0.28 or higher
Note: Earlier versions might work but is unsupported.

Recommended:
* >= PHP 5.2.0
* PHP Builtin GD library

Installation
------------
1. Make sure that the PHP version is compatible with the stated 
   requirements and that the PHP installation has support for 
   the GD library. Please run phpinfo() to check if GD library 
   is supported in the installation. 
   If the GD library doesn't seem to be installed 
   please consult the PHP manual under section "Image" for
   instructions on where to find this library. Please refer to
   the manual section "Verifying your PHP installation"
   
2. Unzip and copy the files to a directory of your choice where Your
   httpd sever can access them. 
   For a global site installation you should copy the files to 
   somewhere in the PHP search path. 

3. Check that the default directory paths in jpg-config.inc.php
   for cache directory and TTF directory suits your installation. 
   Note1: The default directories are different depending on if
   the library is running on Windows or UNIX.
   Note2: Apache/PHP must have write permission to your cache 
   directory if you enable the cache feature. By default the cache
   is disabled.
   

Documentation
-------------
The installation includes HTML documentation and reference guide for the
library. The portal page for all documentation is
<YOUR-INSTALLATION-DIRECTORY>/docs/index.html


Bug reports and suggestions
---------------------------
Should be reported using the contact form at

http://jpgraph.net/contact/
