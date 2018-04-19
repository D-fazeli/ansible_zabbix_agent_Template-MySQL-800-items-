Zabbix-agent with config Template mysql (800 item)
===

Example Inventory ==> /etc/ansible/hosts
-----------------

    [zabbix_nodes]
    your_server_hostname ansible_host=192.168.231.91 (ip_server)
 
Example Playbook
----------------   
    - hosts:
       - zabbix_nodes
    roles:
    - zabbix-agent-800item

