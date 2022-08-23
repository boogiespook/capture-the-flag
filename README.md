CTF Setup
=========

A very simple Ansible playbook to configure a RHEL server for a 50 point CTF exercise.

Requirements
------------

It's always best to run this on a newly provisioned RHEL server as it changes repositories, firewalld and SELinux.

Execution
------
Edit your inventory file then run
```
$ ansible-playbook -i inventory tasks/main.yml
```
CAVEAT: This will change your target system so *please* only use on systems provision only for the purpose
