Vector role
=========

Install vector in your hosts

Requirements
------------

tested only on centos 7

Role Variables
--------------

"vector_version" variables is used: 
- vector_version  
  
example
`vector_version: "0.21.1"`  
if version is not specified, latest version will be installed



Example Playbook
----------------

    - hosts: servers
      roles:
         - vector-role

