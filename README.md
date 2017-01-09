## phantomjs-2.1.1-linux-arm

PhantomJS 2.1.1, compiled on Debian “jessie” for Raspberry PI using QEMU (http://wiki.qemu.org/Main_Page)

PhantomJS is a headless WebKit with JavaScript API. It has fast and native support for various web standards: DOM handling, CSS selector, JSON, Canvas, and SVG. (http://phantomjs.org).


### Installation on Raspberry PI

Download the archive and extract the binary:

<pre>
$ cd /tmp
$ wget https://raw.githubusercontent.com/ApioLab/phantomjs-2.1.1-linux-arm/master/phantomjs-2.1.1-linux-arm.tar.bz2
$ bunzip2 phantomjs-2.1.1-linux-arm.tar.bz2
$ tar xvf phantomjs-2.1.1-linux-arm.tar
</pre>

The binary <code>phantomjs</code> is located in the <code>bin</code> directory:

<pre>
$ ./phantomjs-2.1.1-linux-arm/bin/phantomjs --version
2.1.1
</pre>


### Build Process

PhantomJS has been built using the process described below.

__1.__ Set a QEMU Emulator as described in here: https://wiki.debian.org/RaspberryPi/qemu-user-static

__2.__ Followed the build instructions as described in here: http://phantomjs.org/build.html
