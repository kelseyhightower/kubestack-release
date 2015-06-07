# Kubestack Release

Kubestack provides the following binaries:

* docker
* etcd
* etcdctl
* flanneld
* hyperkube
* kube-apiserver
* kube-proxy
* kube-scheduler
* kubectl
* kubelet

## Creating a release

Releases are created from upstream binary releases.

```
./release kubestack-0.18.1-versions
```

You should end up with a kubestack release package:

```
kubestack-0.18.1.tar.gz
```
