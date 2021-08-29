# bitwarden_playbook
Ansible playbook for configuration Bitwarden self-hosted instance. 

1. Create your vps.
2. Configure in `inventories/host_vars/bitwarden_server`.
3. For creation encrypted variable use `ansible-vault encrypt_string "YOUR_VALUE_HERE" --name 'account_notifications_email'`  `account_notifications_email` is variable name, change other variables.
4. use `bash run.sh` for starting playbook.
