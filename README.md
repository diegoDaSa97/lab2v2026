[![CI/CD Pipeline](https://github.com/diegoDaSa97/lab2v2026/actions/workflows/build.yml/badge.svg)](https://github.com/diegoDaSa97/lab2v2026/actions/workflows/build.yml)

[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=diegoDaSa97_lab2v2026)](https://sonarcloud.io/summary/new_code?id=diegoDaSa97_lab2v2026)

[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=diegoDaSa97_lab2v2026&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=diegoDaSa97_lab2v2026)

[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=diegoDaSa97_lab2v2026&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=diegoDaSa97_lab2v2026)

[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=diegoDaSa97_lab2v2026&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=diegoDaSa97_lab2v2026)

# lab2v2026
Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random Aircraft
* Get application version
* health check

Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk

### Folders Structure

In the folder `src` is located the main code of the app

In the folder `test` is located the unit tests

### How to install it

Execute:

  ```shell
  $ mvnw spring-boot:run
  ```
to download the node dependencies

### How to test it

Execute:

  ```shell
  $ mvnw clean install
  ```

### How to get coverage test

Execute:

  ```shell
  $ mvwn -B package -DskipTests --file pom.xml
  ```