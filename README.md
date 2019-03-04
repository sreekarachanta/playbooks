# Playbook - useraccess.yml
____________________________________
This playbook will grant/revoke access to a user on multiple servers.

Pre-Requirements
__________________

- Ansible 2.6.13
- Python 2.7.14

Supported OS
_________________
Amazon Linux

Variables used:
______________

username - Specify the user name of the user
userpassword - Specify the password of the user

Expected result
__________________
After execution of the PLAYBOOK, the specified user will have access to the destination servers

SAMPLE OUTPUT
_________________

PLAY RECAP **********************************************************************************************************************************************************************************
172.31.19.128              : ok=1    changed=1    unreachable=0    failed=0
172.31.22.118              : ok=1    changed=1    unreachable=0    failed=0

LICENSE
_________

BSD

Author/Developer Information
_____________________________

Sreekar Achanta <sreekar.achanta07@gmail.com>


