# Jupyter Lite and Xeus-lite based Speasy demo

This repository contains a demo of using [Jupyter Lite](https://jupyterlite.readthedocs.io/en/latest/) with [xeus-lite](https://github.com/jupyterlite/xeus) to run [Speasy](https://speasy.readthedocs.io/en/latest/) in the browser.

## Getting Started

Open the demo directly in your browser using [this link](https://sciqlop.github.io/Speasy-lite/) then open the demo notebook `demo.ipynb` located at the root of your Jupyter Lite file browser.
No installation is required, everything runs in your browser! 
Because it runs in the browser, some features of Speasy may be limited compared to a full Python environment. The following limitations apply:
- File system access is restricted, so local caching of data is disabled.
- HTTP requests are not allowed, so data retrieval from HTTP only online databases is not possible.
- Because of browser memory limitations, large requests may produce memory errors.
