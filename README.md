jb install github.com/coreos/kube-prometheus/jsonnet/kube-prometheus

./build.sh

kubectl create -f manifests/
