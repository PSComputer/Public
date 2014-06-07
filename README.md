Public
======

Public repository of useful code to share.

Assume everything is listed under a GPL license where no license is specified in the source code.

Feel free to provide feedback.

History
=======

2014-06-07

Added a Nagios plugin for Debian-based Linux hosts to check their running kernel is up-to-date with what is installed. i.e. it checks whether a reboot is required due to a kernel upgrade. 

The script has been written as simple as possible to keep it maintainable and adaptable by us and others. It uses dpkg to find the list of installed kernels, finds the most recent one, then compares this with the running kernel.




