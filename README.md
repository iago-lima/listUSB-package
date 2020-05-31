## listUSB-package
### A Debian package from a simple tool to list USB devices

In this repository, we have the source code used to generate this package. If you want to regenerate the .deb package, use the command: 

`dpkg -b listusb-debian-package` and the output is this file listusb-debian-package.deb

If you want to install the package use:

`dpkg -i listusb-debian-package.deb`

The package will be installed in /opt/listusb, to use the tool run the following command:

`/opt/listusb/./listusb` the output is something like this:

8087:8000 (bus 1, device 2) path: 1
1d6b:0002 (bus 1, device 1)
1d6b:0003 (bus 3, device 1)
04f2:b39a (bus 2, device 4) path: 8
8087:07dc (bus 2, device 3) path: 7
046d:c246 (bus 2, device 2) path: 2
1d6b:0002 (bus 2, device 1)

