FROM almalinux
RUN yum install nginx -y
RUN rm -rf /User/DELL/Onedrive/nginx/index.html
COPY index.html /User/DELL/Onedrive/nginx/index.html/
ADD https://raw.githubusercontent.com/Akhilsadhu-24/terraform/refs/heads/main/main.tf /User/DELL/Onedrive/nginx/index.html/
CMD ["nginx","-g","daemon off;"]