# rancherosservices
rancheros services for the klouds stack, all relying on RancherOS' ability to run docker containers as services using a docker-compose.yml format.  Add the label

labels:
  - io.rancher.os.scope=system
 
If you want this to run on system docker, instead of the "userspace" docker.  


####if you're like ?!  here's a quick update:  RancherOS has 2 docker engines in it:

#####1) System Docker

system-docker ps (shows you system services)

#####2) User Docker

docker ps (shows you your usual docker containers)



