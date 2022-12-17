CI:
Dockerbuild:
    aws ecr login | docker login
    docker build -t ecrRepourl:tag
    docker push ecrrepourl:tag
CD:
###workernode will pull we don't need to pull like how we did in jenkins
deployment.yaml
svc.yaml
ingress.yaml
kubectl apply -f deployment.yaml service.yaml ingress.yaml

Jenkins:

