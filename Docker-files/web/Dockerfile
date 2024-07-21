FROM nginx
LABEL "Project"="CICD-Jenkins"
LABEL "Author"="Shay Guedj"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf