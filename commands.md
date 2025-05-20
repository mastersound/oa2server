docker build -f ./building/devlocal/Dockerfile -t chakalo/oa2server:v1 .

minikube kubectl -- apply -f ./building/devlocal/deployment.yaml

minikube kubectl -- apply -f ./building/devlocal/service.yaml