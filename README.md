# ansible-role-nodejs

Tested only on Ubuntu 16.04

Installs Node 7.x and sets up folders at /usr/local/{{node_app_name}} and /var/log/{{node_app_name}} owned by {{node_user}}

defaults/main.yml
```
node_app_name: default
node_user: node
```
