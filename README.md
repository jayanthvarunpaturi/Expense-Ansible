# 💸 Expense Tracker – Ansible Deployment

A lightweight command-line expense tracker application, automated using **Ansible** for quick and consistent deployment.

---

## 📦 Project Overview

This project demonstrates:
- A simple shell-based expense tracker
- Ansible-based automation for deployment/setup
- Configuration of required permissions and dependencies

---

## ⚙️ Technologies Used

- 🐧 Shell Script (Bash)
- ⚙️ Ansible (Provisioning & Automation)
- 🧾 YAML (Playbook Configuration)

---

## 🚀 How to Run

### 🔧 Prerequisites
- Ansible installed on the control machine
- SSH access to target host(s)
- Python installed on the target system

### 📂 Directory Structure

expense-tracker-ansible/
├── playbook.yml
├── inventory.ini
├── roles/
│ └── tracker/
│ ├── tasks/
│ │ └── main.yml
│ └── files/
│ └── tracker.sh


### ▶️ Run the Playbook

```bash
ansible-playbook -i inventory.ini playbook.yml
