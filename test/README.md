# AutoScript Install XRAY / SSH Websocket

Repositorio optimizado para la instalación automática de servicios VPN (XRAY, SSH Websocket, Trojan, VLESS, etc.) en servidores VPS.

---

## ⚙️ Requisitos Previos

- Un servidor VPS limpio (recién formateado).
- Sistema operativo: **Debian 9 / 10 / 11** o **Ubuntu 18.04 / 20.04 / 22.04**.
- Acceso como usuario `root`.
- Se recomienda actualizar el sistema antes de la instalación.

---

## 🔄 Actualización del Sistema (Primera Instalación)

### ♦️ Para Debian 9 / 10 / 11
```bash
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
