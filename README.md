Nmap [![Build Status](https://travis-ci.org/nmap/nmap.svg?branch=master)](https://travis-ci.org/nmap/nmap) [![Language grade: C/C++](https://img.shields.io/lgtm/grade/cpp/g/nmap/nmap.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/nmap/nmap/context:cpp) [![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/nmap/nmap.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/nmap/nmap/context:python) [![Total alerts](https://img.shields.io/lgtm/alerts/g/nmap/nmap.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/nmap/nmap/alerts/)
====

Nmap is released under a custom license, which is based on (but not compatible
with) GPLv2. The Nmap license allows free usage by end users, and we also offer
a commercial license for companies that wish to redistribute Nmap technology
with their products. See [Nmap Copyright and Licensing](https://nmap.org/book/man-legal.html)
for full details.

The latest version of this software as well as binary installers for Windows,
macOS, and Linux (RPM) are available from
[Nmap.org](https://nmap.org/download.html)

Full documentation is also available
[on the Nmap.org website](https://nmap.org/docs.html).

Questions and suggestions may be sent to
[the Nmap-dev mailing list](https://nmap.org/mailman/listinfo/dev).

Installing
----------
Ideally, you should be able to just type:

    ./configure
    make
    make install

For far more in-depth compilation, installation, and removal notes, read the
[Nmap Install Guide](https://nmap.org/book/install.html) on Nmap.org.

Using Nmap
----------
Nmap has a lot of features, but getting started is as easy as running `nmap
scanme.nmap.org`. Running `nmap` without any parameters will give a helpful
list of the most common options, which are discussed in depth in [the man
page](https://nmap.org/book/man.html). Users who prefer a graphical interface
can use the included [Zenmap front-end](https://nmap.org/zenmap/).

Contributing
------------
Information about filing bug reports and contributing to the Nmap project can
be found in the [HACKING](HACKING) and [CONTRIBUTING.md](CONTRIBUTING.md)
files.

# Speedy-Fastest-Live-Port-Scanner
Faster and more stable port scanner than nmap or rustscan to scan for all open ports
This is created to shorten the time of detecting open ports for CTF
place speedy binary in /usr/bin

Usage:

./speedy

choose as option:
1 - check all ports
2 - manual check
>

type in 1 to check all 65535 ports for ipv4 address

type in 2 to check for single port

>1

target ip
>192.168.0.1 (example)

Port 53 is open
Port 45555 is open
Port 80 is open
12% complete
25% complete
38% complete
51% complete
Port 443 is open
64% complete
77% complete
90% complete
#Checking for false positives...
Port 53,45555,80,443 are open!

>2
target ip
>192.168.0.1 (example)

check port
>80
Port 80 is open

Feel free to give suggestions or help to contribute to this tool.
