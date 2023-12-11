NAME                                                   READY   STATUS    RESTARTS      AGE
pod/argocd-notifications-controller-db4f975f8-2x4bl    1/1     Running   5 (24m ago)   22h
pod/argocd-applicationset-controller-dc5c4c965-65l76   1/1     Running   3 (24m ago)   22h
pod/argocd-server-557c4c6dff-szx2p                     1/1     Running   3 (24m ago)   22h
pod/argocd-redis-b5d6bf5f5-jfjvb                       1/1     Running   3 (24m ago)   22h
pod/argocd-dex-server-9769d6499-fvjb9                  1/1     Running   3 (24m ago)   22h
pod/argocd-repo-server-579cdc7849-nkknx                1/1     Running   3 (24m ago)   22h
pod/argocd-application-controller-0                    1/1     Running   3 (24m ago)   22h

NAME                                              TYPE        CLUSTER-IP      EXTERNAL-IP   PORT(S)                      AGE
service/argocd-applicationset-controller          ClusterIP   10.43.10.142    <none>        7000/TCP,8080/TCP            22h
service/argocd-dex-server                         ClusterIP   10.43.22.61     <none>        5556/TCP,5557/TCP,5558/TCP   22h
service/argocd-metrics                            ClusterIP   10.43.199.188   <none>        8082/TCP                     22h
service/argocd-notifications-controller-metrics   ClusterIP   10.43.220.140   <none>        9001/TCP                     22h
service/argocd-redis                              ClusterIP   10.43.250.148   <none>        6379/TCP                     22h
service/argocd-repo-server                        ClusterIP   10.43.12.172    <none>        8081/TCP,8084/TCP            22h
service/argocd-server                             ClusterIP   10.43.64.161    <none>        80/TCP,443/TCP               22h
service/argocd-server-metrics                     ClusterIP   10.43.66.239    <none>        8083/TCP                     22h

NAME                                               READY   UP-TO-DATE   AVAILABLE   AGE
deployment.apps/argocd-notifications-controller    1/1     1            1           22h
deployment.apps/argocd-dex-server                  1/1     1            1           22h
deployment.apps/argocd-redis                       1/1     1            1           22h
deployment.apps/argocd-applicationset-controller   1/1     1            1           22h
deployment.apps/argocd-server                      1/1     1            1           22h
deployment.apps/argocd-repo-server                 1/1     1            1           22h

NAME                                                         DESIRED   CURRENT   READY   AGE
replicaset.apps/argocd-notifications-controller-db4f975f8    1         1         1       22h
replicaset.apps/argocd-dex-server-9769d6499                  1         1         1       22h
replicaset.apps/argocd-redis-b5d6bf5f5                       1         1         1       22h
replicaset.apps/argocd-applicationset-controller-dc5c4c965   1         1         1       22h
replicaset.apps/argocd-server-557c4c6dff                     1         1         1       22h
replicaset.apps/argocd-repo-server-579cdc7849                1         1         1       22h

NAME                                             READY   AGE
statefulset.apps/argocd-application-controller   1/1     22h
