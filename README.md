# HowTo
## Build
$ mvn install

## Run
$ mvn spring-boot:run

## Kill port
$ sudo kill `sudo lsof -t -i:8080`

## Check port
$ lsof -i :8080

## Run MySQL DBS
$ docker run --name recipe-mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=recipe-db-root-pw -d mysql:8.0


## Reference
https://medium.com/@benjaminliu_42474/how-to-setup-spring-boot-with-reactjs-and-webpack-9b190edeb0c8
