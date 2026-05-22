## homelab
A public portfolio show caseing my home lab infrastructure, projects, and learning journey — built as part of a structured 90-day plan to land a DevSecOps or Cloud Engineering role.
This repo is the front door. It documents how everything is set up, how components connect, what technology decisions were made and why. Individual project repos branch off from here, covering everything from infrastructure-as-code to security monitoring. The work here is to document my own learning both complete/polished and still in progress.


## About me
I'm Alex Simmonds (Tank77777 online), based just west of London.
I hold a BSc (Hons) in Cyber Security from the University of Gloucestershire. After graduating I moved into software testing on a large government project in the private sector, which evolved into an application support role, triaging defects and analysing complex issues across a wide network environment made up of hundreds of components.
I'm now making a deliberate move into cloud engineering and DevSecOps, where I can make full use of my security background alongside the infrastructure and tooling skills I've been building in this lab.
I'm a practical, hands-on learner. who prefers to build and experiment to understand concepts tools. I've been told I approach problems from a unique perspective and think out side the box which has served me well professionally and in all aspects of life.


## Lab setup
[ Add a short description of your physical server, Proxmox setup, and remote access here. No IPs or network details — just the shape of the thing. ]



## Project index / Ideas
Repo					Description														Status
terraform-proxmox		IaC to provision and manage VMs on Proxmox						In progress
ansible-playbooks		Configuration management and system hardening					In progress
cloud-resume-challenge	Azure full-stack project following the Cloud Resume Challenge	Planned
selfmade-nas			Using Dell Tiny PC make a NAS systme for mass Storage			Planned
media-center			Self hosted Media center for films, music etc. on NAS			Planned
bitcoin-node			Self hosted bitcoin node using Umbrel OS on Dell Tiny PC		Complete
							> Running/Active utilises Bitcoin Knots and home miners				
devsecops-pipeline		GitHub Actions CI/CD with integrated security scanning			Planned
wazuh-siem-setup		Security monitoring using Wazuh SIEM							Planned
devdocs-assistant		AI-powered writing tool for generating documentation			Complete
							> First version v1 live, via Github pages 
								>API proxy server on Proxmox for v2


## What I'm learning
Infrastructure: Proxmox VE · Terraform · Ansible · Linux administration
Cloud: Azure (in progress via Cloud Resume Challenge)
Security: Wazuh SIEM · system hardening · security scanning in CI/CD pipelines
CI/CD: GitHub Actions · pipeline design · secrets management
Networking: VLANs · Tailscale · remote access · DNS


## 90-day roadmap
Phase 1 — Foundation 
Set up Proxmox on physical Dell PC, configure SSH access with static IP 
Set up Tailscale for secure external remote access  
Provision first VM using Terraform (terraform-proxmox)

Phase 2 — Cloud + CI/CD 
Build and host the Cloud Resume Challenge on Azure (or AWS) 
Build a GitHub Actions CI/CD pipeline and integrate it across projects
Implement security scanning in the pipeline with attack/defence VM setup and log filtering

Phase 3 — Security + Polish 
Introduce Wazuh SIEM — practice filter creation and policy management
Clean up documentation across all repos, add screenshots and evidence

Full detail → roadmap/90-day-plan.md

## Learning journal
I document progress and reflections weekly in journal/ — what I built, what broke, what I learned. Updated every week throughout the 90 days.


## Connect
[ LinkedIn URL ]

[ Blog or portfolio URL if you have one ]
 
