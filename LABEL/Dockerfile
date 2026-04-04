FROM redhat/ubi9
RUN dnf install nginx -y
LABEL course = "Docker" \
      TRAINER = "Nagababu"  
CMD ["nginx","-g","daemon off;"]