# kubectl

> Command-line interface for running commands against Kubernetes clusters.
> More information: <https://kubernetes.io/docs/reference/kubectl/>.

- Scale number of replicas:

```sh
kubectl -n {{namespace}} get deployments
kubectl -n {{namespace}} --replicas={{number}} deployment/{{deployment_name}}
```

