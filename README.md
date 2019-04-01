## Introduction

# Table of contents

# Architecture
![ClearGDPR Architecture](/docs/diagram.png)
## Project structure

```
project root
├─ admin                      # Admin UI to manage the controller
├─ api                        # Code for the ClearGDPR API implementation
├─ cg                         # Code for the ClearGDPR API implementation
├─ docker                     # Helpers for docker run, stop, start.
├─ frontend                   # demo front-end integrating ClearGDPR ElementSDK
├─ packages
  ├─ js-sdk                   # Code for the ClearGDPR JS SDK implementation
  └─ element-sdk              # Code for the ClearGDPR ElementSDK implementation
├─ quorum                     # Blockchain related docker images and helper tools
├─ travis                     # Scripts used on the CI server
├─ website                    # ClearGDPR public website
```

# Requirements
- NodeJS v7.6+
- Yarn
# Quick Start

## Full Installation Setup

Once the setup is done, you will have access to:
- http://localhost:3000 - Demo Website
- http://localhost:4000 - Admin
- http://localhost:8082 - API

## Development Mode

# Integrations

## Element SDK

### Demo
Coming soon.

### Installation
Coming soon.

### Code Example
Coming soon.

## HTTP API
### Example

### Documentation
#### Website
#### Postman Collections
# Further reading
# Troubleshooting
# Roadmap

* Development deploy  
* HTTP API support for the right to consent and right to be forgotten(complete erasure)
* All events related to users data are written succesfully to the blockchain
* smart contract that stores the state of processors and controllers
* Processor run mode and controller run mode, with events propagated between nodes through the blockchain smart contract
* Example UI with registration/consent and erasure abilities
* Encryption of all personal data on CG nodes
* Robust integration test suite of CG nodes for both processor and controller mode
* Admin dashboard design + front-end code (configuration, subject & processor status)
* Automataic Quick Start script
* Interactive Quick Start wizard
* Admin dashboard hooked up to controller state via the CG api
* HTTP API support for the remaining GDPR article actions/rights
* More granular controls of consent/revoking of data (ie. which data can be shared specifically)
* End-2-End test suite of controller/processor interactions via blockchain
* SDK for implementing from your frontend
* Evolving functionalities, upgradability and security in the smart contract
* Stage/Production deploy
* Usage of custom privateFor method to whitelist nodes that are privy to specific events
* Complete documentation
* Drop in wordpress plugin
* Commercial middleware plugin(s)

# License

This project is licensed under [GNU LGPL LICENSE](LICENSE)
