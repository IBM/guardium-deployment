# Guardium Deployment

This repository contains Ansible playbooks for deploying the IBM Security Guardium virtual appliance using VMware ESXi.

## Files

- `main.yml`: The main Ansible playbook for creating and configuring the Guardium virtual machine.
- `vars.yml`: A variables file to store configuration parameters.

## Prerequisites

- Ansible installed on your local machine.
- Python 3 installed on your local machine.
- VMware ESXi server with sufficient resources for the Guardium VM.
- IBM Security Guardium ISO image available in the ESXi datastore.

## Setup and Usage

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/yourusername/guardium-deployment.git
   cd guardium-deployment

2. Configure Variables:

Edit the vars.yml file to match your environment and requirements.


Run the Playbook:

Execute the main.yml playbook to deploy the Guardium virtual appliance.

sh

ansible-playbook main.yml
