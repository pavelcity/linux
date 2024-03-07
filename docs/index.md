[На главную](/){ .md-button }
##
# Linux
Установка программ / пакетов / полезные команды

### Обновляем спис­ки пакетов / обновление всех установленных пакетов до их последних версий
```
sudo apt update
```
```
sudo apt upgrade
```

---

## Установка программ

### MCeditor
```
apt install mc
```

### Nginx
```
sudo apt install nginx
```

* Добавление Nginx в автозагрузку:
```
sudo systemctl enable nginx
```
* Проверка статуса работы веб-сервера:
```
sudo service nginx status
```

## Commands
получение списка ранее выполненных команд
```
history
```
переменные окружения
```
env
```
узнать имя пользователя

```
echo $USER
```

