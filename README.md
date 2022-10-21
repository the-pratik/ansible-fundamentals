<img src="https://img.shields.io/badge/Ansible-000000?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible" />
<h1>Ansible Fundamentals</h1>

<h3># To run a particular playbook file use the below command:</h3>

1. To create, delete folder and file using `playbook.yml` <br><i>`ansible-playbook -i hosts playbook.yml`</i>

2. To uninstall and install vim using `playbook_apt.yml` <br><i>`ansible-playbook -i hosts playbook_apt.yml`</i>

3. To compress, copy and find archive using `playbook_file.yml` <br><i>`ansible-playbook -i hosts playbook_file.yml`</i>

<h3># For nginx on local machine:</h3>

Run `ansible-playbook nginx.yml`

<h3># For ping module:</h3>

1. Using Playbook <br>
   Run `ansible-playbook -i portfolio ping_pong.yml --connection=local`
   
2. Without Playbook <br>
   Run `ansible all -i portfolio -m ping --connection=local`
   
<h6>Note: -i is used to specify custom inventory of hosts</h6>
