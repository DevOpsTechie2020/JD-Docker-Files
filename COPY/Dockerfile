FROM nginx:1.29.7
RUN rm -f /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]
COPY index.html /usr/share/nginx/html
