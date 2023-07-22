# GitOps: CI/CD automation workflow using GitHub Actions, ArgoCD, and Helm charts deployed on K8s cluster


1. i also used terraform as the IAC to setup my infra using AWS EKS
2. then installed argoCD using default namespace

Note: you can either install argoCD using the application yaml file in the root folder or install directly from their official doc and expose the load balancer url.
3. i also added trivy scanner to scan the docker images and save result in the root of folder.
a sample of the trivy image i ran recently is saved.


security tips:
make sure you setup aws credentials in the github secrets , elase  you wont be authenticated