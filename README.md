# Mentoring program, 02-11~03-08, 21 working days.

## 2020-01-07 (Tue)
- [Cloud Native Curriculum](https://hackmd.io/eZ340XcfQVSG-4UhXvqN9A)

## 2019-09-17 (Tue)
- [Declarative application management in Kubernetes](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/architecture/declarative-application-management.md)
- [Kubebuilder](https://book.kubebuilder.io/)

## 2019-03-08 (Fri)
- [Twitter](https://twitter.com/gosharplite/following)
- [CNCF](https://www.cncf.io/)
  - Governing Board
  - TOC, [github](https://github.com/cncf/toc), [mailing list](https://lists.cncf.io/g/cncf-toc/messages)
  - [CNCF Cloud Native Interactive Landscape](https://landscape.cncf.io/)
- [K8s](https://kubernetes.io/) [github](https://github.com/kubernetes)
  - [community](https://github.com/kubernetes/community)
    - [Steering committee](https://github.com/kubernetes/steering)
    - [SIGs and WGs](https://github.com/kubernetes/community/blob/master/sig-list.md)
- Links
  - [K8s releases](https://github.com/kubernetes/kubernetes/releases)
  - [Kubernetes SIGs](https://github.com/kubernetes-sigs)
  - [kubernetes-announce](https://groups.google.com/forum/#!forum/kubernetes-announce)
  - [Kubernetes developer/contributor discussion](https://groups.google.com/forum/#!forum/kubernetes-dev)
  - [youtube](https://www.youtube.com/channel/UCZ2bu0qutTOM0tHYa_jkIwg/videos)
  - [K8s discuss](https://discuss.kubernetes.io/)
  - [Mixing Grafana](http://kube-worker.cloud.m800.com:30005/?orgId=1)
  - [Kubenetes Cluster complexity](https://issuetracking.maaii.com:9443/pages/viewpage.action?spaceKey=CN&title=Kubenetes+Cluster+complexity)
- Team
  - [Handbook](https://issuetracking.maaii.com:9443/display/CN/Handbook)
  - [Guidelines and Values](https://docs.google.com/presentation/d/1qLK6HFQuB-OH4tX1NGyO8skIFBiEbyW1uQI-b7At4nY/edit#slide=id.p1)
  - [Performance Review](https://docs.google.com/presentation/d/1K0hpEv7rxqsN0y0MCY4uTNVL6PBN9V-mSEd9vE09jMs/edit#slide=id.p1)
- Urgent or frequent ops
  - [Common Operation Format about Jira and GitLab](https://docs.google.com/presentation/d/1D8X7bQtiweUoSUxVwbNjvwZFfFvRWszwSxFgpjgEFbU/edit#slide=id.p)

## 2019-03-07 (Thu)
- Mixing cluster
  - [K8s technical design](https://issuetracking.maaii.com:9443/display/SOC/K8s+technical+design)
  - [Kubernetes Operation](https://issuetracking.maaii.com:9443/display/CN/Kubernetes+Operation)
    - Tools
      - [kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
      - [kubectl for Docker Users](https://kubernetes.io/docs/reference/kubectl/docker-cli-to-kubectl/)
      - [Kubectl Reference Docs](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands)
      - [kubectx](https://github.com/ahmetb/kubectx)
      - [kube-ps1](https://github.com/jonmosco/kube-ps1)
      - [kustomize](https://github.com/kubernetes-sigs/kustomize)
  - [gitlab.com/CNCT](https://gitlab.com/CNCT)
  - [gitlab.devops.maaii.com/cloud-native](https://gitlab.devops.maaii.com/cloud-native)
  - [Naming rule for Kubernetes namespace](https://issuetracking.maaii.com:9443/pages/viewpage.action?spaceKey=TBRD&title=20180814+Naming+rule+for+Kubernetes+namespace)

## 2019-03-07 (Thu)
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

## 2019-03-06 (Wed)
- [Kubernetes Resource Management](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/architecture/resource-management.md)
  - [Kubernetes Design and Development Explained](https://thenewstack.io/kubernetes-design-and-development-explained)
- [Strategy map](https://www.facebook.com/groups/1868708016534431/permalink/2034137079991523/)
  - [M800 Cloud Native strategy map](https://docs.google.com/presentation/d/1MU-_srB0eWBUWks4vDLn5cvzPrOpcSRbXPQrN0-VrVk/edit#slide=id.g445b95b491_0_692)
  - [Strategy map basic](https://issuetracking.maaii.com:9443/display/CN/Presentations?preview=/65136093/82297136/Strategy%20Map%20Basic.pdf)
  - [Sun Tzu's Art of War](https://github.com/gosharplite/RichardHCL/blob/master/Art_of_War.md)

## 2019-02-23 (Sat)
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
