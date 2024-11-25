

SHOW TABLES

select * from information_schema.tables

# Convert curl commands to Python, JavaScript and more
https://curlconverter.com/ansible/


# https://www.redhat.com/en/blog/monitor-remote-systems-ansible-jinja2
----------------------------------------------------------------------------
[defaults]
retry_files_enabled = False
timeout = 60
connection = smart
interpreter_python = auto
forks = 10
inventory = /home/vcirrus-consulting/RHCE-Ansible/inventory-gather-facts.yml
roles_path = /home/vcirrus-consulting/RHCE-Ansible/roles:/usr/share/ansible/roles
remote_user = ansible-devops
host_key_checking = False
command_warnings = False
deprecation_warnings = False
ansible_managed = Caution: This File is Managed By Ansible - DO NOT EDIT MANUALLY.

[privilege_escalation]
become = True
become_method = sudo
become_user = root
become_ask_pass = False
