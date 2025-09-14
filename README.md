# Hands-on Activity 12.1 – Security Automation with Ansible

This repository contains **Hands-on Activity 12.1** from **CPE 213-CPE32S21 - Cloud Management and Security**. It demonstrates the use of **Ansible automation** for network and system security tasks, simulating real-world **network forensics and security operations**.

## Overview
Implemented **security automation** for Linux systems using Ansible, focusing on:

- Firewall management
- User and group configuration
- Service hardening
- Compliance with login banners and messages of the day (MOTD)

Automation streamlined repetitive tasks, improved system reliability, and minimized human error.

## Key Tasks
- Automated creation and removal of firewall rules using `acl_manager` roles.
- Configured users, groups, and SSH access securely.
- Managed unnecessary services and software using variables and loops for reusability.
- Applied system hardening and compliance policies.
- Ensured consistent security policies across multiple servers.

## Simulation Environment
- VirtualBox with Ubuntu Server nodes
- One node as **Ansible control**, others as **managed hosts**
- Tasks executed via Ansible playbooks and roles

## Skills & Tools
Ansible | Linux (Ubuntu/CentOS) | Firewall Management (UFW/Check Point) | Security Automation | Playbooks & Roles

## Reflections
Using Ansible allowed me to **automate manual security tasks**, enforce policies consistently, and reduce errors. This project reinforced the value of automation in maintaining system and network security while providing hands-on experience in **enterprise-level security operations**.
