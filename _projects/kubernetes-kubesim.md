---
title: "Kubernetes-Kubesim"
description: "Distributed System Simulator"
layout: page
---

# [Kubernetes-Kubesim](https://github.com/OmkarKashyap/KubernetesKubesim)

**Kubernetes-Kubesim** is a lightweight simulator of a Kubernetes-style control plane built with Flask and Docker. It simulates node registration, heartbeat handling, pod scheduling, and node failure/recovery. The simulator can be controlled via both a simple CLI and a RESTful API.

## Project Context

This project was created as part of the Cloud Computing course at PES University, where we explored key concepts in distributed systems, containerization, and Kubernetes-like architectures. The objective was to implement a lightweight simulator to understand node management, pod scheduling, and fault tolerance, which are core features of the Kubernetes control plane.

## Features

- **Node Registration & Heartbeat Handling**  
  Register nodes, manage heartbeats, and simulate node failure/recovery in a Kubernetes-like environment.

- **Pod Scheduling**  
  Launch and manage pods with defined resource requirements (e.g., CPU allocation).

- **Persistent Storage**  
  Supports data persistence by binding volumes for maintaining state between runs.

- **CLI and RESTful API**  
  Easily interact with the simulator using either the command line or HTTP API.

## Tech Stack

- **Frontend:** Flask (Python)
- **Containerization:** Docker
- **Database:** SQLite (cluster state storage)
- **Simulator Interface:** CLI & RESTful API

## Repository

Explore the full project here: [ Kubernetes-Kubesim GitHub Repository](https://github.com/OmkarKashyap/KubernetesKubesim)

---

Feel free to fork, contribute, or report any issues. Simulate Kubernetes-like control planes with **Kubernetes-Kubesim**!
