# Hyperledger Fabric with ERC-20 token

## Overview

- Hyperledger Fabric version: 2.3.1 and CA version: 1.5.0.
- There are 3 organizations in the network:
  - Org0 (Orderer Org): 3 orderers.
  - Org1: 2 peers (using CouchDB).
  - Org2: 2 peers (using CouchDB).
- There are 3 Root CAs (RCAs) for 3 organzations.
- And one TLS CA.
- Tested on CentOS 7.

## Prerequisites

The following prerequisites are required to be installed on your system before you can run all-in-one script:

- Docker.
- Docker-compose.
- jq.

## Execution

`./deploy.sh`

## Contribution

Your contribution is welcome and greatly appreciated. Please contribute your fixes and new features via a pull request.
Pull requests and proposed changes will then go through a code review and once approved will be merged into the project.

If you like my work, please leave me a star :)
