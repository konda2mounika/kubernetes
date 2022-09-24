# kubenetes commands 


Most used Kubernetes commands :

```
Syntax :  kubectl action resources 

* kubectl get nodes  
* kubectl get nodes -o wide
* kubectl cluster-info 
* kubectl api-versions
* kubectl api-resources 
* kubectl --help 
```

### Kubernetes Configuration :
```
    Kubectl will try to use the config resides in ~/.kube/config file 
```

## K8 resources can be created by imperative commands or with the declaratvie approch ( VCS )

#### Resources :
```
    1) PODS
    2) ENV 
    3) CMD 
    4) ConfigMap 
    5) Secret 
    6) SETS  
        a) Deployments
        b) ReplicaSets 
        c) DaemonSets
        d) StatefulSets
    7) Health Checks

``` 

### OpenShift
```
    Linux ---> RedHat ( ES )
        ---> CentOS ( CS )

    K8   ---> OpenShift  ( ES ) 
        ---> Kubernetes ( CS )
            ( EKS , GKE )

```


Liveliness Prode:

The kubelet uses liveness probes to know when to restart a container. For example, liveness probes could catch a deadlock, where an application is running, but unable to make progress. Restarting a container in such a state can help to make the application more available despite bugs.