# Wireguard Installation for Debian 11 Bullseye

Remove the `_example` of the inventory and secrets file. Also fill them with your data.

Then run this to setup the wireguard easy:
```shell
python3 -m pip install --user ansible
ansible-playbook -i inventory.yml playbook-deploy-django.yml
```