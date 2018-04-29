
deluge
======
[![Build Status](https://travis-ci.org/GR360RY/ansible-role-deluge.svg?branch=master)](https://travis-ci.org/GR360RY/ansible-role-deluge) [![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.deluge-green.svg)](https://galaxy.ansible.com/GR360RY/deluge/)

An Ansible role to setup and configure Deluge Daemon and Deluge-Web on Raspbian.


Requirements
------------


Overview
--------

List of tasks that will be performed under `deluge` role:

1. Install and Configure Deluge Daemon
2. Install and Configure Deluge Web Daemon
3. Create Deluge Complete and Incomplete Downloads folders
4. Configure Label and Exectute plugins if installed with `nzbtomedia` roles