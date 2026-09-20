<div align="center">

# 🦖 Pterodactyl RedM Custom Egg

*A fully optimized, custom Pterodactyl egg designed for seamless RedM server deployment and management.*

[![Pterodactyl Support](https://img.shields.io/badge/Pterodactyl-Ready-blue?style=for-the-badge&logo=pterodactyl)](#)
[![RedM Compatible](https://img.shields.io/badge/RedM-Optimized-red?style=for-the-badge&logo=rockstargames)](#)
[![GitHub Commit](https://img.shields.io/github/last-commit/Forza-Studios/Pterodactyl.REDM.CUSTOM.EGG?style=for-the-badge)](#)

</div>

---

## 📖 Overview

This repository contains a custom [Pterodactyl](https://pterodactyl.io/) Egg specifically configured for running and managing **RedM** servers. It streamlines the installation process, configures the environment correctly, and ensures your Red Dead Redemption 2 roleplay or freeroam server runs smoothly on your panel.

## ✨ Features

- **Quick Deployment:** Easily deploy RedM servers with minimal manual configuration.
- **Optimized Environment:** Pre-configured startup scripts tailored specifically for RedM and TxAdmin.
- **Accessible Variables:** Manage your Server Key, Ports, and TxAdmin settings directly from the Pterodactyl UI.
- **Artifact Management:** Automatically handles and pulls the necessary server artifacts.

## 🚀 Installation Guide

1. **Download the Egg**
   Download the `Pterodactyl.REDM.CUSTOM.EGG.json` file from the main branch of this repository.
2. **Access Admin Panel**
   Log into your Pterodactyl Admin Control Panel.
3. **Import the Egg**
   Navigate to **Nests** -> **Import Egg** and upload the downloaded `.json` file.
4. **Assign to a Nest**
   Assign the imported egg to an existing Nest (e.g., "FiveM/RedM" or "Game Servers").
5. **Deploy a Server**
   Create a new server, select the imported RedM custom egg, fill in your Cfx.re License Key, and deploy!

## ⚙️ Configuration Variables

When deploying a server with this egg, you can quickly configure the following environment variables directly in the panel's "Startup" tab:

| Variable | Description |
| :--- | :--- |
| `LICENSE_KEY` | Your official Cfx.re Server License Key (required). |
| `MAX_PLAYERS` | The maximum number of slots for your server (e.g., 32, 64, 500). |
| `SERVER_HOSTNAME` | The public display name of your RedM server. |
| `TXADMIN_PORT` | The dedicated port for the TxAdmin web interface. |

## 🛠️ Requirements

* A functioning [Pterodactyl Panel](https://pterodactyl.io/) (v1.0 or higher)
* A configured Daemon (Wings)
* A registered [Cfx.re License Key](https://keymaster.fivem.net/)

## 🤝 Support & Contributions

If you encounter any issues with this egg or have suggestions for improvements, please feel free to open an **Issue** or submit a **Pull Request**. Contributions to keep the egg updated with the latest Cfx.re standards are always welcome.

---
<div align="center">
Built by <b>Forza-Studios</b>
</div>
