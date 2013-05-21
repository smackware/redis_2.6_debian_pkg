redis_2.6_debian_pkg
====================

Building
-------------
	wget http://redis.googlecode.com/files/redis-2.6.13.tar.gz
	tar -xvzf redis-2.6.13.tar.gz
	cd redis-2.6.13
	git clone https://github.com/smackware/redis_2.6_debian_pkg.git debian
	dpkg-buildpackage -b -uc -rfakeroot
