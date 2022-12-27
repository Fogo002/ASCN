ASCN-TP-G26

Deploy Ghost with:
ansible-playbook -i inventory/gcp.yml -e @mail_pass.enc --ask-vault-pass deploy-ghost.yml 