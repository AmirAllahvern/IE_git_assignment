# IE_git_assignment

# Golang - web app
Here is simple go web application.

Two web api has been implemented:
1.
![hello world](https://www.bogotobogo.com/GoLang/images/Web-Docker-Image/localhost-3000-index.png)

2.
![health check](https://www.bogotobogo.com/GoLang/images/Web-Docker-Image/localhost-3000-health-check.png)

#### Pre-install

- install [Go](https://golang.org/doc/install) , [Docker](https://docs.docker.com/engine/install/) and [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) 

- to insure you have installed successfully tools above, run these commands below:
        ```
        -   go version
        
        -   git --version

        -   docker --verion
        ```  

- also make sure you have pulled [golang docker image](https://hub.docker.com/_/golang) from [docker hub](https://hub.docker.com/)
        ```
        -   docker pull golang:alpine
        ```

#### Installation

1. Install this code on your local system
    
    1. Fork this repository (click 'Fork' button in top right corner)
    2. Clone the forked repository on your local file system
    
        ```
        -   cd /path/to/install/location
        
        -   git clone https://github.com/[your_username]/IE_git_assignment.git
        ```  

2. build Docker image and run it:
        ```
        -   docker build -t go-app-img .

        -   docker run -d -p 3333:3000 --name go-app-container go-app-img
        ```

3. Go to the browser and navigate to localhost:3333 :

![result](https://www.bogotobogo.com/GoLang/images/Web-Docker-Image/localhost-3333-index.png)
