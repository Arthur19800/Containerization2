# **HomeWork 5. Docker Compose и Docker Swarm**

1. Создать сервис, состоящий из 2 различных контейнеров: 1 - веб, 2 - БД (compose) 
2. Необходимо создать 3 сервиса в каждом окружении (dev, prod, lab)
3. По итогу на каждой ноде должно быть по 2 работающих контейнера
4. Выводы зафиксировать

1. Создаем директорию "compose" и переходим в неё:
   mkdir compose
   cd compose

2. В данной директории создаем файл "compose.yaml" и меняем его содиржимое:
    nano compose.yaml

    ![Alt](001.jpg)

3. Создаем сервис из 2-х контейнеров (web и db)
    
    ![Alt](002.jpg)
4. Запуск Docker Compose:
   docker-compose up -d

   Проверяем активность контейнера

   docker-compose ps

   ![Alt](003.jpg)

