Ansible Role: NOIA NETWORK node
=========

An Ansible Role that installs NOIA NETWORK node on RHEL/CentOS.


How to run
----------------

    ansible-playbook -l HOST_NAME noia-node.yml  
    
Also, you can pass your Airdrop waller address as a variable:  

    ansible-playbook -l HOST_NAME noia-node.yml  -e "airdrop_address=YOUR_ETH_ADDRESS"
    
    

License
-------

MIT / BSD


