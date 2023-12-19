docker exec -i soupaloignon-db-1 mariadb-dump -ubackup -pbackup_password --databases mydatabase --skip-comments > backup/dump.sql

gpg  --batch --passphrase mielgoutsandwich -c backup/dump.sql 