# Automated Server Configuration and Application Deployment using Ansible

## Project Overview
This project automates server configuration and application deployment using Ansible. It includes tasks such as installing Nginx, cloning a web application from GitHub, and setting up Python dependencies.

## Features
- Automates package installation on Ubuntu and CentOS.
- Configures Nginx as a reverse proxy.
- Deploys a Python-based web application from a GitHub repository.
- Ensures idempotency and reusability using Ansible roles.

## Directory Structure
Refer to the repository structure to understand the code organization.

## How to Run
1. Clone this repository to your control node.
2. Update the `inventory` file with your managed nodes' details.
3. Run the playbook:
   ```bash
   ansible-playbook playbooks/main.yml
   ```
4. Verify the application is accessible in your browser.

## Tools Used
- Ansible: Configuration management and orchestration.
- Nginx: Web server.
- Git: To fetch application code.
- Python: For backend application logic.
