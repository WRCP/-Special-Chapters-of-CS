# -Special-Chapters-of-CS
Special Chapters of Computer Science
## Практическая работа 1

Установить гипервизор UTM на Mac
https://mac.getutm.app

Скачать Ubuntu Server
https://ubuntu.com/download/server

Обновить сервер
```bash
sudo apt-get update
sudo apt-get dist-upgrade
```

Установить сетевые утилиты
```bash
sudo apt inslall net-tools
```

Проверить IP-адреса и определить адрес вирутальной машины в локальной сети
```bash
sudo ifconfig
```

Установить SSH сервер (инструкция https://selectel.ru/blog/ssh-ubuntu-setup/)
```bash
sudo apt install openssh-server -y
```

Установить запуск SSH-сервера при загрузке системы
```bash
sudo systemctl enable ssh
```

Проверить вход на саму себя
```bash
ssh localhost
```

Установить metasplot
Репозиторий  https://github.com/rapid7/metasploit-framework
Инструкция https://docs.metasploit.com/docs/using-metasploit/getting-started/nightly-installers.html
Установить Metasploit на Linux / macOS 
```bash
curl https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb > msfinstall && \
  chmod 755 msfinstall && \
  ./msfinstall
```

Запустить metasplot
```bash
msfconsole
```
