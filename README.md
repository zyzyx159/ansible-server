ansible playbook to install server apps.

ansible-pull -U https://github.com/zyzyx159/ansible-server.git -i "$(hostname --short)," --ask-become-pass
