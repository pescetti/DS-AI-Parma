![Python](https://img.shields.io/badge/python-3.5+,2.7-green.svg)
![OS](https://img.shields.io/badge/OS-Fedora-orange.svg)
[![Platform](https://img.shields.io/badge/Platform-GoogleCloudPlatform-blue.svg)](https://cloud.google.com/free/)

## Installation instructions

We assume the default (Python 2) stack. Use Virtualenv for Python 3.

### System Requirements

- Python (2.7+)
- pip
- Jupyter
- Java

```bash
$ sudo dnf install python2-pip notebook python2-notebook install java-1.8.0-openjdk-devel
```

Test your setup:

```bash
$ jupyter notebook
```

### Python requirements

- mxnet
- h2o
- tensorflow
- keras

```bash
$ sudo pip install mxnet h2o tensorflow keras
```
