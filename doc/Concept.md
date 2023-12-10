Minikube
+ Minikube is a tool for running Kubernetes clusters on a local machine. One of the primary benefits of Minikube is its ease of use. Also Minikube provides a built-in dashboard that allows you to view and manage cluster from a web browser.

KinD
+ KinD is another tool for running Kubernetes clusters on a local machine. One of the primary benefits of KinD is its flexibility. KinD allows to customize your cluster by adding or removing nodes, changing configuration settings, and installing additional software. KinD provides a built-in dashboard that allows to view and manage cluster from a web browser.

k3d
+ k3d is a tool for running Kubernetes clusters on a local machine. One of the primary benefits of k3d is speed. Also k3d provides a built-in dashboard that allows to view and manage cluster from a web browser.

| Feature          | Minikube                                                                                               | KinD                                                                                                                                                                              | k3d                                                             |
|------------------------|------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| Easy of use | +     |                         |                                                      |
| Flexibility  |    | +  |                                           |
| Speed       |   |          | + |
| Resource usage      |   |     +     |  |
| Compatibility     |  + |          |  |
| Vanilla Kubernetes    |  + |     +     | - |
| Node Control System    |  virtualbox  <br> vmwarefusion  <br> kvm2 <br> vmware <br> docker <br> podman |    docker   |  docker |

So, only Minikube can work with podman. Also Minikube easy to use. I choose Minikube.
