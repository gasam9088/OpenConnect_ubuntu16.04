# Настройка VPN сервера для приложения AnyConnect
ОС - Ubuntu16.04

VPS - macloud

## Установка
```
:set fileformat=unix
wget https://raw.githubusercontent.com/gasam9088/OpenConnect_ubuntu16.04/main/ocserv
chmod +x ocserv
./ocserv
```

## Для создания/удаления аккаунтов 
```
cd /etc/ocserv
./manage.sh
```
