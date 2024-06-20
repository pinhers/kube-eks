## Running the project on Kubernetes

- inside the k8-deployment-files folder
```sh
./run-kube.sh
kubectl apply -f <yaml-file-name> 
```

---

# Removing components in k8s

```bash
`kubectl delete <service/deployment>`
`kubectl delete all --all --all-namespaces` (will need to run ./13-... from jdaniels' project)
```

---

# Troubleshoot

- kubectl logs <pod-name>
- kubectl describe pods

---
