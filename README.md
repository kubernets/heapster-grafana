# heapster-grafana

github addr [https://github.com/kubernets/heapster-grafana](https://github.com/kubernets/heapster-grafana)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/heapster-grafana/raw/master/get-heapster-grafana-image.sh

## Arch and Version

- [**amd64** v5.0.4](https://hub.docker.com/r/kubernets/heapster-grafana-amd64)

    > docker pull kubernets/heapster-grafana-amd64:v5.0.4

    > docker tag kubernets/heapster-grafana-amd64:v5.0.4 k8s.gcr.io/heapster-grafana-amd64:v5.0.4 

    > docker rmi kubernets/heapster-grafana-amd64:v5.0.4
