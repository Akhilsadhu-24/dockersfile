FROM almalinux
RUN yum install nginx -y
RUN rm -rf /User/DELL/Onedrive/nginx/index.html
COPY index.html /User/DELL/Onedrive/nginx/index.html/
CMD ["nginx","-g","daemon off;"]