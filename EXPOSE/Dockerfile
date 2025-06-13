FROM almalinux:9 
RUN dnf install nginx -y
# There is no funxtionality for EXPOSE. It is just for an information. If you give wrong info then we can't do anything. make sure info should be accurate
EXPOSE 80
CMD [ "nginx", "-g", "daemon off;" ]