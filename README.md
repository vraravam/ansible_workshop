# ansible_workshop

#### 1: Create ansible user as root user
```
ansible-playbook -i inventories/dev.inv site.yml --user=vagrant --ask-pass
```

#### 2: Add more verbose output from ansible

```
ansible-playbook -i inventories/dev.inv site.yml --user=vagrant --ask-pass -vvvv
```
