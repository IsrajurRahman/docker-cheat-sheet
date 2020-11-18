# docker-cheat-sheet
Docker Commands

To **Build** a docker project
```
docker-compose build
```

To **Run** a docker project
```
docker-compose up
```

To **Stop** a docker project
```
docker-compose down
```

To show Docker **image lists**
```
docker images
```

To remove a Docker **image**
```
docker rmi <IMAGE ID>
```

To show only **running containers**
```
docker ps
```

To show **all containers**
```
docker ps -a
```

To show the **latest created container**
```
docker ps -l
```

To show the **n last created containers**
```
docker ps -n=-1
```

To display **total file sizes**
```
docker ps -s
```

To **remove all containers** that are NOT running
```
docker rm `docker ps -aq -f status=exited`
```

To **Run Django** commands on docker project 
```
docker-compose run idareengine sh -c "python manage.py createsuperuser"
```
