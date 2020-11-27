# 04 NFS

* Результаты выполненных действий 

* Server
![результат server](https://github.com/Elijah-Fox/otus-nfs/blob/main/images/server.png)


* Client
![результат server](https://github.com/Elijah-Fox/otus-nfs/blob/main/images/client.png)


# Лог действий /log

SERVER
https://github.com/Elijah-Fox/otus-nfs/blob/main/log/server.log

CLIENT
https://github.com/Elijah-Fox/otus-nfs/blob/main/log/client.log

* для автоматического монтирования добавил строчку в /etc/fstab

192.168.10.10:/export/shared /mnt nfs auto,nofail,noatime,intr,actimeo=3600 0 0
