# limit-initializer

Kubernetes initializer that adds resource limits/requests to containers if limits/requests are not set

It is based on [Kubernetes Initializer Tutorial](https://github.com/kelseyhightower/kubernetes-initializer-tutorial)

## Prerequisites

Kubernetes 1.7.0+ is required with [support for Initializers enabled](https://kubernetes.io/docs/admin/extensible-admission-controllers/#enable-initializers-alpha-feature). If you're using Google Container Engine create an alpha cluster:

