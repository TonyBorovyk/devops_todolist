Link to my personal Docker Hub:
https://hub.docker.com/repositories/antonborovyk2001

App image link:
https://hub.docker.com/repository/docker/antonborovyk2001/todoapp-py/tags/latest/sha256-7fec641063c64f82f01135710eb3ed99dafa424bb8930d180c7e1bd8f2024fdc

Command for building an image:
docker build -t todoapp:1.0.0 .

Command to start a container:
docker run -p 8000:8080 todoapp:1.0.0

Browser access link:
http://localhost:8000/