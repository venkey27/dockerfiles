FROM almalinux:9   

RUN dnf install nginx -y

# exec form, Any time you see a command in a Dockerfile written inside square brackets [] and using double quotes "", it is called the exec form.
# Exec is just short for execute or executable.
CMD ["nginx", "-g","daemon off;"]