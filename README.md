### kubectl apply commands in order

    kubectl apply -f mongodb-secret.yaml
    kubectl apply -f mongodb-deployment.yaml
    kubectl apply -f mongodb-service.yaml
    kubectl apply -f mongodb-configmap.yaml
    kubectl apply -f mongo-express-deployment.yaml
    kubectl apply -f mongo-express-service.yaml

### kubectl get commands

    kubectl get pod
    kubectl get pod --watch
    kubectl get pod -o wide
    kubectl get service
    kubectl get secret
    kubectl get all | grep mongodb

### kubectl debugging commands

    kubectl describe pod mongodb-deployment-xxxxxx
    kubectl describe service mongodb-service
    kubectl logs mongo-express-xxxxxx

### give a URL to external service

    http://localhost:8081/
