# Netflix Service 

1. Repos link

- https://github.com/exit-zero-academy/NetflixFrontend
- https://github.com/exit-zero-academy/NetflixMovieCatalog

2. Build docker images and run them locally.
3. Push your images to DockerHub.
4. Create a new GitHub repo called `NetflixInfra`.
5. Deploy the Netflix stack in a Kubernetes cluster. Create a `Deployment` and `Service` for each microservice. Put your YAML manifests in `NetflixInfra`.  
   Make sure the service is up and running by `port-forward`ing your NetflixFrontend service locally. 
6. Install ArgoCD: https://argo-cd.readthedocs.io/en/stable/getting_started/
   read the ArgoCD initial secret by: `kubectl get secret -n argocd argocd-initial-admin-secret -o jsonpath='{.data.*}' | base64 -d`.
