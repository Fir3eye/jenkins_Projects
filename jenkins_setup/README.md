# 📢Jenkins Setup on Docker🚀

### 🚩Search the jenkins image on dockerHub
```
sudo docker search jenkins
```
### 🚩Pull the jenkins/jenkins image
```
sudo docker pull jenkins/jenkins
```
### 🚩Run Jenkins On docker
```
sudo docker run -d -p 8080:8080 --name jenkins jenkins/jenkins
```
### 🚩Check the docker service
```
sudo docker ps -a
```
### 🚩Go to browser and type your `Server_IP` with port `8080`
```
$IP:8080
```

### 🚩Search this /var/jenkins_home/secrets/initialAdminPassword Password
** You can try on this folder, nor it can be right search own way where is present secrets **
```
 
/var/lib/docker/volumes/Your_Id_number/_data/secrets

```
