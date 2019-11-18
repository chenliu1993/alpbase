# alpbase
docker run --privileged -v /lib/modules:/lib/modules -it -e K3S_KUBECONFIG_OUTPUT=/home/cliu2/Documents/go/src/github.com/chenliu1993/apline_base/tmp/output/kubeconfig.yaml -e K3S_KUBECONFIG_MODE=666 -v /home/cliu2/Documents/go/src/github.com/chenliu1993/apline_base/tmp/tmp:/var/lib/rancher/k3s -p 6444:6443 --name base0 alpine:base
