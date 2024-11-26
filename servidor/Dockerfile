FROM debian:12

RUN apt update && apt install -y apache2 libapache2-mod-php

EXPOSE 80
EXPOSE 443

ENTRYPOINT ["apachectl" ,"-D", "FOREGROUND"]