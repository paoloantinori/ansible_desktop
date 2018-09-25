# Fedora - Ansible Contrib Repository

based on https://github.com/fabaff/fedora-ansible

```
ansible-playbook --check --become --ask-become-pass main.yml
```
Companion rsync invocation for personal files:

```
rsync  --progress --del --exclude-from=rsync_exclude.cfg -vrAXzEh  klimt:/home/pantinor ~
```
