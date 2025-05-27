# infra-setup-docs
This repo contains documentation and setup configurations of services and tools implemented for a small-medium sized business environment.


🏗️ IT Infrastructure Homelab – Enterprise Simulation implemented with Docker
This project is a meant to simulate the building and managing of an enterprise-grade IT infrastructure using Docker to contain critical services, by containerizing core services like DNS, firewall management, and other infrastructure components, this project allows you to learn, test, and iterate on IT infrastructure design and deployment without the need for expensive physical hardware.

### 🔧 Key Features
- Service isolation and networking using Docker
- DNS management using Technitium DNS Server
- A Focus on enterprise-level security practices and configurations
- Planning network topologies, segmentation (e.g., VLANs/Subnets)
- Evaluating infrastructure trade-offs: on-prem vs. cloud vs. hybrid

♻️ Easily extendable: add LDAP, proxy servers, monitoring tools, cloud tools, etc.

### What's does the repo consist of:

#### - README.md file
- Overview of your lab and its purpose
- How to spin up services
- What technologies are used
Diagrams (optional but encouraged)

#### - docker-compose.yml file
- Define services like:
- Technitium DNS
- Uptime Kuma (monitoring)
- Nginx Reverse Proxy
- Maybe even LDAP later
- Use volumes to persist data
- Configure ports and environment variables

#### - docs/ Folder
- Write detailed markdown files for each service and component:
- Why it's used
- How it's configured
- What it's replacing in the real world (e.g., Technitium = internal DNS)
- Security considerations

#### - .env File
- For any private variables for configurations.

This lab environment is ideal for aspiring IT professionals, system administrators, and homelab builders looking to strengthen their infrastructure knowledge by simulating how small to medium businesses might build and manage their internal networks.

This project will continue to grow and evolve over time as new components and improvements are added.
