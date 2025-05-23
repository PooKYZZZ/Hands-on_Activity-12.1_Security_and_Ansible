# hoa12


qfmgayao@workstation:~/activities/hoa12$ ansible-playbook main.yml --ask-become-pass
BECOME password: 

PLAY [Activity 12] *****************************************************************************************************

TASK [Gathering Facts] *************************************************************************************************
[WARNING]: Platform linux on host mn1 is using the discovered Python interpreter at /usr/bin/python3.13, but future
installation of another Python interpreter could change the meaning of that path. See https://docs.ansible.com/ansible-
core/2.18/reference_appendices/interpreter_discovery.html for more information.
ok: [mn1]

TASK [Perform full patching] *******************************************************************************************
ok: [mn1]

TASK [Add admin group] *************************************************************************************************
ok: [mn1]

TASK [Add local user] **************************************************************************************************
ok: [mn1]

TASK [Add SSH public key for user] *************************************************************************************
ok: [mn1]

TASK [Add sudoer rule for local user] **********************************************************************************
ok: [mn1]

TASK [Add hardened SSH config] *****************************************************************************************
ok: [mn1]

TASK [Add SSH port to internal zone] ***********************************************************************************
fatal: [mn1]: FAILED! => {"changed": false, "msg": "firewall is not currently running, unable to perform immediate actions without a running firewall daemon"}

PLAY RECAP *************************************************************************************************************
mn1                        : ok=7    changed=0    unreachable=0    failed=1    skipped=0    rescued=0    ignored=0   

qfmgayao@workstation:~/activities/hoa12$ 

qfmgayao@workstation:~/activities/hoa12$ 
