FROM almalinux:9

#RUN cd /tmp -- this cd /tmp wont work. only WORKDIR /app will work and present working directory will be /app
RUN cd /tmp

RUN mkdir /app
#used to move to another directory inside docker image
WORKDIR /app
RUN echo "present working directory ${PWD}"
CMD ["sleep", "100"]