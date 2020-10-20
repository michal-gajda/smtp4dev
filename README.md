# smtp4dev

    docker run -p 3000:80 -p 25:25 rnwood/smtp4dev:v3

## copy SQLite DB file from containter

    docker ps -a
    docker cp container_id:/smtp4dev/database.db database.db
