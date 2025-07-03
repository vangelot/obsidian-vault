Отлично! Теперь у вашего контейнера **есть IP-адрес**:  
**`192.168.50.36`** (видно в выводе команды `ip a`).

# Активировать venv и запустить бота
pct exec 101 -- /bin/bash -c "source /root/discord-bot-venv/bin/activate && python3 /root/delete_message.py"

файл конфига бота:
# Автозапуск бота при старте контейнера
lxc.hook.start: /var/lib/vz/snippets/start_bot.sh
lxc.hook.start-stop: /var/lib/vz/snippets/stop_bot.sh

# Копирование файлов

| Команда                                              | Значение                                  |
| ---------------------------------------------------- | ----------------------------------------- |
| pct push 101 /tmp/test.txt /root/test.txt            | пушит с сервера в root контейнера         |
| scp -v D:\test.txt root@192.168.50.166:/tmp/test.txt | копирует с компа на сервер (не контейнер) |
|                                                      |                                           |
