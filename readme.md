 If you wish to see how this proxy script works in practice on a live server, visit unblockvideos.com which is powered by this very same software application.
PHP-Proxy as an alternative to Glype

The main motivation behind the creation of this project is to create a better alternative to Glype which at that time was extremely lacking in many features that I wanted. Latest version of Glype can be downloaded directly from their site on their download page, but most of their site appears to be down. If that is the case, you can download Glype 1.4 directly from our servers.
PHP-Proxy vs PHPProxy

Despite sharing almost the exact name, this proxy script has no relationship to the once popular PHPProxy script from whitefyre which has been officially discontinued on September 7 of 2007. However, its last version that was last updated in 2013, PHPProxy can still be downloaded from SourceForge, and it is still receving hundreds of downloads each week.

It is still usable for now, but there have been no updates or new features added to it for many years now. There are many similar function proxy scripts named "PHP Proxy", we were just the lucky ones to acquire such domain name. While PHPProxy is still being widely used, it is outdated, hard to customize and it breaks on many popular websites such as Facebook and YouTube.

Download PHP-Proxy

The method of installation depends on the type of web server that you have. I would recommend installing it via Composer using this command (replacing /var/www/ with the web directory of your choice):

	composer create-project athlon1600/php-proxy-app:dev-master /var/www/
	

For those who do not have access to shell, for example, people on a shared hosting environment, would need to download a pre-installed version of php-proxy, and then upload it to their web-server. 
