> This project is no longer active. The VPS subscription was not renewed, and all functionality has been migrated to the **Pi Keeper** setup.

# 🌐 VPS-Kamatera

> This project is no longer active. The VPS subscription was not renewed, and all functionality has been migrated to the **Pi Keeper** setup.

A self-managed VPS used to run VPN and file-sync services, configured to bypass port restrictions in a dorm network environment.

---

## 📹 Demo

[![Watch Demo](https://img.shields.io/badge/YouTube-Watch%20Demo-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/watch?v=0Txh8oTFT4c)

---

## 🛠️ Setup & Infrastructure

| Parameter | Details |
| :--- | :--- |
| **Provider** | Kamatera |
| **OS** | Ubuntu LTS 24 |

### 🔒 Firewall Configuration (UFW)
Only necessary ports were left open for security hardening:
* `22/tcp` — **SSH**
* `51821/udp` — **WireGuard**
* `1194/udp` — **OpenVPN**

### ⚙️ Running Services
* 🛡️ **WireGuard**
* 🔐 **OpenVPN**
* ☁️ **Nextcloud**

---

## 💡 Why This Existed

My dorm's network blocks incoming ports, making self-hosted services unreachable from the outside. Renting a VPS with a public IP allowed me to create a VPN tunnel back into my home setup and host **Nextcloud** file synchronization without network restrictions.

---

## 🛑 Why I Stopped

The VPS network speed was too slow to comfortably run all desired workloads. I stopped renewing the subscription and migrated the setup to **Pi Keeper**.

---

## 🧰 Tech Stack

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Nextcloud](https://img.shields.io/badge/Nextcloud-0082C9?style=for-the-badge&logo=nextcloud&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white)
![OpenVPN](https://img.shields.io/badge/OpenVPN-EA7E20?style=for-the-badge&logo=openvpn&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
