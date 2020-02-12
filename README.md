# Getting Started on Okteto with Go

This example shows how to use [Okteto](https://github.com/okteto/okteto) to develop a Go Sample App directly in Kubernetes. The Go Sample App is deployed using Kubernetes manifests.

This is the application used for the [How to Develop and Debug Go Applications in Kubernetes](https://okteto.com/blog/how-to-develop-go-apps-in-kubernetes/) blog post.

## switch between different deploy environment

1. local minikube
```shell=
export KUBECONFIG=C:\Users\json\.kube\config
```

2. okteto online

```shell=
export KUBECONFIG=C:\Users\json\.kube\okteto-kube.config
```
