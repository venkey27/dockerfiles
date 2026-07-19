FROM almalinux

#CMD command can be overriden at the time of running container
#CMD ["ping", "yahoo.com"]

#ENTRYPOINT can't be overriden, if you try to do it will go and append
#ENTRYPOINT ["ping", "yahoo.com"]


ENTRYPOINT ["ping"]
CMD ["yahoo.com"]
#CMD can be used as supplier of default args to ENTRYPOINT and we can always override those default args at run time.