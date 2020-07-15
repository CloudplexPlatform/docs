# Eventing

Knative Eventing is a system that provides composable primitives to enable late-binding event sources and event consumers. It is a whole set of event managemnet functions to publish as well as consuming events. Knative Eventing sources publish events to broker component using HTTP POST and trigger component consumes those events based on attributes and forwards them to your application using HTTP POST. On CloudPlex, events can be delivered using following three sources.  

1. [GCP Pub/Sub](/pages/user-guide/components/eventing/gcp-pubsub/gcp-pubsub)
2. [Github](/pages/user-guide/components/eventing/github/github)
3. [Kubernetes](/pages/user-guide/components/eventing/kubernetes/kubernetes)
