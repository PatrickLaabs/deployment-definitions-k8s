podman machine stop
podman machine rm
podman machine init --cpus 2 --memory 2048 --disk-size 20
podman machine start

minikube start --driver=podman --container-runtime=cri-o
