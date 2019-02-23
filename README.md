## TBD
- [Kubernetes Resource Management](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/architecture/resource-management.md) (part 1)
- [Kubernetes Resource Management](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/architecture/resource-management.md) (part 2)
- [Strategy map](https://www.facebook.com/groups/1868708016534431/permalink/2034137079991523/)
- [M800 Cloud Native strategy map](https://docs.google.com/presentation/d/1MU-_srB0eWBUWks4vDLn5cvzPrOpcSRbXPQrN0-VrVk/edit#slide=id.g445b95b491_0_692)

## TBD
- [Accessing Clusters](https://kubernetes.io/docs/tasks/access-application-cluster/access-cluster/)
- [Cluster Management](https://kubernetes.io/docs/tasks/administer-cluster/cluster-management/)
  - Creating a new cluster
  - Upgrading your cluster’s master and worker nodes
  - Performing node maintenance (e.g. kernel upgrades)
  - Upgrading the Kubernetes API version of a running cluster
- [ETCD cluster](https://github.com/etcd-io/etcd)
  - Secure
  - Health check
  - Disaster recovery

## 
- Look into initial cluster objects
- Disecting cluster components
  - Modules
  - Parameters
  
## 2019-02-11 (Mon)
- Prologue
  - [References](https://github.com/gosharplite/RichardHCL/blob/master/references.md)
- [Hands-on with kubeadm + calico](https://kubernetes.io/docs/setup/independent/install-kubeadm/)
  - [DigitalOcean](https://cloud.digitalocean.com/login) + [CoreOS Container Linux](https://coreos.com/releases/) is one possible combination.
  - How are modules started? (etcd, kubelet, api-server, kube-controller, kube-proxy)
  - Where are the parameters?
  - What are the parameters for?
  - [Implementation design for kubeadm](https://github.com/kubernetes/kubeadm/blob/master/docs/design/design_v1.10.md)
- Official documentation
  - [Concepts](https://kubernetes.io/docs/concepts/) 
  - [Accessing the API](https://kubernetes.io/docs/admin/accessing-the-api/)
