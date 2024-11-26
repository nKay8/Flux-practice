use the command below to apply the kustomization file
kubectl apply -k .

use below to check exactly what changes applied with the kustomization
kubectl kustomize .

use below to undo all that was done with the kustomization file
kubectl delete -k .


- use below for portfording
`kubectl port-forward service/todoapp-service 8000:80 -n banku`
