![PhishCraft logo](https://raw.github.com/phishcraft/phishcraft/master/static/images/phishcraft_orange.png)

PhishCraft
==========

![Build Status](https://github.com/phishcraft/phishcraft/workflows/CI/badge.svg) [![GoDoc](https://godoc.org/github.com/phishcraft/phishcraft?status.svg)](https://godoc.org/github.com/phishcraft/phishcraft)

PhishCraft: Open-Source Phishing Toolkit

[PhishCraft](https://getphishcraft.com) is an open-source phishing toolkit designed for businesses and penetration testers. It provides the ability to quickly and easily setup and execute phishing engagements and security awareness training.

### Install

Installation of PhishCraft is dead-simple - just download and extract the zip containing the [release for your system](https://github.com/phishcraft/phishcraft/releases/), and run the binary. PhishCraft has binary releases for Windows, Mac, and Linux platforms.

### Building From Source
**If you are building from source, please note that PhishCraft requires Go v1.10 or above!**

To build PhishCraft from source, simply run ```git clone https://github.com/phishcraft/phishcraft.git``` and ```cd``` into the project source directory. Then, run ```go build```. After this, you should have a binary called ```phishcraft``` in the current directory.

### Docker
You can also use PhishCraft via the official Docker container [here](https://hub.docker.com/r/phishcraft/phishcraft/).

### Setup
After running the PhishCraft binary, open an Internet browser to https://localhost:3333 and login with the default username and password listed in the log output.
e.g.
```
time="2020-07-29T01:24:08Z" level=info msg="Please login with the username admin and the password 4304d5255378177d"
```

Releases of PhishCraft prior to v0.10.1 have a default username of `admin` and password of `phishcraft`.

### Documentation

Documentation can be found on our [site](http://getphishcraft.com/documentation). Find something missing? Let us know by filing an issue!

### Issues

Find a bug? Want more features? Find something missing in the documentation? Let us know! Please don't hesitate to [file an issue](https://github.com/phishcraft/phishcraft/issues/new) and we'll get right on it.

### License
```
PhishCraft - Open-Source Phishing Framework

The MIT License (MIT)

Copyright (c) 2013 - 2020 Jordan Wright
Modified for PhishCraft Community Edition

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software ("PhishCraft Community Edition") and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
