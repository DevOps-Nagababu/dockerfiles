FROM almalinux:9
RUN dnf install nginx -y
LABEL course = "Docker" \
      TRAINER = "Nagababu"  
EXPOSE 80
CMD ["nginx","-g","daemon off;"]