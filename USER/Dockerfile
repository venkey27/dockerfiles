FROM almalinux
RUN useradd roboshop
RUN dnf install nginx -y

#from here the container will run with normal roboshop access not root access
#the roboshop user cannot do any installations inside the container and dont get any host access 
USER roboshop
CMD ["sleep", "100"]

