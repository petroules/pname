[uname for Windows](http://www.petroules.com)
=================

uname is, as the name suggests, a Windows port of the [uname](https://en.wikipedia.org/wiki/Uname) program found in Unix operating systems.

The purpose is to provide an easy way for software developers writing scripts (mainly as part of build processes) to discover the same information about a Windows operating system that uname provides about Unix systems.



Quick start
-----------

Clone the repo, `git clone git@github.com:petroules/uname-windows.git`, or [download the latest release](https://github.com/downloads/petroules/uname-windows/uname.exe).



Bug tracker
-----------

This project is still very much a work in progress, so if you've found a bug, please create an issue here on GitHub!

https://github.com/petroules/uname-windows/issues



Known issues
------------

uname builds with 32-bit MSVC, 64-bit MSVC or MinGW (32-bit), however only the 32-bit MSVC binary runs correctly. The 64-bit MSVC build has been observed to crash, and the MinGW build has been observed to crash in certain situations, such as whether it's run from cmd.exe or the MinGW shell. We will seek to fix these problems but they are not a priority as they will probably not inconvenience anyone.



Developers
----------

We have included a makefile for convenience of building. You should open the 32-bit Visual Studio command prompt to properly set environment variables.

+ **build** - `nmake`
Compiles uname to an exe.

+ **clean** - `nmake clean`
Removes all files generated by the build.



Authors
-------

**Jake Petroules**

+ http://twitter.com/jakepetroules
+ http://github.com/jakepetroules



Copyright and license
---------------------

Copyright (c) 2012 Petroules Corporation. All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met: 

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer. 
2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution. 

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.