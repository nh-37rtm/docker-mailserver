# docker mail server

# create an account

have a look at : https://github.com/docker-mailserver/docker-mailserver/blob/master/docs/content/examples/tutorials/basic-installation.md

# create an alias
docker-compose exec -ti mailserver setup alias add postmaster@example.com user@example.com
