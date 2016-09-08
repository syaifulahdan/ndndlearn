
#Prerequisites

####1. Core dependencies
- python >= 2.6
- libsqlite3
- libcrypto++
- pkg-config
- Boost libraries >= 1.49

#### Linux 16.04

sudo apt-get install build-essential libsqlite3-dev libcrypto++-dev

##### For Ubuntu 12.04
sudo apt-get install python-software-properties
sudo add-apt-repository ppa:boost-latest/ppa
sudo apt-get update
sudo apt-get install libboost1.55-all-dev

##### For all other Ubuntu versions
sudo apt-get install libboost-all-dev
<pre>
bertopeng17@bertopeng17-ThinkPad-T520:~$ <b>sudo apt-get install build-essential libsqlite3-dev libcrypto++-dev</b>
[sudo] password for bertopeng17: 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
build-essential is already the newest version (12.1ubuntu2).
build-essential set to manually installed.
Suggested packages:
  sqlite3-doc
The following NEW packages will be installed:
  libcrypto++-dev libcrypto++9v5 libsqlite3-dev
0 upgraded, 3 newly installed, 0 to remove and 130 not upgraded.
Need to get 2.973 kB of archives.
After this operation, 18,9 MB of additional disk space will be used.
Get:1 http://id.archive.ubuntu.com/ubuntu xenial/universe i386 libcrypto++9v5 i386 5.6.1-9 [950 kB]
Get:2 http://id.archive.ubuntu.com/ubuntu xenial/universe i386 libcrypto++-dev i386 5.6.1-9 [1.491 kB]
Get:3 http://id.archive.ubuntu.com/ubuntu xenial/main i386 libsqlite3-dev i386 3.11.0-1ubuntu1 [533 kB]
Fetched 2.973 kB in 30s (98,7 kB/s)                                            
Selecting previously unselected package libcrypto++9v5.
(Reading database ... 176087 files and directories currently installed.)
Preparing to unpack .../libcrypto++9v5_5.6.1-9_i386.deb ...
Unpacking libcrypto++9v5 (5.6.1-9) ...
Selecting previously unselected package libcrypto++-dev.
Preparing to unpack .../libcrypto++-dev_5.6.1-9_i386.deb ...
Unpacking libcrypto++-dev (5.6.1-9) ...
Selecting previously unselected package libsqlite3-dev:i386.
Preparing to unpack .../libsqlite3-dev_3.11.0-1ubuntu1_i386.deb ...
Unpacking libsqlite3-dev:i386 (3.11.0-1ubuntu1) ...
Processing triggers for libc-bin (2.23-0ubuntu3) ...
Setting up libcrypto++9v5 (5.6.1-9) ...
Setting up libcrypto++-dev (5.6.1-9) ...
Setting up libsqlite3-dev:i386 (3.11.0-1ubuntu1) ...
Processing triggers for libc-bin (2.23-0ubuntu3) ...
bertopeng17@bertopeng17-ThinkPad-T520:~$ ^
</pre>

####2. Dependencies for NS-3 Python bindings

<div class="highlight-bash"><div class="highlight"><pre>sudo apt-get install python-dev python-pygraphviz python-kiwi
sudo apt-get install python-pygoocanvas python-gnome2
sudo apt-get install python-rsvg ipython
</pre></div>
