# Ansible script for deploy datadog agent 

https://www.datadoghq.com/

https://github.com/DataDog/ansible-datadog

Deploy agent:
    
    ansible-galaxy install datadog.datadog
    ansible-playbook -D -l server1,server2 -e "datadog_api_key=xyzxyzxyzxyzxyzxyzxyzxyzxyzxyz" ./datadoghq.yml
