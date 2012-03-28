#README

##How To Install

###Requirements
* Maven
* Java (v1.6+)
* A configured LDAP Server (with SSL)


###Install
* Fill in your LDAPS information in ```<agmip-cas-directory>/src/main/webapp/WEB-INF/cas-connection.properties```
* Fill in your domain information in ```<agmip-cas-directory>/src/main/webapps/WEB-INF/cas.properties```
* Run ```mvn package```
