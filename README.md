#This repository is archived and will no longer receive updates.

# openvm-tools-atomic-playbook
Ansible playbook for installing openvm-tools as a system container on Atomic hosts

What It Does
------------

1. Downloads the openvm-tools image from registry.access.redhat.com
2. Installs the image as a system container
3. Starts the system container with `systemctl`

Based on the commands shown here: [https://developers.redhat.com/blog/2017/05/24/containerizing-open-vm-tools-part-2-atomic-cli-and-converting-to-a-systems-container/](https://developers.redhat.com/blog/2017/05/24/containerizing-open-vm-tools-part-2-atomic-cli-and-converting-to-a-systems-container/)
