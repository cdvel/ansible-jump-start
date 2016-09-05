#Ansible Jump Start


A template for new Ansible projects.


##File Structure

```
├── Readme.md
├── ansible.cfg
├── host_vars
├── inventories
│   ├── hosts
│   ├── production
│   │   └── group_vars
│   └── staging
│       └── group_vars
├── playbooks
│   ├── common.yml
│   └── roles
│       └── common
│           ├── defaults
│           │   └── main.yml
│           ├── files
│           │   └── main.yml
│           ├── handlers
│           │   └── main.yml
│           ├── meta
│           │   └── main.yml
│           ├── tasks
│           │   └── main.yml
│           ├── templates
│           │   └── main.conf.j2
│           └── vars
│               └── main.yml
├── production
├── requirements.yml
├── roles.yml
└── staging

```
