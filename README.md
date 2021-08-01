Helm chart to deploy [Countly](https://count.ly/) on Kubernetes. Both [api](https://hub.docker.com/r/countly/api) and [frontend](https://hub.docker.com/r/countly/frontend) are contained, based on the official Countly docker images.

The chart uses the [Mongo DB helm chart by Bitnami](https://github.com/bitnami/charts/tree/master/bitnami/mongodb) to deploy the database.