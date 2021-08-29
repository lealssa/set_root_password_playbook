# set_root_password_playbook
Set a predefined, or random generated, root password on Linux hosts

## Get started
Set a predefined password

`ansible-playbook -i hosts.ini -e password="<predefined_password>" set_root_password.yaml`

If dont pass the password, it will generate one (and show to anotate)...

`ansible-playbook -i hosts.ini set_root_password.yaml`