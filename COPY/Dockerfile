FROM nginx

#used to copy files from local to image.
# removing the default cotent  /usr/share/nginx/html/*
RUN rm -rf /usr/share/nginx/html/*

# copying the qi file into /usr/share/nginx/html/ location
COPY qi/ /usr/share/nginx/html/
