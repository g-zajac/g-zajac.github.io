# Introduction to Skycharge SDK

Skycharge Software Development Kit is a set of tools and open-source software for developers. Skycharge SDK supports C programming language and all Skycharge tools are based on the comprehensive charging API that allows full control of the Skycharge system.

Icon test
<i class="fa-light fa-note"></i>

**Note**
Skycharge SDK is open source and published under the BSD-3 license. Developers can integrate the existing Skycharge services and create their own. The Skycharge git repository can be accessed here: https://github.com/Skycharge/libskycharge

The present documentation describes how to get started with the Skycharge SDK to test, monitor, and control your Skycharge systems.

## Software package

1. skycharge-conf – Skycharge system configuration file
2. skycharged – Linux daemon installed on the system Linux board. Skycharged allows users to manage, monitor and control the Skycharge systems remotely.
3. skycharge-cli – Linux client for skycharged installed on the system. Used to launch commands to manage and monitor the system. skycharge-cli is compiled for Linux Debian 9.1 (codename "stretch") and thus it can be optionally installed on the User computer.

[!LATEST SOFTWARE PACKAGE]

LATEST SOFTWARE PACKAGE
The latest software packages are managed by debian package manager, thus the up-to-date version can be always installed on the system by executing the following commands:
```bash
$ apt update
$ apt install skycharge-conf skycharged skycharge-cli
```
The debian repository of all Skycharge packages is available here: http://install.skycharge.de/debian/


