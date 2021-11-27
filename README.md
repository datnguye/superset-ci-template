# superset-ci-template
[![SSH deployment](https://github.com/datnguye/superset-ci-template/actions/workflows/ssh-deploy-superset.yml/badge.svg)](https://github.com/datnguye/superset-ci-template/actions/workflows/ssh-deploy-superset.yml)

A workflow template to ssh deploy superset service to Ubuntu 20.04 server.

> NOTE: It doesn't include steps to preinstall the ubuntu server's dependencies e.g. python, certbot, etc


References: [Installing Superset from Scratch](https://superset.apache.org/docs/installation/installing-superset-from-scratch)


## STEPS
### 1. Checkout the source code
See [action.yml](.github/action/ssh-checkout/action.yml)

### 2. Install Superset
See [action.yml](.github/action/ssh-install-superset/action.yml)

### 3. Prepare the service file for Python
See [action.yml](.github/action/ssh-create-python-unit/action.yml)

### 4. Start service
See [action.yml](.github/action/ssh-start-service/action.yml)