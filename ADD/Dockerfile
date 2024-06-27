FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /user/share/nginx/html/index.html
COPY paste the link from where you want to copy the content /user/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]
