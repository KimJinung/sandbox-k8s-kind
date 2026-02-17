# sandbox-k8s-kind
This project provisions a High-Availability (HA) Kubernetes cluster for local development and testing using kind. The primary goal is to automate repetitive infrastructure bootstrapping and provide a local environment that maintains parity with cloud-native setups.

🚀 Quick Start

Spin up the entire environment with a single command—no complex manual configuration required.

## Prerequisites
```bash
./install-kind.sh
./install-kubectl.sh
```

## Create K8s cluster
```bash
./create-cluster.sh
```

## Clean up
```bash
./delete-cluster.sh
```
