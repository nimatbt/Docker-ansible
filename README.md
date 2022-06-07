# DevOps-Ansible Practice Project

This Ansible roles install the last version of Docker and Docker-compose in target hosts.

  ## What is Ansible?

Ansible is IaC tool for configuration management. With the aid of Ansible, we can configure a multitude of systems without direct human interactions.
Ansible is responsible for configuring existing systems, usually mutable ones.
Ansible.com for more information.

  ## what is docker?
 
Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. With Docker, you can manage your infrastructure in the same ways you manage your applications. By taking advantage of Docker’s methodologies for shipping, testing, and deploying code quickly, you can significantly reduce the delay between writing code and running it in production.

  ## Get started guide:

Ansible version: 5.2.0

1) Install python3-pip and python3-venv on your system
    ```  apt install -y python3-pip python3-venv ```
     
2) Create virtual environment(venv)
    ``` python -m venv venv ```
    
3) Install requirements package from requirements.txt

4) Run this command:
  - For normal installation
    ``` ansible-playbook -i inventory.ini playbook.yaml ```
    
  - For force update installation
    ``` ansible-playbook -i inventory.ini playbook.yaml --skip-tags "force update" ```
    
    
### Ansible Practice
- Name: Nima Tabatabaee
- Grops: Bladrina
- Practice Name: Ops-003-Ansible
- [@dwsclass](https://github.com/dwsclass) dws-ops-003-Ansible


Copyright 2022 Nima Tabatabaee <nima.tabatabaee@gmail.com>


