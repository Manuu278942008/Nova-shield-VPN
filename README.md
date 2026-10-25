sudo apt update && sudo apt upgrade -y
sudo apt install -y curl wget git ufw fail2ban
sudo ufw allow OpenSSH
sudo ufw allow 80/tcp
sudo ufw allow 443/tcp
sudo ufw enable
