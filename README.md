Сборка и запуск контейнера:

docker build . --tag=task_2

docker run -d -p 8888:8000 task_2

Проверка:

curl localhost:8888
