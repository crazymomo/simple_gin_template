# simple_gin_template

### How to start the service
Please make sure that you have installed the **docker** and **docker-compose**
```
$ docker-compose up -d
```

### How to stop the service
```
$ docker-compose down
```

### How to change the port
Open the docker-compose.yml and change the port **8080** to your wish port directly
```
$ vi docker-compose.yml
15     ports:
16       - "8080:3000"
```

### How to modify your code and see the change
The hot reload function is built-in so that the service will be auto-reload after you modify the code
