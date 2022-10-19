FROM nginx:latest


COPY ./ssl/localhost.crt /etc/ssl/certs/localhost.crt
COPY ./ssl/localhost.key /etc/ssl/private/localhost.key



EXPOSE 80

STOPSIGNAL SIGQUIT

CMD ["nginx", "-g", "daemon off;"]
