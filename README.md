# CatLab 🐱

CatLab is my personal homelab repository, focused on managing and experimenting with **Kubernetes clusters** on Raspberry Pi devices and old mini-PCs.
It’s a playground for learning, testing GitOps, and exploring cluster automation.
And also my CV 😎 (I’m open to work!)

---

## Current Setup

I currently maintain **two K3s clusters**:

### `cat-k3s` (Staging)

* **Nodes:** 3× Raspberry Pi 5
* **Purpose:** Testing and staging deployments

### `magi-k3s` (Production)

* **Nodes:** 3× HP EliteDesk 800 Mini PCs
* **Purpose:** Production-ready cluster for stable services

---

## Tools & Practices

* **K3s** – Lightweight Kubernetes for edge devices
* **Flux (GitOps)** – Automated deployments from Git
* **SOPS** – Managing and encrypting secrets
* **Cloudflare Tunnels** – Exposing services safely
* **k9s** – Terminal-based cluster management

---

## Goals & Future Plans

* Expand automation using **Terraform** and **Ansible** for cluster provisioning
* Implement GitOps-driven workflows across staging and production
* Experiment with monitoring, secrets management, and multi-cluster orchestration

---

## Explore the Repo

Inside you’ll find:

* Cluster manifests
* GitOps configuration
* Secrets management examples
* Notes and experiments from my homelab Kubernetes setups
