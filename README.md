# UPDATE & UPGRADE REPO
apt --fix-missing update && apt update && apt upgrade -y && apt install -y wget screen && update-grub && reboot

# Copy Paste ke vps & pastikan memiliki domain aktif
wget -q https://raw.githubusercontent.com/adminssh580808/aioxray/main/setup.sh && chmod +x setup.sh && ./setup.sh
