CatLab is my personal homelab repository, focused on managing and experimenting with **Kubernetes clusters** on Raspberry Pi devices and old mini-PC's.
It’s a playground for learning, testing GitOps, and exploring cluster automation.
And also my CV :D (I'm open to work! :))

## Current Setup

I currently maintain **two K3s clusters**:

### `cat-k3s` (Staging)

* 3x Raspberry Pi 5 nodes
* Purpose: Testing and staging deployments
  
### `magi-k3s` (Production)

* Hardware: 3x HP EliteDesk 800 mini
* Purpose: Production-ready cluster for stable services

## Tools & Practices

* **K3s** – Lightweight Kubernetes
* **Flux (GitOps)** – Automated deployments from Git
* **SOPS** – Managing and encrypting secrets
* **Cloudflare Tunnels** – Exposing services safely
* **k9s** – Terminal-based cluster management

## Goals & Future Plans

* Expand automation using **Terraform** and **Ansible** for cluster provisioning
* Implement GitOps-driven workflows across staging and production
* Experiment with monitoring, secrets management, and multi-cluster orchestration

## Explore

Check out the repository to see:

* Cluster manifests
* GitOps configuration
* Secrets management examples
* My experimentation notes for homelab Kubernetes setups
