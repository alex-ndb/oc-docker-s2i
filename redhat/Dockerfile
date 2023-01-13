# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

# CMD ["/bin/bash", "-c", "sleep infinity"]
#CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
RUN yum update -y && yum install httpd && yum clean all
CMD ["/sbin/init"]
