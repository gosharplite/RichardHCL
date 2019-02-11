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

## TBD
- Look into initial cluster objects
- Disecting cluster components
  - Modules
  - Parameters
  
## TBD
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
