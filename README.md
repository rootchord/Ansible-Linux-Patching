# Ansible_Linux_Patching
Role for patching various linux OSes

## Runtime Variables
-------------------------

## For notification(Note: if no notification variables are set, the play will still run):

### If you wish to use Email

owner_email_address - address to send the notification to

### If you wish to use Authenticated Email(in addition to previous variable)
ansible_email_username 

ansible_email_password 

### If you wish to use Teams(in place of the previous 3 variables)

teams_webhook - set to full url of the teams webhook you want it to message upon completion

## Optional:

keep_version - if defined it will only update to the newest packages for the CURRENT minor version(RHEL6+ only).
