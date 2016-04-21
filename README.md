# kubernetes-projects
Inventory of community and opensource projects

### Network 

##### Weave - [weave.works](https://www.weave.works/)
https://github.com/weaveworks/weave
> Weave is a lightweight container overlay network that doesn't require an external K/V database cluster.

##### Romana - [romana.io](http://romana.io/)
https://github.com/romana/romana
> Romana is a new network and security automation solution for Cloud Native applications.

##### Calico - [projectcalico.org](https://www.projectcalico.org/)
https://github.com/projectcalico/calico
> Calico's pure L3 approach to data center networking integrates seamlessly with cloud orchestration systems to enable secure IP communication between virtual machines, containers, or bare metal workloads.
 
##### Flannel - [coreos.com/flannel](https://coreos.com/flannel/)
https://github.com/coreos/flannel/
> flannel is a virtual network that gives a subnet to each host for use with container runtimes.

##### OpenContrail - [opencontrail.org](http://www.opencontrail.org/)
https://github.com/Juniper/contrail-controller
> An open-source network virtualization platform for the cloud

### Cluster managment/deployment tools

##### kraken
https://github.com/Samsung-AG/kraken

> Deploy a Kubernetes cluster using Terraform and Ansible on top of CoreOS.

##### kargo - [kubespray.io](https://doc.kubespray.io)
https://github.com/kubespray/kargo

> - Deploy a production ready kubernetes cluster on AWS, GCE, OpenStack or Baremetal
- Options to chose the network plugin: weave/flannel/calico/opencontrail/romana/
- Support popular os: CoreOS, Debian, Centos....
- Stable deployment scripts with continuous integration tests (deploy clusters and test them on PR)

##### kube-aws - [coreos.com/kube-aws](https://coreos.com/kubernetes/docs/latest/kubernetes-on-aws.html)
https://github.com/coreos/coreos-kubernetes

> At CoreOS, we use the kube-aws CLI tool to automate cluster deployment to AWS

##### Digital Rebar/RackN Enterprise
* https://rebar.digital
* https://rackn.com

> - Deploy and orchestrate kuberenetes deployments across multiple clouds, bare metal, and operating systems.
- Options to choose network plugins - same as kargo.
- Supports bare metal provisioning as well as cloud infrastructure
- Kubernetes component is based currently on kargo ansible scripts - imports directly.
- Uses composition to build out clusters


### Dashboards and UI components
##### kubernetes-dashboard
##### kube-ui
##### kubedash

### Monitoring tools

### Loadbalancing
