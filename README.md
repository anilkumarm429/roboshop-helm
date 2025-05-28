# roboshop-helm

https://helm.sh/docs/intro/install/
curl https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | sudo bash

helm install frontend . --set appName=frontend,containerPort=80
