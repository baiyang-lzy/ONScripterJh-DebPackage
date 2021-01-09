# ONScripterJh-DebPackage
Deb Package of ONScripter-Jh For Debian-based Distributions.

This Repository contains files for packaging, but not include the onscripter-jh binary file.

## How to use (For User)
Go [here](https://github.com/baiyang-lzy/ONScripterJh-DebPackage/releases), and download the file. 

## How to use (For Packager)

Firstly, download the binary file [here](https://www.linuxgame.cn/onscripter-jh-ons%e6%a8%a1%e6%8b%9f%e5%99%a8).

Then, clone this repository
```
git clone https://github.com/baiyang-lzy/ONScripterJh-DebPackage.git
```

Then Copy the downloaded onscripter-jh Binary file to ONScripterJh-DebPackage/onscripter-jh/usr/bin

Then chmod +x ONScripterJh-DebPackage/onscripter-jh/usr/bin/onscripter-jh

Finally, open terminal in ONScripterJh-DebPackage/ and run command "dpkg -b ./onscripter-jh/".

The Debian Package should be built at ONScripterJh-DebPackage/ 