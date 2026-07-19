FROM almalinux:9
RUN dnf install nginx -y

# expose form # just to show port number to public, who want to use your docker images, expose doesnt open port 80
EXPOSE 80

CMD ["nginx", "-g","daemon off;"]