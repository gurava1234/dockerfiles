FROM almalinux:8
RUN yum install nginx -y
ENV  TRAINING="DEVOPS" \
     LEARNER="guru" \
     DURATION="120HRS"
CMD ["nginx","-g","daemon off;"]