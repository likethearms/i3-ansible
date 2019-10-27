## Prepare
```
su -
apt install ansible
```
## Run
```
ansible-playbook i3-playbook.yml
```
## Install virtual box guest
```
sudo mount /dev/cdrom /media/cdrom
sudo /media/cdrom/VBoxLinuxAdditions.run
reboot
```
