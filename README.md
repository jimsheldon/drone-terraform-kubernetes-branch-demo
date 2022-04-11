# drone-terraform-kubernetes-branch-demo

This repository demonstrates an example workflow of a [Kubernetes](https://kubernetes.io) deployment and service managed by the Kubernetes [Terraform](https://www.terraform.io) [provider](https://registry.terraform.io/providers/hashicorp/kubernetes/latest/docs).

Changes are first made to the `main` branch, which deploys to the `demo-dev` namespace. When ready, the developer will promote the desired build to the `prod` target.
