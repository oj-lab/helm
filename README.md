# OJ Lab Helm

![Static Badge](https://img.shields.io/badge/Chart%20-%20?style=flat&logo=helm&color=blue)

## Dev Guide

You can follow [K8s Setup Guide](https://oj-lab.github.io/oj-lab-docusaurus/docs/learn/dev-environment/k8s-setup-guide/)
to get the local develop environment.

First, you need a local minikube cluster.

Then, use

```
helm dependency build

helm install ojlab .
```

Follow the given NOTES to expose service you want.