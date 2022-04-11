# drone-terraform-kubernetes-branch-demo

This repository demonstrates an example workflow of a [Kubernetes](https://kubernetes.io) deployment and service managed by the Kubernetes [Terraform](https://www.terraform.io) [provider](https://registry.terraform.io/providers/hashicorp/kubernetes/latest/docs).

Changes are first made to the `dev` branch, which deploys to the `demo-dev` namespace. Changes are then merged from the `dev` branch to the `prod` branch to deploy changes to the `demo-prod` namespace.
