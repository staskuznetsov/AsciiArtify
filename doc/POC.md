
https://github.com/staskuznetsov/AsciiArtify/assets/88095654/427dc977-02ee-45b8-b8ef-468791a4c9ad
  

[Screenshot-7](https://github.com/staskuznetsov/AsciiArtify/assets/88095654/427dc977-02ee-45b8-b8ef-468791a4c9ad)

kubectl create namespace argocd
+ kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
+ kubectl port-forward svc/argocd-server -n argocd 8080:443&
+ curl https://127.0.0.1:8080

