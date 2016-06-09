# ansible_workshop

### NOTE: Password for vagrant box is 'vagrant'


#### 1: Create ansible user as root user
```
ansible-playbook -i inventories/dev.inv site.yml --user=vagrant --ask-pass
```

#### 2: Add more verbose output from ansible

```
ansible-playbook -i inventories/dev.inv site.yml --user=vagrant --ask-pass -vvvv
```

#### 3: Provision Java

```
ansible-playbook -i inventories/dev.inv site.yml --user=vagrant --ask-pass
```
