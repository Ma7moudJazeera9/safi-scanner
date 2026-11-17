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
| pikepdf | MPL-2.0 | https://github.com/pikepdf/pikepdf |
| qpdf (bundled with pikepdf) | Apache-2.0 | https://github.com/qpdf/qpdf |
| lxml / libxml2 / libxslt | BSD-3-Clause / MIT | https://lxml.de/ |
| OpenBLAS (bundled with NumPy) | BSD-3-Clause | https://www.openblas.net/ |
| FFmpeg (bundled with OpenCV) | LGPL-2.1 | https://ffmpeg.org/ |
| shiboken6 | LGPL-3.0 | https://code.qt.io/ |
| Pydantic / pydantic-core | MIT | https://github.com/pydantic/pydantic |
| httptools, watchfiles, PyYAML, setuptools | MIT | https://pypi.org/ |
| websockets, click | BSD-3-Clause | https://pypi.org/ |
| opentelemetry-api | Apache-2.0 | https://github.com/open-telemetry/opentelemetry-python |

## LGPL components (Qt / PySide6 / shiboken6, FFmpeg, img2pdf)

All are used unmodified. The Qt / PySide6 / shiboken6 and FFmpeg libraries are shipped as separate files in the
installation folder (`C:\Program Files\Safi\_internal`) and may be replaced with your own
compatible builds. img2pdf is a pure-Python module included unmodified in the application
archive. The full source code of each is available from the links above. The full text of the LGPL-3.0
is available at https://www.gnu.org/licenses/lgpl-3.0.html.
