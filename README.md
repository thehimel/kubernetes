# Kubernetes

- **K8s is an open-source system for automating DSM of containerized apps.**
  - DSM = deployment, scaling, and management.
- It groups containers that make up an app into logical units for easy management and discovery.
- Planet Scale: Designed on the same principles that allows Google to run billions of containers a week,
  K8s can scale without increasing your ops team.
- Never Outgrow: Whether testing locally or running a global enterprise, Kubernetes flexibility grows with you to
deliver your applications consistently and easily no matter how complex your need is.
- Run K8s Anywhere: Kubernetes is open source giving you the freedom to take advantage of on-premises, hybrid,
or public cloud infrastructure, letting you effortlessly move workloads to where it matters to you.
- Source: [kubernetes.io](https://kubernetes.io/)


## Kubernetes Features

- Automated rollouts and rollbacks
  - K8s progressively rolls out changes to your app or its configuration, while monitoring app health to ensure
  it doesn't kill all your instances at the same time.
  - If something goes wrong, K8s will rollback the change for you.
  - Take advantage of a growing ecosystem of deployment solutions.
- Service discovery and load balancing
  - No need to modify your app to use an unfamiliar service discovery mechanism.
  - K8s gives Pods their own IP addresses and a single DNS name for a set of Pods, and can load-balance across them.
- Storage orchestration
  - Automatically mount the storage system of your choice, whether from local storage, a public cloud provider
  such as GCP or AWS, or a network storage system such as NFS, iSCSI, Gluster, Ceph, Cinder, or Flocker.
- Secret and configuration management
  - Deploy and update secrets and app configuration without rebuilding your image
  and without exposing secrets in your stack configuration.
- Automatic bin packing
  - Automatically places containers based on their resource requirements and other constraints,
  while not sacrificing availability.
  - Mix critical and best-effort workloads in order to drive up utilization and save even more resources.
- Batch execution
  - In addition to services, K8s can manage your batch and CI workloads, replacing containers that fail, if desired.
- IPv4/IPv6 dual-stack
  - Allocation of IPv4 and IPv6 addresses to Pods and Services.
- Horizontal scaling
  - Scale your app up and down with a simple command, with a UI, or automatically based on CPU usage.
- Self-healing
  - Restarts containers that fail, replaces and reschedules containers when nodes die,
  kills containers that don't respond to your user-defined health check,
  and doesn't advertise them to clients until they are ready to serve.
- Designed for extensibility
  - Add features to your K8s cluster without changing upstream source code.
- Source: [kubernetes.io](https://kubernetes.io/)
