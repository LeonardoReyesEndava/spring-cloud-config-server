Spring Cloud Config Sever  leverages the Spring Cloud Config Server in order to introduce centralized configuration management and runtime properties reload.

## High Level Diagram
Below is a high level on how the components will pull the properties.

![High Level Diagram](./docs/diagrams/ConfigServer.drawio.png)

### Server URL
This service will run under 8888 port: http://localhost:8888

### End Point to test properties by profile
Properties can be reviewed using the next endpoints:
* Default profile: http://localhost:8888/limits-service/default
* Dev profile: http://localhost:8888/limits-service/dev
* QA profile: http://localhost:8888/limits-service/qa