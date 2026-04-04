# FROM is used to mention the base os for the image
FROM redhat/ubi9
RUN dnf install nginx -y
EXPOSE 80
CMD ["nginx","-g","daemon off;"]
