
---

## 🧩 **5️⃣ ansible-ubuntu-bootstrap**
```markdown
# Ansible Ubuntu Bootstrap

An **Ansible playbook** to bootstrap and configure a fresh Ubuntu server:  
- Installs Docker and Nginx  
- Creates a `devops` user  
- Sets up a sample web page

---

## 🧱 Inventory Example
```ini
[web]
your_server ansible_host=1.2.3.4 ansible_user=ubuntu
