# metallb-installation
---

### Installing MetalLB load-balancer in On-Prem K8S cluster
=======================================
---
### 1) Edit configmap for your cluster. 


Change *strictARP* value from *true* to *false*
```configmap
kubectl edit configmap -n kube-system kube-proxy 
```
