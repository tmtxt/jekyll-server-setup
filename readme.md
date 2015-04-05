# Setup Jekyll server on Ubuntu 14.04 using rvm

- Install Ansible on server
- Clone the project
- Do a local provisioning, (use extra_vars if you want to override anything)

```
ansible-playbook -i localhost, -c local -e "@/path/to/extra_vars.yml" -K /path/to/clojure-web-skeleton/ansible/main.yml
```
