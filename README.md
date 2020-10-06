# descheduler-kustomize

This repository is an example of how to use the descheduler via kustomize.

## Run As A Job
```
git clone https://github.com/m3y/descheduler-kustomize.git
cd descheduler-kustomize/
kustomize build . | kubectl apply -f -
```
