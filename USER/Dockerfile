FROM almalinux:9
RUN dnf install nginx -y

RUN useradd sagar
USER sagar

CMD ["nginx", "-g", "daemon off;"]