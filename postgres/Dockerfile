# Задаем базовый образ
FROM postgres:13

# Устанавливаем переменные окружения для PostgreSQL
ENV POSTGRES_USER=program
ENV POSTGRES_PASSWORD=test
ENV POSTGRES_DB=todo_list

# Задаем точку монтирования для данных PostgreSQL
VOLUME /var/lib/postgresql/data

# Указываем рабочий каталог
WORKDIR /var/lib/postgresql/data

# Порт по умолчанию для PostgreSQL
EXPOSE 5432

# Команда запуска контейнера
CMD ["postgres"]

