# LDOCE5 Viewer (PySide6, Python 3, Qt6)

-----

The LDOCE5 Viewer is an alternative dictionary viewer for the Longman Dictionary of Contemporary English 5th Edition (LDOCE 5).

![image](https://cloud.githubusercontent.com/assets/15828926/24585732/efb068a4-17bb-11e7-8294-7241f73d9ed8.png)

It runs on macOS (Intel, arm), Linux and Microsoft Windows.

This software is free and open source software licensed under the terms of GPLv3.

## Linux Python 3
change default python to python3:
```bash
cd /usr/bin/ &&
sudo rm python &&
sudo ln -s python3 python
```



sudo apt install python3-pip libqt6pdfquick6 libqt6quick3d6 

sudo /usr/bin/pip3 install -r requirements.txt --break-system-packages

compile & install
```bash
make build
sudo make install
```
