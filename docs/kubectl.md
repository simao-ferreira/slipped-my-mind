# kubectl

> Command-line interface for running commands against Kubernetes clusters.
> More information: <https://kubernetes.io/docs/reference/kubectl/>.

- Print the address of the master and cluster services:

`kubectl cluster-info`

- Print available namespaces

`kubectl get namespace`

- Print available resources for given namespace

`kubectl get {{pod|service|deployment|all|...}} --namespace {{namespace}}`
