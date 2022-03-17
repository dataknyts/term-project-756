# CMPT756: Term-Project

### Pre-requisite Setup

1. Start service
make -f eks.mak start

2. Provision services and set Kubectl context
make -f k8s.mak provision
kubectl config set-context --current --namespace=c756ns

3. Print grafana URL
make -f k8s.mak grafana-url
Create gatling-1-music.sh
