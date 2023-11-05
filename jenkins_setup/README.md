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
### 🚩Go to browser and type our public IP:8080
```
$IP:8080
```
### 🚩Search this /var/jenkins_home/secrets/initialAdminPassword Password
```
# You can try on this folder, nor it can be right search own way where is present secrets
/var/lib/docker/volumes/97fa4bf557c1c923da9d649ef6b0dd26a95605616fa7d44d43bc6ef7bd7512b7/_data/secrets

```
