mariadb-galera
=======================

Stands up MariaDB 10.2.11 (and Galera) on RHEL/CentOS

Role Variables
--------------

See the example inventory below...

Example Inventory ==> /etc/ansible/hosts
-----------------

  [zabbix_nodes]
    node3 ansible_host=192.168.231.103
    
            
 Example Playbook
----------------
    - hosts:
        - zabbiz_nodes
      roles:
        - zabbix-agent-800item



