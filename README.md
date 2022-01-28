# Documentation

https://gabrielepicco.github.io/alembik-kubernetes/

# alembik-kubernetes

Alembik Kubernetes deployment files

# MongoDB

1. Make the persistent volume claim:

    kubectl apply -f mongo/mongo_local_path_pvc.yaml

2. Deploy Mongo:

    kubectl apply -f mongo/mongo_deployment.yaml

3. Deploy the service that expose Mongo

    kubectl apply -f mongo/mongo_service.yaml


### Update submodules

    git submodule update --remote 
    
  
# Useful information
  
## Update Instagram token

1. Go to https://developers.facebook.com/apps/393538215044865/dashboard/
2. Tools -> Graph API Explorer -> Generate Access Token
    ![photo_2021-11-17_22-34-36](https://user-images.githubusercontent.com/12031208/142293372-3bdd02fa-1a78-4f67-84e8-2f933d5a8ee7.jpg)
3. Exchange with a long live token: 
    `oauth/access_token?client_id=393538215044865&client_secret=8a63459b0a43fea013553a77ca861103&grant_type=fb_exchange_token&fb_exchange_token={TOKEN_DI_BREVE_DURATA}`
4. Check for access token status: https://developers.facebook.com/tools/debug/accesstoken/
