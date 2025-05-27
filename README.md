# Proxmox VE 8.4 Setup

I downloaded the latest version of **Proxmox VE 8.4** and used the open-source GUI utility [balenaEtcher](https://www.balena.io/etcher/) to flash the ISO image to a USB drive.

## Hardware

- **Machine:** Dell OptiPlex 9020
- **CPU:** Intel Core i7
- **RAM:** 16 GB
- **Storage:** SSD

This is my current primary Proxmox machine. I may add a dedicated server later and use this one as a backup or as part of a Proxmox cluster.

## BIOS Configuration

Before installing Proxmox, I made sure to:

- ✅ Enable **UEFI Boot**
- ✅ Enable all **virtualization features** (e.g., VT-x, VT-d)
- ✅ Boot from the **USB drive**

## Installation

Since this is my first time using Proxmox, I chose the **GUI installer** and followed the default installation flow.

### Network Configuration

During installation, I:

- Assigned a **static IP address**: `192.168.1.100`
- Set up **DNS** and **gateway**
- Configured a **hostname**

## Accessing the Web Interface

After installation and reboot, I was able to access the Proxmox web interface at:

```

[https://192.168.1.100:8006](https://192.168.1.100:8006)

```

From there, I proceeded with the initial server configuration.

---

> 🛠️ This is a work in progress. I'll update this README as I expand the setup (e.g., adding storage, clustering, VMs, containers, etc.).
```

Let me know if you’d like to add badges, a table of contents, or sections for usage, screenshots, or future enhancements.


![image](https://github.com/user-attachments/assets/2fb56f8b-676f-448e-97e4-6cd4bc9c92b6)


