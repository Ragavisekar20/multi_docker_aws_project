Dockerized Multi-Container Application on AWS EC2

Project Name

Dockerized Multi-Container Application Deployment on AWS EC2 with persistent storage

Project Obective 

The Objective of this project is to containerize a web application using Docker and deploy it on an AWS EC2 instance using Docker Compose. Persistent storage isprovided using Amazon EBS.

Tools & Technologies Used

- Docker
- Docker Compose
- Amazon Web Services EC2
- Amazon EBS
- Nginx
- Mysql
- Git

Architecture Diagram

-User

-Browser

-AWS EC2 Instance

-Docker Compose
    -web container (Nginx)
    -Database Container (Mysql)
    -EBS Persistent Storage

Project Steps

1. Launch EC2 instance on AWS
2. Connect to EC2 using ssh
3. Install Docker
4. Install Docker Compose
5. Create aplication files
6. Create Dockerfile
7. Create docker-compose.yml
8. Run Containers
9. Attach and mount EBS Volume
10. Test application in browser 

EC2 Screenshot

/home/kiaq-lap-225/Pictures/Screenshots/EC2.png

<img width="1298" height="592" alt="EC2" src="https://github.com/user-attachments/assets/0a4260d3-1a2d-4c01-ba7e-e089aa68e41f" />


Output Screenshot

/home/kiaq-lap-225/Pictures/Screenshots/Multi-AWS.png

<img width="1298" height="592" alt="Multi-AWS" src="https://github.com/user-attachments/assets/543e75cf-cb39-4050-8c8f-ea35c4418e0f" />


Final Output

The application runs successfully inside Docker containers on AWS EC2 and is accessible through the public IP address.

http://3.108.67.238:8080


