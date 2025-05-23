# My Homelab 🏠💻

Welcome to my homelab setup! This is my personal homelab, which I use for tinkering and experimentation.

![](./img/DSCF7869.jpg)

## Overview
My homelab consists of several key components, each serving a specific function:

- **Pi-hole** – Network-wide ad blocking and DNS filtering
- **Unifi** – Managing my home network and Wi-Fi setup
- **OctoPrint** – Remote monitoring and control of my 3D printer
- **ESP32s running WLED** – LED control and automation
- **K3S cluster** – Lightweight Kubernetes for containerized applications

Here are the services I'm permanently running on my **K3S Raspberry Pi cluster**:
- **Grafana** – For visualization and dashboards 
- **Prometheus** – Collecting and storing time-series metrics
- **Traefik** – Reverse proxy and ingress controller
- **Kubernetes Dashboard** – Web UI for cluster management

I've recently started **monitoring external metrics via Prometheus**. You can learn more by checking out [this repository](https://github.com/Demerak/HomeLabEnvironmentalSensors). I use Grafana to visualize these metrics. I also use Grafana to track my running activity metrics via Strava API integration. 

## Future Plans
- Expanding monitoring with **additional Prometheus integrations**, specifically **soil moisture monitoring** for my plants
- Setting up **Home Assistant** for better automation and control
- Adding a **DIY NAS running TrueNAS** 
- Setting up a **self-hosted Git platform** (most likely **Gitea**)
- Exploring **ArgoCD** for GitOps-based Kubernetes application management

Homelabbing feels like a never-ending rabbit hole, but that's exactly what makes it exciting. There’s always something new to learn, a new technology to explore, and another opportunity to deepen my understanding across different fields. I love staying up to date with the latest innovations, experimenting with new tools, and refining my setup as I go. As a little wink to where it all began, here’s how my homelab setup first started taking shape. It hasn’t changed drastically yet, but I know it will continue evolving and improving over time. :smile:

![](./img/DSCF7863.jpg)