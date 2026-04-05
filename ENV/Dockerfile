FROM almalinux:9
RUN dnf install nginx -y
LABEL course = "Docker" \
      TRAINER = "Nagababu"  
ENV MONGO_URL = "mongodb-dev.nagababu.online" \
    MONGO_USER = "admin"

CMD ["nginx","-g","daemon off;"]