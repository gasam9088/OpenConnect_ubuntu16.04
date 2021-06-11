# Настройка VPN сервера для приложения AnyConnect
ОС - Ubuntu16.04

VPS - macloud

## Установка
```
wget https://raw.githubusercontent.com/gasam9088/OpenConnect_ubuntu16.04/main/ocserv
sed -i -e ‘s/\r$//’ ocserv
chmod +x ocserv
./ocserv
```

## Для создания/удаления аккаунтов 
```
cd /etc/ocserv
./manage.sh
```
