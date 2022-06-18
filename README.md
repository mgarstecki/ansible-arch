# ansible-arch
Some Ansible recipes to configure an Archlinux system to my tastes

# Using

- Get dependencies: `ansible-galaxy install -r requirements.yml`
- Run the OS setup playbook as root: `ansible -i inventories/local.ini os-desktop.yml`
- Create your user, then run the user customization playbook as that user: `ansible -i inventories/local.ini user-desktop.ini`
