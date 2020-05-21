## Prepare

```
su -
apt install ansible git
git clone https://github.com/likethearms/i3-ansible
```

## Run install

```
ansible-playbook i3-playbook.yml
```

## Setup sudo

```
su -
adduser <name> sudo
reboot
```

## Post install

```
su -
cd i3-ansible
ansible-galaxy install -r requirements.yml
ansible-playbook post-install.yml
```
