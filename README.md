# Holapython
This is a small program that throws a hello world from python

## This is the results
<p align="center">
    <img src="./img/img1.png" alt="Hello from python">
</p>

## How to use
### Pre-requisites

* Python 13.13.0
* Visual Code

### Run local
Clone the repository
 
 ```
 git clone https://github.com/FranchescoAC/holapython.git
```

* Once the project has been cloned, you must open it with the visual code editor.
* After run app.py with the comand "python app.py" .
* After opening your localhost on port 8080.
## This is the results
<p align="center">
    <img src="./img/img1.png" alt="Hello from python">
</p>

## How to run in docker
### Pre-requisites

* Docker - DockerDesktop installed
* DockerHub account

### Download image
* Open the visual code terminal and enter the following code
```
docker pull franchescoac/holapython
```
### Run image
* In the same terminal, enter the following command line
```
docker run --name <NEWCONTAINERNAME> -d -p 6060:5000 <IMAGENAME>
```
* In which "NEWCONTAINERNAME" is the name of the container to be named and "IMAGENAME" is the image to be created
```
Example:  docker run -d --name holapythonc -p 6060:5000 holapython
```
### View the results
Open new window browser and search "localhost:6060"

### Link RAILWAY
* Use this link to see the program running on 
## This is the results
<p align="center">
    <img src="./img/img2.png" alt="Hello from python">
</p>

RAILWAY
```
holapython-production.up.railway.app
```