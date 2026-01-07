# CrOSSD Demo

A web-based interactive demonstration for exploring and analyzing CrOSSD project data using JupyterLite.

## Overview

This project provides an interactive Jupyter-based interface to the CrOSSD API, allowing users to explore project metrics, retrieve snapshots, and analyze software requirements. The notebook includes examples of fetching project data, querying snapshots, and visualizing project information through an embedded web interface.

## Features

- Interactive Jupyter notebooks powered by JupyterLite
- Direct integration with the CrOSSD API endpoints
- In-browser data exploration without server setup
- Access to project listings and snapshot data
- Real-time data visualization and analysis

## Browser Execution Considerations

- **CORS Proxy**: Uses `https://corsproxy.io/?url=` for bypassing cross-origin restrictions when making API requests
- **HTTP Requests**: Uses Pyodide's `pyxhr` module instead of the standard `requests` library, which is required for browser-based Python execution

## Browser Requirements

JupyterLite works with modern web browsers:

- Firefox 90+
- Chromium 89+

## Contents

- [CrOSSD.ipynb](content/CrOSSD.ipynb) - Main notebook with API examples and project analysis
- [Pipfile](content/Pipfile) - Example Pipfile for use with CrOSSD notebook
- [requirements.txt](requirements.txt) - Python dependencies for notebooks

## Getting Started

- Visit https://fh-crossd.github.io/demo
- Open the `CrOSSD.ipynb` notebook to start exploring the CrOSSD API and project data.


