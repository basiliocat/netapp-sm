netapp-sm
=========

NetApp onCommand System Manager install scripts for CentOS

Purpose of those scripts is to install NetApp onCommand System Manager as shared web service, running from unprivileged user.

##### Requirements
- CentOS 6 i386 minimal
- epel repository

##### Install
Put downloaded file "sysmgr-setup-2-0-2-linux.rpm" in this directory and run install.sh either by pasting it line by line, or by running "bash install.txt"

##### Certificates and passwords
Web server is protected by HTTP Auth, passwords are stored in /etc/nginx/conf.d/htpasswd
By default there is user "1" with password "1".
Script also generates self-signed HTTPS certificate. You're advised to replace it with valid one (8$/year from namecheap ;)
