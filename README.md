# 🛠️ Ansible Tasks & Mini Projects

This repository contains **5 Ansible mini-projects** that demonstrate automation use cases, configuration management, and DevOps practices.

---

## 📌 Project Overview
This repository showcases different use cases of **Ansible** for automating system administration tasks.  
Each folder represents a self-contained project with its own playbook, inventory, and supporting files.  
The projects cover topics such as:  
- Web server deployment with templates  
- Infrastructure automation using roles  
- Secure credential management with Ansible Vault  
- Using community roles from Ansible Galaxy  
- Handlers and facts for automated configuration  

---

## 🛠️ Tools & Technologies
- **Ansible** (Automation & Configuration Management)  
- **YAML** (Playbook & Config Files)  
- **Linux** (Ubuntu/Debian/RedHat Servers)  
- **Jinja2** (Templating Engine)  
- **Ansible Galaxy** (Community Roles)  
- **Ansible Vault** (Secrets Management)  

---

## 📂 Projects Structure
```
ansible-tasks-labs/
│
├── Task1_Automated_Nginx_Template/    # Nginx + Jinja2 Template for index.html
├── Task2_Infrastructure_Roles/        # Infrastructure automation with Ansible roles
├── Task3_Secure_Vault/                # Encrypted credentials with Ansible Vault
├── Task4_Galaxy_Role/                 # Using community role from Ansible Galaxy
├── Task5_Handlers_Facts/              # File management with handlers & facts
└── README.md                          # Main project documentation
```

---

## 📂 Included Projects
1. **[Task1_Automated_Nginx_Template](./Task1_Automated_Nginx_Template)**  
   Automates **Nginx installation** and deploys a **Jinja2 template** HTML page.  

2. **[Task2_Infrastructure_Roles](./Task2_Infrastructure_Roles)**  
   Uses modular **Ansible roles** to install packages, create users, and manage directories/files.  

3. **[Task3_Secure_Vault](./Task3_Secure_Vault)**  
   Secures sensitive data using **Ansible Vault** and prints values safely with `debug`.  

4. **[Task4_Galaxy_Role](./Task4_Galaxy_Role)**  
   Installs and uses a community role (`raj-pushp.nginx-custom`) from **Ansible Galaxy**.  

5. **[Task5_Handlers_Facts](./Task5_Handlers_Facts)**  
   Updates `/etc/motd` with timestamp using **Handlers** and **Ansible facts** when files change.  

---

## 🚀 How to Use
Clone the repository:
```bash
git clone https://github.com/AMD971126/ansible-tasks-labs.git
cd ansible-tasks-labs
```

Navigate to a specific task folder and run the playbook:
```bash
ansible-playbook -i inventory.ini playbook.yml
```

---

## 👤 Author
**Ahmed Mohamed Daoud**  
- IT Specialist | Network Engineer | DevOps Enthusiast  
- [LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/AMD971126)
