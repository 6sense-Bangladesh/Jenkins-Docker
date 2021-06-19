# Jenkins-Docker

You need to ensure the directory ~/jenkins exists:

`mkdir ~/jenkins`


# Run Docker Compose
`docker-compose up -d`


Jenkins is running in localhost:8081.

# First Log in
View the generated administrator password to log in the first time.

`docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword`
