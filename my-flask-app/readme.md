

helm create my-flask-app

helm template my-flask-app .\my-flask-app
helm lint .\my-flask-app
helm install my-flask-app .\my-flask-app --dry-run --debug
helm install my-flask-app .\my-flask-app
helm uninstall my-flask-app
helm status my-flask-app

kubectl get pods
kubectl get svc


git init | add | coomit | push

