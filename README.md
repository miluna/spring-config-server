# Spring Config Server
This Config Server can be used by multiple Spring projects by linking all of them to a Git Repository with all the .yml configuration files

## application.yml
```yml
#CONFIG SERVER
spring:
  cloud:
    config:
      server:
        git:
          uri: {YOUR GIT REPOSITORY}

```
