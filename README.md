# Prototyping ArgoCD the app of apps GitOps pattern

- https://argo-cd.readthedocs.io/en/stable/operator-manual/cluster-bootstrapping/#cluster-bootstrapping

Bootstrap Kubernetes cluster using following repos:

- https://github.com/pasiol/kubespray-kvm-bootsrap
- https://github.com/pasiol/kubespray/tree/provisioning/k8s-dev

## App of Apps

- metallb for loadbalancing and and exposing external ips
- kubegres operator for creating HA Postgres replicaset services
