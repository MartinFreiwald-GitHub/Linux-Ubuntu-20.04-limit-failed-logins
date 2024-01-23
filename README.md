# Linux-Ubuntu-20.04-limit-failed-logins
Using Apache2 server &amp; Open SSL 1.1.1 along with PAM faillock file to stop brute force login attacks

Use my installation of Linux Ubuntu Apache2 & Open SSL 1.1.1 along with firewall installation on my github account before your start using these files.

First start with, making a copy of both the files /etc/security/faillock.conf and /etc/pam.d/login.  Save these copies in the same directory location for ease of use.  
You can use these copies to start over if you screw up the file changing it.

Use the configuring PAM faillock file as a guide to configure the /etc/security/faillock.conf file.  Info for this file found at https://manpages.ubuntu.com/manpages/jammy/man5/faillock.conf.5.html
