+ kubectl create namespace argocd
+ kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
+ kubectl port-forward svc/argocd-server -n argocd 8080:443&
+ curl https://127.0.0.1:8080

+ https://127.0.0.1:8080/applications
