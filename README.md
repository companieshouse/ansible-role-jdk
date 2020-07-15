Ansible Role: jdk
==================

An ansible role for installing openjdk.

Branch Approach
------------

We have opted to use the branch approach in determining the version of Java you need to install as a galaxy role

Example Requirements File
----------------

The version is the Github branch name which indicates the version of Java you require for your project
```
- src: https://github.com/companieshouse/ansible-role-jdk
  name: ansible-role-jdk
  version: "java8"
```  
