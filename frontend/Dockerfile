FROM nginx:alpine
 
COPY dist/ /usr/share/nginx/html
 
RUN chmod -R 755 /usr/share/nginx/html
 
COPY dist/default.conf /etc/nginx/conf.d/default.conf
 
EXPOSE 80
 
CMD ["nginx", "-g", "daemon off;"]
