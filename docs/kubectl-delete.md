# kubectl

> Command-line interface for running commands against Kubernetes clusters.
> More information: <https://kubernetes.io/docs/reference/kubectl/>.

- Delete deployment:

```bash
kubectl -n {{namespace}} get deployments
kubectl -n {{namespace}} delete deployments {{deployment_name}}
```

- Delete pod, deployment still exists it will recreate pod again according to defined blueprint:

```bash
kubectl -n {{namespace}} get pods
kubectl -n {{namespace}} delete pod {{pod_name}}
```
