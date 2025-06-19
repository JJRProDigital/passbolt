# passbolt

$ git clone https://github.com/jmlcas/passbolt
$ cd passbolt
$ docker-compose up -d

Una vez que el contenedor se esté ejecutando, cree su primer usuario administrador:

$ docker exec passbolt su -m -c "bin/cake passbolt register_user -u your@email.com -f yourname -l surname -r admin" -s /bin/sh www-data

Cambia: your@email.com - yourname y surname.
