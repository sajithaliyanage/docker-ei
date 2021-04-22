# Changelog

All notable changes to this project `7.1.x` per each release will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [v7.1.0.4] - 2021-02-19
### Changed
- Upgrade the base version of images to adoptopenjdk/openjdk11:jdk-11.0.10_9

## [v7.1.0.3] - 2020-11-23
### Changed
- Upgrade base Docker images to jdk-11.0.9_11

For detailed information on the tasks carried out during this release, please see the GitHub milestone
[v7.1.0.3](https://github.com/wso2/docker-ei/milestone/21).

## [v7.1.0.2] - 2020-10-09

### Added
- Adding the Docker Source Git Release Tag Version to Image Metadata. (refer to [issue](https://github.com/wso2/docker-ei/issues/207))
### Fixed
- Download product pack from Github. (refer to [issue](https://github.com/wso2/docker-ei/issues/208)) 
- Enable SSL verification for wget. (refer to [issue](https://github.com/wso2/docker-ei/issues/206)) 
- Unable to pass parameters for server startup script. (refer to [issue](https://github.com/wso2/docker-ei/issues/229)) 

For detailed information on the tasks carried out during this release, please see the GitHub milestone
[v7.1.0.2](https://github.com/wso2/docker-ei/milestone/15).

## [v7.1.0.1] - 2020-08-18

### Added
- Alpine, CentOS and Ubuntu based Docker resources WSO2 Integration v7.1.x product profiles (Micro Integrator,
 Streaming Integrator, Micro Integrator Monitoring Dashboard and Analytics Dashboard)
### Changed
- Upgrade AdoptOpenJDK 11 version to the latest version - 11.0.8_10-jdk
### Removed
- Avoid packaging the MySQL JDBC connector

For detailed information on the tasks carried out during this release, please see the GitHub milestone
[v7.1.0.1](https://github.com/wso2/docker-ei/milestone/14).

[v7.1.0.3]: https://github.com/wso2/docker-ei/compare/v7.1.0.2...v7.1.0.3
[v7.1.0.2]: https://github.com/wso2/docker-ei/compare/v7.1.0.1...v7.1.0.2
[v7.1.0.1]: https://github.com/wso2/docker-ei/compare/v7.0.0.3...v7.1.0.1
