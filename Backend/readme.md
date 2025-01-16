1}Edit context.xml file and add ip address of db-container



2}Create Docker Image

   
   docker build -t tomcat .

3}Create Docker Container


   docker run -itd --name tomcat-be -p 8080:8080 tomcat

4}You can verify using below URL


   instance-piblic-ip:8080/student
