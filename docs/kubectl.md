# kubectl

> Command-line interface for running commands against Kubernetes clusters.
> More information: <https://kubernetes.io/docs/reference/kubectl/>.

- Print the address of the master and cluster services:

`kubectl cluster-info`

- Print available namespaces

`kubectl get namespace`

- Print available resources for given namespace, (--namespace/-n)

`kubectl get {{pod|service|deployment|all|...}} --namespace {{namespace}}`

- Print available pods:

`kubectl get pods -n {{namespace}}`

- Print release status:

`kubectl -n {{namespace}} status {{application_name}}`

- Print pod logs:

`kubectl -n {{namespace}} logs {{pod_name}} -c {{application_name}}`

- Print deployment information:

`kubectl -n {{namespace}} describe deployment {{pod_name}}`
