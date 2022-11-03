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

Sample ansible command for execution in command line.

```
ansible -i inv all -e ansible_user=centos -e ansible_password=<password> -m shell -a "netstat -tulpn"
"ansible-playbook" is used for executing ansible playbook
 ```

PS : YAML is intendation specific. 