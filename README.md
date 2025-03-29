# Домашнее задание к занятию «Хранение в K8s. Часть 1»

# Задание 1
Создать Deployment приложения, состоящего из двух контейнеров и обменивающихся данными.

1) Создать Deployment приложения, состоящего из контейнеров busybox и multitool.
2) Сделать так, чтобы busybox писал каждые пять секунд в некий файл в общей директории.
3) Обеспечить возможность чтения файла контейнером multitool.
4) Продемонстрировать, что multitool может читать файл, который периодоически обновляется.
5) Предоставить манифесты Deployment в решении, а также скриншоты или вывод команды из п. 4.

![1 1](https://github.com/user-attachments/assets/21238f60-fc4f-469d-bc87-772195bc20ad)

![1 2](https://github.com/user-attachments/assets/024201ef-867c-42ea-b4f4-5b435eb18d8c)

![1 3](https://github.com/user-attachments/assets/8f8feede-7aeb-4856-9cf8-9a6af6580c88)

![1 4](https://github.com/user-attachments/assets/6be8b1c3-c767-4b57-832f-d3c649192dd6)


# Задание 2
Создать DaemonSet приложения, которое может прочитать логи ноды.

1) Создать DaemonSet приложения, состоящего из multitool.
2) Обеспечить возможность чтения файла /var/log/syslog кластера MicroK8S.
3) Продемонстрировать возможность чтения файла изнутри пода.
4) Предоставить манифесты Deployment, а также скриншоты или вывод команды из п. 2.
 
![2 1](https://github.com/user-attachments/assets/1ffb0c26-ef22-4848-9147-2073805d4d00)

![2 2](https://github.com/user-attachments/assets/7957da55-dbc3-4023-8915-16451c9dee34)

![2 3](https://github.com/user-attachments/assets/8e07ef3e-cc91-4b3b-8483-e790a06a9c74)
