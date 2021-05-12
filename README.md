**Run this script for Renaming or for changing the File Format of the image**

**Enter "input path" and "output path" according to your need.**

**Requirements:**

Install Pillow with pip:

python3 -m pip install --upgrade pip

python3 -m pip install --upgrade Pillow

Windows Installation

We provide Pillow binaries for Windows compiled for the matrix of supported Pythons in both 32 and 64-bit versions in the wheel format. These binaries include support for all optional libraries except libimagequant and libxcb. Raqm support requires FriBiDi to be installed separately:

python3 -m pip install --upgrade pip

python3 -m pip install --upgrade Pillow

To install Pillow in MSYS2, see Building on Windows using MSYS2/MinGW.

macOS Installation

We provide binaries for macOS for each of the supported Python versions in the wheel format. These include support for all optional libraries except libimagequant. Raqm support requires FriBiDi to be installed separately:

python3 -m pip install --upgrade pip

python3 -m pip install --upgrade Pillow

Linux Installation

We provide binaries for Linux for each of the supported Python versions in the manylinux wheel format. These include support for all optional libraries except libimagequant. Raqm support requires FriBiDi to be installed separately:

python3 -m pip install --upgrade pip

python3 -m pip install --upgrade Pillow

Most major Linux distributions, including Fedora, Ubuntu and ArchLinux also include Pillow in packages that previously contained PIL e.g. python-imaging. Debian splits it into two packages, python3-pil and python3-pil.imagetk.
