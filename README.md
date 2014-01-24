Setup
=====
	$ vagrant up
	$ vagrant ssh
	$ cd haproxy

Building
========
	$ ./build

Releasing
=========
	$ ./release

Testing
=======
	$ sudo dpkg -i haproxy-*deb   # may fail for missing dependencies
	$ sudo apt-get -fy install    # fixes missing dependencies and finishes install
