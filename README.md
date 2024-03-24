# Ansible Training Project
This project is a training exercise for learning Ansible. It includes a set of Ansible playbooks and roles to perform various tasks on target hosts.
The Ansible Training Project provides a hands-on learning experience for mastering Ansible automation tool. It covers various aspects of Ansible, including playbook creation, role management, task execution, and more.

## Installation
To use this project, follow these steps:
1. Clone the repository to your local machine:
git clone https://github.com/your_username/ansible-training-project.git
2. Install Ansible on your local machine. Refer to the [official Ansible documentation](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) for installation instructions.
3. Navigate to the project directory:
cd ansible-training-project


## Usage
To run the provided playbooks and roles, follow these steps:
1. Edit the inventory file (`inventory/hosts`) to specify the target hosts and their connection details.
2. Review the playbooks and roles available in the `tasks` directory.
3. Run the desired playbook using the `ansible-playbook` command:
ansible-playbook tasks/my_playbook.yml -i inventory/hosts
   
## Directory Structure
The directory structure of the project is as follows:
ansible-training-project/
├── inventory/
│ └── hosts
├── tasks/
│ ├── roles/
│ │ └── my_role/
│ │ └── tasks/
│ │ └── main.yml
│ └── my_playbook.yml
└── README.md
