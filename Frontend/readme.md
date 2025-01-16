1}Edit index.html file and add backend URL

2}Create Docker Image
    docker build -t apache .
    
3}Create Docker Container
    docker run -itd --name apache-fe -p 80:80 apache

4}Go to browser add public ip of instance you will see following Output
    ![Screenshot (2)](https://github.com/user-attachments/assets/ecd80266-35dc-48df-ba85-2814b9b599f8)

   
