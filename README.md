MyDocker
========

My view of the Docker


License
=======

This script is free software; you can redistribute it and/or modify it under the terms of
the GNU Lesser General Public License as published by the Free Software Foundation;
either version 2.1 of the License, or (at your option) any later version.

You should have received a copy of the GNU Lesser General Public License along with this
script; if not, please visit http://www.gnu.org/copyleft/gpl.html for more information.


Usage
=====

wget https://github.com/tianon/docker-brew-debian/raw/dist/wheezy/rootfs.tar.xz

docker build -t wheezy01 -f ./Dockerfile .

docker run -d --name=test2 wheezy01

docker create --name=test2 wheezy01

docker run -d -p 1022:22/tcp --name testing wheezy01
