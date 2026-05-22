# Homelab

A public portfolio showcasing my home lab infrastructure, projects, and learning journey — built as part of a structured 90-day plan to land a DevSecOps or Cloud Engineering role.

This repo is the front door. It documents how everything is set up, how components connect, what technology decisions were made and why. Individual project repos branch off from here, covering everything from infrastructure-as-code to security monitoring. The work here is real — both complete and still in progress — because that's what learning looks like.

---

## About me

I'm Alex Simmonds (Tank77777 online), based just west of London.

I hold a BSc (Hons) in Cyber Security from the University of Gloucestershire. After graduating I moved into software testing on a large government project in the private sector, which evolved into an application support role — triaging defects and analysing complex issues across a wide network environment made up of hundreds of components.

I'm now making a deliberate move into cloud engineering and DevSecOps, where I can make full use of my security background alongside the infrastructure and tooling skills I've been building in this lab.

I'm a practical, hands-on learner who prefers to build and experiment to understand things. I've been told I approach problems from a unique perspective and think outside the box — that's served me well professionally and in all aspects of life.

---

## Lab setup

> Coming soon — full architecture diagram and specs to be added after initial setup is complete.

---

## Project index

### Core projects

| Repo | Description | Status |
|------|-------------|--------|
| [terraform-proxmox](#) | IaC to provision and manage VMs on Proxmox | In progress |
| [ansible-playbooks](#) | Configuration management and system hardening | In progress |
| [cloud-resume-challenge](#) | Azure full-stack project following the Cloud Resume Challenge | Planned |
| [devsecops-pipeline](#) | GitHub Actions CI/CD with integrated security scanning | Planned |
| [wazuh-siem-setup](#) | Security monitoring and policy management using Wazuh SIEM | Planned |
| [devdocs-assistant](#) | AI-powered documentation writing tool — v1 live via GitHub Pages, v2 in development with API proxy on Proxmox | Active |

### Side projects

| Repo | Description | Status |
|------|-------------|--------|
| [bitcoin-node](#) | Self-hosted Bitcoin node via Umbrel OS on Dell Tiny PC — running Bitcoin Knots with home miners | Running |
| [selfmade-nas](#) | NAS build using a Dell Tiny PC — mass storage, Home Assistant, expandable housing | Planned |
| [media-center](#) | Self-hosted media server on the NAS — Plex or Jellyfin with music and film libraries | Planned |

> Replace each `#` with the actual repo URL once created.

---

## What I'm learning

- **Infrastructure:** Proxmox VE · Terraform · Ansible · Linux administration
- **Cloud:** Azure (in progress via Cloud Resume Challenge)
- **Security:** Wazuh SIEM · system hardening · security scanning in CI/CD pipelines
- **CI/CD:** GitHub Actions · pipeline design · secrets management
- **Networking:** VLANs · Tailscale · remote access · DNS

---

## 90-day roadmap

**Phase 1 — Foundation**
- Set up Proxmox on physical Dell PC, configure SSH access with static IP
- Set up Tailscale for secure external remote access
- Provision first VM using Terraform (`terraform-proxmox`)

**Phase 2 — Cloud + CI/CD**
- Build and host the Cloud Resume Challenge on Azure
- Build a GitHub Actions CI/CD pipeline and integrate it across projects
- Implement security scanning in the pipeline with attack/defence VM setup and log filtering

**Phase 3 — Security + Polish**
- Introduce Wazuh SIEM — practice filter creation and policy management
- Clean up documentation across all repos, add screenshots and evidence

Full detail → [roadmap/90-day-plan.md](roadmap/90-day-plan.md)

---

## Learning journal

I document progress and reflections weekly in [`journal/`](journal/) — what I built, what broke, what I learned. Updated every week throughout the 90 days.

---

## Connect

- [LinkedIn](#) ← replace with your URL
- [Blog / Portfolio](#) ← replace with your URL if you have one
