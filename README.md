# Ansible-Playbook-to-deploy-application-to-any-environments


This is an Ansible Playbook to deploy website from GitHub to both staging and production environments in AWS.

```sh
# cd /etc/ansible/roles/
# pwd
/etc/ansible/roles

# ls -l
total 0
```

```sh
# ansible-galaxy init env
- Role env was created successfully
```



```sh
# tree env
env
├── defaults
│   └── main.yml
├── files
├── handlers
│   └── main.yml
├── meta
│   └── main.yml
├── README.md
├── tasks
│   └── main.yml
├── templates
├── tests
│   ├── inventory
│   └── test.yml
└── vars
    └── main.yml
 ```



```sh
# Run a syntax check

ansible-playbook main.yml --syntax-check

# Execute the Playbook

ansible-playbook main.yml
```
