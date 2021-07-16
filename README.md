# autoscaler-docker-swarm
Service to scale up and down conatiners in swarm depending on the load

It is one of the features, lack of which swarm makes k8s as a no brainer for many use cases.
Plan is to make a simple stack addon which will deployed on swarm manager and control replicas of other services based on cpu usage.

## Features

[ ] Autoscaler stack
[ ] Add support to check disc, ram and other parameters to make sure server has resources to scale up the service
[ ] Support notifications to slack, email or other custom api
[ ] Terraform support to scale up and down infra as well.
