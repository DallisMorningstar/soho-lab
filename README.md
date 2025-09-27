# soho-lab

## Purpose
This repository documents my Small Office / Home Office (SOHO) lab environment.  
It is built from repurposed hardware to practice home networking and to host services like a Minecraft server and a NAS.

## Lab Overview
- **Server**: Older desktop repurposed as a Minecraft server & NAS (extra storage drive shared over the network)
- **Switch**: 4-port unmanaged switch (handles local device connections)
- **Clients**: Other PCs on the network can connect to the Minecraft server or access shared files on the NAS
- **Network**: Plugged into home router for Internet access

## Services
- **Minecraft Server** — multiplayer game server
- **NAS (Network Attached Storage)** — shared network drive for file storage

## Repo Structure
- `architecture/` -> network diagrams & topology
- `configs/` -> configuration files or server settings
- `experiments/` -> step-by-step guides (e.g., setting up Minecraft server, enabling NAS shares)
- `inventory/` -> hardware & software used
- `notes/` -> troubleshooting tips and observations

## Future Roadmap
- Add backup system for NAS data
- Document Minecraft server optimization
- Experiment with adding a firewall or VLAN-capable switch in the future
