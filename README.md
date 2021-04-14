# Imersion Full Stack Full Cycle 2

This is the repo of an app made to study the use of Docker, Kubernetes, Apache Kafka, Elasticsearch, Kibana, microservices with Nest.js, React with websockets and geolocation.

## Configure /etc/hosts

The communication between apps is done directly through the machine's network.
To achieve that an address that all docker containers can access needs to set up.

Add this at the end of your `/etc/hosts` (on Windows is `C:\Windows\system32\drivers\etc\hosts`):

```
127.0.0.1 host.docker.internal
```

Edit the _hosts_ file as Administrator or root.

## Running the app

Each project has its own `README.md` showing how it can be executed.
