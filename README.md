# Docker-Compose

---

Project is done on virtual machine, using VirtualBox, Debian os.

\
Setup:
- NGINX with TLSv1.2 or TLSv1.3
- WordPress + php-fpm 
- MariaDB
- A volume that contains a WordPress database
- A second volume that contains a WordPress website files
- A docker-network that establishes the connection between containers
- Redis cache for the WordPress website
- FTP server container pointing to the volume of the WordPress website
- Simple static website
- Some service

---

Usefull links:
- [Best practices for writing Dockerfiles](https://bit.ly/3QSqyka)
- 
