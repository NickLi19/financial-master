# Environment Init

## DataBase
### Management Module
Use `scripts/manager.sql` to create database that are needed, modified databasee configuration in `manager/src/main/resources/application.yml` 

### Sale Module
Use `scripts/seller.sql`, `scripts/seller-backup.sql` to create database that are needed, modified database configuration in `seller/src/main/resources/application.yml`

## activemq
See[activemq](http://activemq.apache.org/version-5-getting-started.html#Version5GettingStarted-InstallationProcedureforUnix) to install and start ActiveMQ, 
modified ActiveMQ configuration in `manager/src/main/resources/application.yml`、`seller/src/main/resources/application.yml`
