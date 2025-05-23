# hoa12


TASK [Gathering Facts] *********************************************************
[WARNING]: Platform linux on host mn1 is using the discovered Python
interpreter at /usr/bin/python3.13, but future installation of another Python
interpreter could change the meaning of that path. See
https://docs.ansible.com/ansible-
core/2.18/reference_appendices/interpreter_discovery.html for more information.
ok: [mn1]

TASK [Perform full patching] ***************************************************
ok: [mn1]

TASK [Add admin group] *********************************************************
changed: [mn1]

TASK [Add local user] **********************************************************
changed: [mn1]

TASK [Add SSH public key for user] *********************************************
changed: [mn1]

TASK [Add sudoer rule for local user] ******************************************
changed: [mn1]

TASK [Add hardened SSH config] *************************************************
changed: [mn1]

TASK [Add SSH port to internal zone] *******************************************
fatal: [mn1]: FAILED! => {"changed": false, "msg": "Failed to import the required Python library (firewall) on mn1's Python /usr/bin/python3.13. Please read the module documentation and install it in the appropriate location. If the required library is installed, but Ansible is using the wrong Python interpreter, please consult the documentation on ansible_python_interpreter. Version 0.2.11 or newer required (0.3.9 or newer for offline operations)"}

PLAY RECAP *********************************************************************
mn1                        : ok=7    changed=5    unreachable=0    failed=1    skipped=0    rescued=0    ignored=0   

qfmgayao@workstation:~/activities/hoa12$ 
