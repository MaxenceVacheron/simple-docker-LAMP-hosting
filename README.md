# Basic LAMP Docker Stack


## Dependencies

### **Docker 19.03**  
#### Linux  
Install using :
```bash
$ curl -fsSL https://get.docker.com -o get-docker.sh
$ sudo sh get-docker.sh
``` 

#### Windows    
Install here : https://hub.docker.com/editions/community/docker-ce-desktop-windows/  
Docker will ask you to install this : https://docs.microsoft.com/en-us/windows/wsl/wsl2-kernel  

#### macOS    
Install here : https://docs.docker.com/desktop/mac/install/  


### **Docker-compose 1.27**  

#### Linux  
Install using :
```bash
sudo apt-get install docker-compose
```

#### Windows  
Already included in Docker for Windows

#### macOS  
Already included in Docker for macOS


## Using this template
#### On UNIX :

Copy this project:
```bash
$ git clone git@github.com:MaxenceVacheron/simple-docker-LAMP.git
```

You can then simply insert your HTML/PHP files in ```src/```.
It is advised to set the volume accordingly in the docker-compose.yml file

### You can both build and up the containers with:  
```bash
$ docker-compose up --build
```


You can now access your local service with the following ports:

- **HTTP:** 80
[Try it !](http://localhost:80)

- **PMA:** Ususally 3306 but 8080 for easy access
[Try it !](http://localhost:8080)
