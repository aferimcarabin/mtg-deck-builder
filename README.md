# mtg-deck-builder
IDP Project

Instructions to run db container

docker run -p 3306:3306 -p 8080:8080 --name mtgdatabase -v /storage:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=root -d aferimcarabin/mtg-deck-builder:db
