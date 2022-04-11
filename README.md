# drone-terraform-kubernetes-promote-demo

This repository demonstrates an example workflow of a [Kubernetes](https://kubernetes.io) deployment and service managed by the Kubernetes [Terraform](https://www.terraform.io) [provider](https://registry.terraform.io/providers/hashicorp/kubernetes/latest/docs).

Changes are first made to the `main` branch, which deploys to the `demo-dev` namespace. When ready, the developer will [promote](https://docs.drone.io/promote/) the desired build to the `prod` [target](https://docs.drone.io/pipeline/triggers/#by-target) which will deploy to the `demo-prod` namespace.
