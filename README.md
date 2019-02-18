Root Insurance Network Admin Work Sample
========================================

Thank you for taking the time to complete our work sample.
This work sample contains some simple problems to help us evaluate your technical skills.

This work sample assumes a baseline familiarity with git and Linux.

Problem 1: Intermittent office connectivity issues!
---------------------------------------------------

Help!  Our employees are reporting that pages are intermittently not loading.
Sometimes the pages work, but other times Firefox reports 'We’re having trouble finding that site.' and Chrome reports '[the] server IP address could not be found.'

Log into the Linux client machine and troubleshoot.
Use the server IP and SSH key you were sent, username on all servers is ```ec2-user```.

Fork this repo, create a branch, and create a problem1 directory.
In this directory document your troubleshooting steps, what you found, and any steps taken to resolve the issue.

Problem 2: New Printer
----------------------

Our facilities manager is installing a new printer and it needs to be added to DNS.
This repo contains the DNS server Docker container source files.
In your branch from problem 1 modify the config files to assign 10.4.7.19 to printer4.testroot.local.

Problem 3: New VLAN
-------------------

We need another VLAN on the network.
This repo contains the config for our Zyxel firewall.
The switches are already configured with VLAN5 on the LAG, we need you to add VLAN5 to the firewall.
It is 10.0.5.0/24, should use 10.0.5.100-200 for DHCP with a 24 hour lease time, and only be allowed access to the internet.
Commit your change to the same fork and branch as problem 1.

Completing the sample
=====================

Please send us back a link to your branch which contains your commits.
Thank you!
