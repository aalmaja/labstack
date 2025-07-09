This repo is a home lab infrastructure automation project that demonstrates real-world DevOps practices using Terraform, Ansible, and Python, orchestrated on an on-premise Proxmox Virtual Environment.

This project automates the full lifecycle of virtual machines:

    Provisioning with Terraform (via Proxmox API)

    Configuration management with Ansible (package install, system setup)

    Custom automation scripts in Python (monitoring, health checks, API integrations)

Key Features

    Infrastructure as Code (IaC): Modular and reusable Terraform configurations

    Agentless Automation: Ansible roles and playbooks for fast, declarative VM setup

    Monitoring Scripts: Python tools for VM status, Proxmox resource usage, and health checks

    Reusable DevOps Toolkit: Suitable for home labs, test environments, and edge deployments

Tech Stack

    Terraform – VM provisioning via Proxmox API

    Ansible – Remote configuration and service installation

    Python – Custom automation and monitoring

    Proxmox VE – On-premise virtualization platform

Hardware:

    32 GB DDR4 RAM

    AMD Processor

    NVIDIA Gigabyte GTX 1060 GPU

    2 TB SSD for VM storage

    2 TB dedicated to TrueNAS SCALE for networked storage and backup
