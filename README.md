# autoscaler-docker-swarm
Service to scale up and down containers in swarm depending on the load.

It is one of the features, lack of which swarm makes k8s a no brainer for many use cases. The plan is to make a simple stack addon that will deploy on swarm manager and control replicas of other services based on CPU usage.

## Features

- [x] Autoscaler stack
- [ ] Add support to check disc, ram and other parameters to make sure server has resources to scale up the service
- [ ] Support notifications to slack, email or other custom api
- [ ] Terraform support to scale up and down infrastructure as well.

It is inspired from [Stack-Answer](https://stackoverflow.com/questions/41668621/how-to-configure-autoscaling-on-docker-swarm) and derived from this [repo](https://github.com/jcwimer/docker-swarm-autoscaler)
