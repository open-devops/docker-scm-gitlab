# docker-scm-gitlab
Software Version Control Managemnet gitlab image for Open DevOps Pipeline

#docker pull
docker pull devopsopen/docker-scm-gitlab

#docker run
docker run -d -p 9010:80 --name gitlab devopsopen/docker-scm-gitlab

#web access
http://docker-host-machine-ip:9010

PS: It may take several minutes till the gitlab login web-gui appears.
