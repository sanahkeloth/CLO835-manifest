# CLO835-manifest

kubectl get all -n webapp -l app.kubernetes.io/version=v1  kubectl get all -n webapp -l app.kubernetes.io/version=v2

kubectl get all -n webapp -l app.kubernetes.io/name=myapp,app.kubernetes.io/component=frontend,app.kubernetes.io/part-of=employeeapp

kubectl get pod mysql-pod -n sqldb -o jsonpath='{.status.podIP}'



kubectl delete all -n webapp -l app.kubernetes.io/name=myapp,app.kubernetes.io/component=frontend,app.kubernetes.io/part-of=employeeapp

