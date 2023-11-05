Setup Using docker 
		
		Docker pull jenkins/jenkins	Pull the jenkins image from dockerhub
		Docker images
		Docker run -d -p 8080:8080 --name jenkins jenkins/jenkins 	Run the jenkins on using port 8080
		Docker ps 	
		
		
	Find password on this dir
			/var/jenkins_home/secrets/initialAdminPassword	/var/lib/docker/volumes/97fa4bf557c1c923da9d649ef6b0dd26a95605616fa7d44d43bc6ef7bd7512b7/_data/secrets
![image](https://github.com/Fir3eye/jenkins_Projects/assets/93431222/8a4e2830-b17b-4551-b126-f1ea1a642d14)
