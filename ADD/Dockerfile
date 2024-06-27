FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /user/share/nginx/html/index.html
COPY index.html /user/share/nginx/html/ 
ADD paste the link from where you want to copy the content /tmp/
ADD sample-a.tar /tmp/
CMD ["nginx","-g","daemon off;"]
