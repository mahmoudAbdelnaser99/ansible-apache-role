
### An Ansible role to configure and manage a basic system setup using `ansible-navigator`, including templates, files, handlers, variables, and tests.

## 🧾 Role Structure

```
mahmoud_role/
├── defaults/
│ └── main.yml # Default variables
├── files/
│ ├── ansible.jpg # Static file to be copied
│ └── index.html # Static HTML file
├── handlers/
│ └── main.yml # Handlers (e.g., restart services)
├── meta/
│ └── main.yml # Role metadata and dependencies
├── tasks/
│ └── main.yml # Main list of tasks
├── templates/
│ └── motd.j2 # Jinja2 template for MOTD
├── tests/
│ ├── inventory # Inventory file for testing
│ └── test.yml # Playbook to test the role
├── vars/
│ └── main.yml # Role-specific variables
└── README.md # Documentation
```

## ⚙️ Role Variables


```yaml
motd_message: "Welcome to my server!"
🚀 Example Usage
Run and test this role using ansible-navigator:
ansible-navigator run -m stdout playbook.yml --syntax-check
ansible-navigator run -m stdout playbook.yml
```

📦 Dependencies
Defined in meta/main.yml. Currently:
dependencies: []

```
by: Mahmoud Abdelnaser Elsayed
```
Supervisor: Dr. Anwar Fouad





