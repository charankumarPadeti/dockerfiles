FROM almalinux:8
RUN yum install nginx -y
ENV TRAINING="DEVOPS" \
    TRAINER="Kirankumar" \
    DURATION="120HRS"
#nginx running command inside container , CMD means command prompt
CMD ["nginx","-g","daemon off;"]