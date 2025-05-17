# Nethunter-rootles-installer
This repo for Nethunter rootless installation 404 error solving


## Installation

```bash
# Update packages
apt update && apt upgrade -y

# Grant storage permissions
termux-setup-storage

# Install Git
apt install git -y

#install wget
pkg install wget -y

# Clone the repository
git clone https://github.com/CK-HACKS/kalirootlessdownload.git

#
cd kalirootlessdownload

#give file executive permission
chmod +x install.sh

# Start the installation
./install.sh

# password for kali:
kali


