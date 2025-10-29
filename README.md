# ansible-ubuntu-bootstrap

Ansible playbook to bootstrap an Ubuntu host: installs Docker & Nginx, creates a `devops` user, and serves a basic page.

## Run

```bash
# edit inventory.ini with your host
ansible-playbook playbook.yml -i inventory.ini
```

You may need to provide SSH key or password with `--ask-pass` / `--private-key`.
