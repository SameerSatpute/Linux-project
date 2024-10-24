Linux Virtualized Home Lab Environment.

Project Description:

This project demonstrates the setup of a fully functional home lab environment using Linux OS 9.0 on VMware. The environment comprises multiple virtual machines, each performing distinct server roles, including FTP, HTTP, DNS, and an Ansible Controller for automation. The goal is to simulate a real-world infrastructure environment and practice systems administration, automation, and network configurations.

Key Features:

1) Multi-Server Setup: Designed and managed a multi-server environment using VMware, where each virtual machine serves a specific role (FTP, HTTP, DNS, etc.).
2) Automation: Implemented automation for server deployment and configuration management using Ansible, improving efficiency and consistency across the home lab.
3) Load Balancing: Configured load balancing to distribute traffic between servers and ensure high availability and reliability.
Storage Management: Set up advanced storage management solutions, such as LVM, Stratis, NAS, and SAN, providing scalable and efficient storage.
4) Centralized Package Management: Set up a DNF server to act as a centralized package repository, ensuring smooth and efficient package updates across all VMs.
5) User and Permission Management: Configured user accounts, group management, file permissions, and access control lists (ACLs) for enhanced security and control.

Technologies Used:

** Linux OS 9.0: Base operating system for all virtual machines.
** VMware: Virtualization platform for creating and managing virtual machines.
** Ansible: Automation tool for managing server configuration and deployment.
** DNF (Dandified YUM): Package manager used for installing and managing software packages.
** LVM (Logical Volume Manager): Advanced storage management for creating and managing logical volumes.
** Stratis-pool: A Linux storage management solution for advanced file system management.
** NAS (Network-Attached Storage): Configured for centralized storage, allowing access over the network.
** SAN (Storage Area Network): Configured for block-level storage access across multiple servers.