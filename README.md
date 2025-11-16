### Домашнее задание к занятию 5. «Практическое применение Docker»
### Инструкция к выполнению:
Для выполнения заданий обязательно ознакомьтесь с инструкцией по экономии облачных ресурсов. Это нужно, чтобы не расходовать средства, полученные в результате использования промокода.
### Своё решение к задачам оформите в вашем GitHub репозитории.
### В личном кабинете отправьте на проверку ссылку на .md-файл в вашем репозитории.
### Сопроводите ответ необходимыми скриншотами.
### Примечание: Ознакомьтесь со схемой виртуального стенда по ссылке

### Задача 0.
1.Убедитесь что у вас НЕ(!) установлен docker-compose, для этого получите следующую ошибку от команды docker-compose --version.

Command 'docker-compose' not found, but can be installed with:

sudo snap install docker          # version 24.0.5, or

sudo apt  install docker-compose  # version 1.25.0-1

See 'snap info docker' for additional versions.

В случае наличия установленного в системе docker-compose - удалите его.
2. Убедитесь что у вас УСТАНОВЛЕН docker compose(без тире) версии не менее v2.24.X, для это выполните команду docker compose version.

Своё решение к задачам оформите в вашем GitHub репозитории!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

### Решение.
<img width="448" height="203" alt="Задача 0" src="https://github.com/user-attachments/assets/7217b706-f2e7-4be8-a930-441138575e2a" />

### Задача 1.
1.Сделайте в своем GitHub пространстве fork репозитория.

2.Создайте файл Dockerfile.python на основе существующего Dockerfile:

Используйте базовый образ python:3.12-slim.

Обязательно используйте конструкцию COPY . . в Dockerfile.

Создайте .dockerignore файл для исключения ненужных файлов.

Используйте CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "5000"] для запуска.

Протестируйте корректность сборки.

3.(Необязательная часть, *) Изучите инструкцию в проекте и запустите web-приложение без использования docker, с помощью venv. (Mysql БД можно запустить в docker run).

4.(Необязательная часть, *) Изучите код приложения и добавьте управление названием таблицы через ENV переменную.

### Решение.
<img width="494" height="284" alt="Задача 1(1)" src="https://github.com/user-attachments/assets/d83b7faa-e582-467a-bee2-7eede9c2d27d" />

<img width="517" height="299" alt="Задача 1(2)" src="https://github.com/user-attachments/assets/5d4db9aa-d62b-45a6-81fd-3f6c902dd3d4" />

<img width="521" height="173" alt="Задача 1(3)" src="https://github.com/user-attachments/assets/a8fea6f6-5369-4ddb-a6d2-b579e8a23d17" />

<img width="516" height="97" alt="Задача 1(4)" src="https://github.com/user-attachments/assets/6a546c94-aa40-4b73-ba3f-b19e78869f7d" />





