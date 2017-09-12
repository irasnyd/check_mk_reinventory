Introduction
============

A set of scripts to automatically add newly discovered services to a
[Nagios](https://www.nagios.org/) and [Check\_MK](http://mathias-kettner.com/check_mk.html)
monitoring service installation.

This allows a the monitoring service to automatically begin monitoring
any new services which are added to your infrastructure, without any
human intervention.

Installation
============

These scripts were designed to work on CentOS 7, using the packages provided within
the distribution and EPEL repositories. If you are using a different operating system
distribution, some of the paths may need to be adjusted.

All scripts are designed to be installed into `/etc/check_mk/scripts/`.

You should arrange for `/etc/check_mk/scripts/check_mk_reinventory` to be run
by cron at a convenient interval.
