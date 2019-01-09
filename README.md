# Ansible for a new demo server

## Playbooks


1. Check syntax:
'''
ansible-playbook main.yml --syntax-check
'''

2. Check affected hosts:
'''
ansible-playbook main.yml --list-hosts
'''

3. Run:

'''
ansible-playbook -vvvv main.yml -e hosts=demo2 -u olga -c paramiko
'''


## Hosts file

```
/etc/ansible/hosts  
```

