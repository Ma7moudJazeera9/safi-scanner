# Third-party notices

Safi is distributed as freeware (free to use and share, no warranty).
The installer bundles the following open-source components, each under its own license:

| Component | License | Source |
|---|---|---|
| Qt 6 / PySide6 (Qt for Python) | LGPL-3.0 | https://download.qt.io/official_releases/ , https://code.qt.io/ |
| Python 3.13 runtime | PSF License | https://www.python.org/ |
| NumPy | BSD-3-Clause | https://numpy.org/ |
| OpenCV (opencv-python-headless) | Apache-2.0 | https://opencv.org/ |
| Pillow | MIT-CMU (HPND) | https://python-pillow.org/ |
| img2pdf | LGPL-3.0 | https://gitlab.mister-muffin.de/josch/img2pdf |
| qrcode | BSD-3-Clause | https://github.com/lincolnloop/python-qrcode |
| FastAPI | MIT | https://github.com/fastapi/fastapi |
| Starlette | BSD-3-Clause | https://github.com/encode/starlette |
| Uvicorn | BSD-3-Clause | https://github.com/encode/uvicorn |
| python-multipart | Apache-2.0 | https://github.com/Kludex/python-multipart |
| PyInstaller bootloader | GPL-2.0 with bootloader exception | https://pyinstaller.org/ |

## LGPL components (Qt / PySide6, img2pdf)

Both are used unmodified. The Qt / PySide6 libraries are shipped as separate files in the
installation folder (`C:\Program Files\Safi\_internal`) and may be replaced with your own
compatible builds. img2pdf is a pure-Python module included unmodified in the application
archive. The full source code of both is available from the links above. The full text of the LGPL-3.0
is available at https://www.gnu.org/licenses/lgpl-3.0.html.
