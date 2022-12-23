# Java EE Modernization Story - Containerization and Jakarta 10

[![Maven Build](https://github.com/ozimakov-rh/jee-container-app/actions/workflows/default.yaml/badge.svg)](https://github.com/ozimakov-rh/jee-container-app/actions/workflows/default.yaml)

* Java 17
* Jakarta 10
* H2 (managed by application server)
* OpenID Connect

Build container with `./mvnw -Pwildfly-build package`

SSO configuration at `oidc.json` files located at `user-webapp`, `admin-webapp`, and `integration` modules.

Access web application
* http://localhost:8080/user-webapp
* http://localhost:8080/admin-webapp
