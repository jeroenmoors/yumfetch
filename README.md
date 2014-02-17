yumfetch
========

A minimalistic yum implementation in php for non-yum systems. 

Usage
-----
This script can be used to install RPM packages from a yum repository on non-yum systems (Debian, Ubuntu,...)

```
Usage: yumfetch <parameter> [package] [version]
	install	Fetches and extract the requested package
	latest	Install the latest version of the requested package
	list	List all available packages
	status	Show the current installed packages and their status
	help	This message
```

Features
--------
- list all packages available on a yum repository
- install a RPM package from a repository
- ensure the latests version of a package is installed
- use ssl client certificates to authenticate to the repository server
