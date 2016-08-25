#Docker Jahia Developement Environment
This is a POC and it is not supported by Jahia.

##Software Dependencies
* Docker, https://www.docker.com/products/overview
* Docker Compose, https://docs.docker.com/compose/install/

##Components
* Jahia DX, processing node
* Jahia DX, browsing node
* MySQL
* Regis
* NGINX
  * Sticky session are set up.

##How to Use
This development environment uses prebuilt images that are on the available on my docker account, https://hub.docker.com/u/sajidmomin/
* Execute: `docker-compose rm -vf && docker-compose up --remove-orphans`
* Processing node: http://localhost:9088/
* Browsing node: http://localhost:9089/
* NGINX: http://localhost
