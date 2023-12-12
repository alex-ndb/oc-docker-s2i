# simple dockerfile to test OCP s2i using Dockerfile 
# Updated in December 2023

#FROM registry.access.redhat.com/ubi9-init:latest

# CMD ["/bin/bash", "-c", "sleep infinity"]
#CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
#RUN yum update -y && yum install httpd -y && yum clean all
#RUN systemctl enable httpd
#CMD ["/sbin/init"]
#Original BIELCO



# simple dockerfile to test OCP s2i using Dockerfile 
# Updated in December 2023

FROM registry.access.redhat.com/ubi7:latest

## This was original
# CMD ["/bin/bash", "-c", "sleep infinity"] 

## And this is edited
CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
