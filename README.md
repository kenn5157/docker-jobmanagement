# JobManagement - Server Configurations

```This repository is purely to easely copy or re-create all configurations for our DevOps exam```

> The main **[docker-compose.yml](https://github.com/kenn5157/JobManagement-serverconf/blob/main/docker-compose.yml)** file is running as of now, MySQL container, together with flyway for migration.
Flyway exits when it's done migrating, making us able to run ```docker-compose up -d``` without being forced to shut the SQL server down first, as it will not affect the SQL server, as long as there's no changes in the service definition.
>> The sql folder include a single **[docker-compose.yml](https://github.com/kenn5157/JobManagement-serverconf/blob/main/sql/docker-compose.yml)** file, identical to the part in the main file describing the service. Stricly it's not needed, though if needed, it's already made to run the services individually.

## Sub Components

# End