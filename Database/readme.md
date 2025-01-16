1}Create Docker Image

    docker build -t mysql .

2}Create Container

    docker run -itd --name mysql-db -p 3306:3306 mysql

3}Copy Container IP and add to context.xml file in Backend folder

    docker inspect <containerID>

4}Login to DB Container

     docker exec -it mysql-db  mariadb --user root -p1234
