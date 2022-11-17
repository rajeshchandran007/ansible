# ansible

This repository contains all the basics and the project automation using `ansible`

What is a playbook ?

```
A Playbook is a list plays.
A Playbook can be written using YAML and all the playbooks should end with `.yml` or `.yaml` 
``` 

What is a play ?

```
A play is a list of taks ?
```

What is a task ?

```
A task can be anything that you wish to perform
```

How to execute ansible command manually?

```
ansible -i inv all -e ansible_user=centos -e ansible_password=<password> -m shell -a "netstat -tulpn"
ansible -i inv all -e ansible_user=centos -e ansible_password=<password> -m setup (This will fetch all the FACTS or System priperties)
 ```

How to execute ansible playbook?

```
ansible-playbook -i inv -e ansible_user=centos -e ansible_password=<password> 01-sample.yaml
ansible-playbook -i inv -e ansible_user=centos -e ansible_password=DevOps321 08-tags.yaml -t web (web is the tag name mentioned inside the ansible playbook)
```

How to execute ansible pull?

```
ansible-pull -U https://github.com/b51-clouddevops/ansible.git -e ansible_user=centos -e ansible_password=xxxxxx -e COMPONENT=mongodb roboshop-pull.yml
```

Branch testing 2


PS : YAML is intendation specific. 