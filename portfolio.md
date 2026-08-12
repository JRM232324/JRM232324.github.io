---
layout: default
title: "Portfolio"
permalink: /portfolio/
---

# My Portfolio

A collection of my projects, experiments, and development work.

---
** **

## Projects

### Wazuh SIEM & Endpoint Monitoring Homelab

I built and configured a self-hosting Wazuh monitoring environment to gain practical experience with tools used for Security Information and Event Management (SIEM), endpoint monitoring, the collection of logs and additional monitoring such as File Integrity Monitoring (FIM).

Overall, the project consisted of installing and deploying Wazuh through Docker onto a virtual machine hosted by Virtualbox, the virtual machine ran on Ubuntu Server version 24.04 LTS. After troubleshooting connectivity issues and a deployment onto a virtual machine without enough storage, I was able to simulate a small scale security monitoring environment, similar to what might be found within a SOC.

**Objectives:**

- Deploy a functional Wazuh SIEM environment
- Configure a Wazuh Manager, Indexer and Dashboard
- Deploy a Wazuh agent onto an Ubuntu server as an endpoint
- Establish communication between the endpoint and Wazuh Manager
- Monitor endpoint security events
- Configure and test FIM
- Understand the flow of information from endpoint to the SIEM

**Environment**

### Enterprise Ubuntu Home Lab

The Enterprise Ubuntu Home Lab is a virtualised server that I have built through the use of Ubuntu Server 24.04 LTS within Oracle Virtualbox, this server was created to simulate the deployment and management of small business infrastructure as well as develop practical Linux skills such as system administration, networking, containerisation and automation skills inside of a realistic environment.

This server hosts multiple containerised services through the use of Docker and Docker Compose, these include nginx to carry out web hosting utilities, Grafana and Prometheus for system monitoring ability and then Portainer for overall container management. Security is then strengthened and emboldened through the use of UFW, Fail2Ban.

**Technologies used:**

- Windows OS
- Oracle Virtualbox
- Ubuntu Server 24.04 LTS
- Docker & Docker Compose
- Nginx
- Grafana
- Prometheus
- Portainer
- UFW Firewall
- Fail2Ban
- Git & Github

**Key skills Demonstrated:**

- Linux System Administration
- Virtualisation
- Docker Container Management
- Web Server Configuration
- Infrastructure Monitoring
- Network Configuration
- Server Security Hardening
- Bash Scripting & Automation

**Project Screenshots:**

### Virtual Machine Setup

![Ubuntu Server running in Virtualbox, main device connected to it]({{ "/assets/homelab/images/homeandvmdisplay.png" | relative_url }})

*Ubuntu Server 24.04 LTS running inside Oracle VirtualBox as well as a Windows machine connected to it via Ubuntu terminal.*

---

### Docker Container Deployment

![Docker containers operating]({{ "/assets/homelab/images/dockerdisplay.png" | relative_url }})

*Docker containers running the deployed services.*

---

### Containers In Use

![Nginx container running]({{ "/assets/homelab/images/nginxdisplay.png" | relative_url }})
![Grafana container running]({{ "/assets/homelab/images/grafanadisplay.png" | relative_url }})
![Portainer container running]({{ "/assets/homelab/images/portainerdisplay.png" | relative_url }})
![Prometheus container running]({{ "/assets/homelab/images/prometheusdisplay.png" | relative_url }})

*Docker Containers being accessed through Firefox, displays the ability to access different services within the same server.*

## Blog

Follow my progress and read about my latest work:

[View Blog Posts]({{ "/blog/" | relative_url }})
