1. ansible --version – Check Ansible version

2. ansible all -m ping – Ping all hosts in the
inventory

3. ansible-playbook playbook.yml – Run a playbook

4. ansible-inventory --list – Show inventory

5. ansible all -a "uptime" – Run a command on all
hosts

6. ansible-playbook -i inventory.ini playbook.yml –
Specify inventory file

7. ansible-playbook -e "variable=value" playbook.yml
– Pass extra variables

8. ansible-playbook --syntax-check playbook.yml –
Check for syntax errors

9. ansible-vault encrypt file.yml – Encrypt afile

10. ansible-vault decrypt file.yml – Decrypt afile

11. ansible-vault encrypted file create secret.yml – Create anew

12. ansible all -m setup– Gather system facts

13. ansible all -m shell-a "df -h" – Run shell commands

14. ansible all -m service -a "name=nginx state=started" – Manage services

15. ansible all -m yum -a "name=httpd state=present" – Install packages

16. ansible all -m copy -a "src=file.txt
dest=/tmp/file.txt" – Copy files

17. ansible all -m file -a "path=/tmp/test mode=0755
state=directory" – Create a directory

18. ansible-playbook -i inventory.yml site.yml --tags
web – Run specific tags

19. ansible-galaxy install role_name – Install a role

20. ansible-galaxy list – List installed roles

21. ansible-playbook -i inventory playbook.yml
--check – Run in dry-run mode

22. ansible-doc -l – List all available Ansible
modules

23. ansible-playbook -i inventory playbook.yml
--start-at-task="task_name" – Start playbook from a 
specific task

24. ansible -i inventory -m ping all – Ping all hosts

25. ansible-galaxy init myrole – Create a new Ansible
role
