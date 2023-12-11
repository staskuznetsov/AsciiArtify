+ kubectl create namespace argocd
+ kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
+ kubectl port-forward svc/argocd-server -n argocd 8080:443&
+ https://127.0.0.1:8080
+ kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d; echo
+ https://127.0.0.1:8080/applications
+ admin:8pL6KuyNAu1ignX2
+ https://127.0.0.1:8080/login?return_url=https%3A%2F%2F127.0.0.1%3A8080%2Fapplications
