FROM alpine:latest


# Add docker-compose-wait tool -------------------
ADD https://github.com/ufoscout/docker-compose-wait/releases/download/2.9.0/wait /wait
RUN chmod +x /wait


## Launch the wait tool and then your application
CMD /wait 
