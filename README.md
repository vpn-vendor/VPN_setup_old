# VPN-Setup-Old

Этот скрипт помогает вам выполнить автоматическую настройку сервера для использования VPN конфигураций, а также легкую замену VPN через ваш собственный локальный веб-сайт. 

Скрипт тестировался на:
- Ubuntu 16.04

Работа на новых версиях убунту не является стабильной и правильной из-за обновлений, поэтому нужно использовать болеее новый скрипт для автоматической настройки на новых версиях

# Установка
Скопируйте эту комнду и следуйте инструкциям чтобы выполнить скрипт на своем оборудовании:
```bash
wget https://raw.githubusercontent.com/Rostarc/VPN_setup_old/main/server_setup.sh -O server_setup.sh && sudo bash server_setup.sh
```
# Программы
Скрипт выполняет автоматическое обновление системы и установку таких программ:
- htop
- net-tools
- dnsmasq
- network-manager
- speedtest-cli
- nload
- mtr
- wireguard
- openvpn
- apache2
- git
- iptables-persistent
- openssh-server
- resolvconf
- ufw
