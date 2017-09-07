# SSP Development

This version of the template, deploys 1 instance of all the SSP services. This template demonstrates rancher based deployment of SSP.

> Current Template Version = 1.0

## Compatibility
* SSP uses `docker-compose` version `2.1` to do the health checks 
* `rancher-compose` as of today, does not support `docker-compose` version `2.1` - https://github.com/rancher/rancher/issues/6188
* Therefore, the rancher stack will have to be setup manually via `docker-compose`