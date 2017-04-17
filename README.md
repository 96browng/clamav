# Overview
Utilises the docker setup for the UK Home Office Clamav for file scanning...
[UKHomeOffice Clamav](https://github.com/UKHomeOffice/docker-clamav)

## Setup
2x virtual machines:
1. Clamav = listening tcp/3010
2. Clamav-rest = listening tcp/8080 (spring-boot with Jetty)

A link between the containers is established so the only externalised port is tcp/8080.
