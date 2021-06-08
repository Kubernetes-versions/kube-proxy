# kube-proxy

### Check the current Kubernetes cluster dependency version

kubeadm config images list --kubernetes-version=${version} |awk -F'/' '{print $NF}'

Docs:
https://github.com/kubernetes/kubernetes/releases/tag/v1.21.1

Dcoker versions
Update the latest validated version of Docker to 20.10 (#98977, @neolit123) [SIG CLI, Cluster Lifecycle and Node]
