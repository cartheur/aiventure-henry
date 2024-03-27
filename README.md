[![GitHub issues](https://img.shields.io/github/issues/cartheur/henry)](https://github.com/cartheur/henry/issues)

# henry

An implementation of animals where an aeon is hosted inside a toy bear. This version is python dummy control of a set of face motors: One for the blinking of the eyes and one for the movement of the mouth. It is designed to leverage the hardware (the bear itself) of a method of control called "puppeteering" where, in a nutshell, the running python code has an API (bottle server) that will take lines of text at an IP address where it will vocalize the response.

The aiventure folder contains the NetCore development version based on aeon AGI. It is in SDK 8.0. Development will be done in a separate working folder then brought over once ready.

## Project log

* 27.03.2024
    - 2005: Brought the henry bear online and noticed this in the ssh connection: `Last login: Fri Mar 24 16:03:46 2023 from 192.168.1.101`.