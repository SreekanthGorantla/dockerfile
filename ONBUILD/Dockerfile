FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# Onbuild command will execute if any user uses your image as their BASE OS
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]