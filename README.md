# Yessos_microservices
Yessos microservices repository

# Docker
Reddit App was put into docker container, uploaded to Docker Hub and deployed to GCP.
Reddit App was separated into microserices inside 4 docker containers for mongodb, ui, posts and comments
Project configured through docker-compose.yml. Network separated into front and back. Project prefix can be changed with -p flag.

# Monitoring
- Prometheus monitoring added to Reddit App
- Container uploaded to Docker Hub user iakrevetko
- Graphs added to cadvisor and Graphana
- App metrics and buisness-logic metrics added
- Alerting added with alertmanager and integrated into Slack

# Logging
- Unstructured log clollection added to Reddit App
- Visualization added with kibana
- Structured log collection configured in fluentd
- Tracing added with Zipkin

# Kubernetes
- Kubernetes THW completed
- Reddit deployed to GKE: https://ibb.co/c8qstZk
- LoadBalancer Configured
- Ingress configured
- Ingress switched to HTTPS
- Network policies deployed to the cluster
- MongoDB isolated with netowrk plicies
- Persistent Volumes created for Mongo
- Persistent Volume Claims created for Mongo
- Dynamic Persistent Volume Claims created for Mongo
