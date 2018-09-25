# docker-function

Function to help dev to use docker as simple as fuck
- docker-enter : Enter into a container (bash) by his image name
> **parameter:** search image name (ex : nginx)

# env-function

- hostadd : add a fqdn into hosts file, by default use 127.0.0.1 as IP destination
> **1st parameter:** fqdn name (ex : google.fr)
> **2ndt parameter:** destination IP (ex: 192.168.1.1) (optional)
- hostdel : remove a fqdn into hosts file
> **parameter:** fqdn name (ex : google.fr)
- mysqldumpnow : mysqldump into file and tar.gz it
> **1st parameter:** database name
> **2ndt parameter:** table name (optional)
