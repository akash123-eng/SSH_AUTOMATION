# SSH_AUTOMATION

1)To Give SSH access to New User use following command :

     ansible-playbook -i hosts -e "action=grant" playbooks/task.yml
  
2)To Revoke SSH access of a user use following command :  

     ansible-playbook -i hosts -e "action=revoke" playbooks/task.yml
