# Ansible Teamcity agents configuration

## How to run
1. Install Ansible 
2. Add your ssh keys to all the agents
3. Run Ansible playbook:
    ```bash
    ansible-playbook -i hosts agents.yml
    ```
    Where hosts is a file with hostnames, one per line
    
Also check out [Ansible docs](https://docs.ansible.com/)