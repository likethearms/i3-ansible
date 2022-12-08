## Usage

```
su -
apt install ansible
git clone https://github.com/likethearms/i3-ansible
cd i3-ansible
ansible-playbook i3-playbook.yml
adduser <name> sudo

# Setup Hyper-V extensions
# Install XRDP and XORGXRDP
git clone https://github.com/Hinara/linux-vm-tools
cd ubuntu/xx.xx
chmod +x install.sh
./install.sh

shutdown
```

Windows hyper-v configurations
```powershell
# Get host session mode
Get-VMHost | select Name, EnableEnhancedSessionMode

# Enable if required
Set-VMHost -EnableEnhancedSessionMode $true

# Turn vm enchanted session on
Set-VM -VMName <Name-of-VM> -EnhancedSessionTransportType HvSocket
```


## Configs

```sh
# Branch
curl https://gist.githubusercontent.com/likethearms/03cf754a4d50c70fb6ecb0eb0f586fa2/raw/0c5a786027b27e27a1ccaf84dcaad036bdb1845e/branch-bash.sh

# Terminator
mkdir -p ~/.config/terminator && wget -O ~/.config/terminator/config https://gist.githubusercontent.com/likethearms/d7db5e52216d2c1c0e816bd00e84aaa5/raw/1d292151a6c60926e01723a2c2d450df72776d92/terminator-config

# VSCode
mkdir -p ~/.config/Code/User && wget -O ~/.config/Code/User/settings.json https://gist.githubusercontent.com/likethearms/a18c1ac034e5856a610bd2ce411c2409/raw/e958f57b37975cc907eb3dffc127c9fcbe2417b3/vscode-config.json
```
