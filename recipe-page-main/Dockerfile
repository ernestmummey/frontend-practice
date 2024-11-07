FROM nginx:latest

COPY index.html /usr/share/nginx/html/
COPY css/ /usr/share/nginx/html/
COPY  image-omelette.jpeg /usr/share/nginx/html/assets/
COPY favicon-32x32.png /usr/share/nginx/html/assets/


EXPOSE 80

CMD [ "nginx", "-g", "daemon off;" ]

