# alembik-kubernetes

Alembik Kubernetes deployment files

# MongoDB

1. Make the persistent volume claim:

    kubectl apply -f mongo/mongo_local_path_pvc.yaml

2. Deploy Mongo:

    kubectl apply -f mongo/mongo_deployment.yaml

3. Deploy the service that expose Mongo

    kubectl apply -f mongo/mongo_service.yaml