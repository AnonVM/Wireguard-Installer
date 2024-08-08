# WireGuard VPN Installer: Easy Setup for Linux Servers

**Easily install and configure a [WireGuard VPN](https://www.wireguard.com/) on your Linux server with this simple bash script.** 

WireGuard is a high-performance, secure, and lightweight VPN protocol that can be set up quickly and used in various network scenarios. This script simplifies the installation process, allowing you to create a point-to-point VPN where all client traffic is routed through an encrypted tunnel to the server. The server then applies NAT, making it appear as if the client is browsing the web using the server's IP address.

### Key Features:
- **Supports IPv4 and IPv6**: Ensuring compatibility with modern networks.
- **Easy Client Management**: Add or remove clients by simply rerunning the script.
- **Systemd Integration**: Automatically create a systemd service for efficient management.

If WireGuard doesn’t meet your needs, consider our [OpenVPN installer](https://github.com/AnonVM/OpenVPN-Installer).

## System Requirements

This script supports the following Linux distributions:

- AlmaLinux 8 or higher
- Arch Linux
- CentOS Stream 8 or higher
- Debian 10 or higher
- Fedora 32 or higher
- Oracle Linux
- Rocky Linux 8 or higher
- Ubuntu 18.04 or higher

## Installation Instructions

Follow these steps to install WireGuard on your server:

1. **Download the Script**:
   ```bash
   curl -O https://raw.githubusercontent.com/AnonVM/Wireguard-Installer/main/setup.sh
   ```

2. **Make the Script Executable**:
   ```bash
   chmod +x wireguard-install.sh
   ```

3. **Run the Script**:
   ```bash
   ./wireguard-install.sh
   ```

The script will automatically install the WireGuard kernel module and tools, configure the server, and generate a client configuration file. Rerun the script anytime to manage clients.

## Recommended Cloud Providers for Your VPN Server

For the best performance and value, consider these cloud providers:

- **[AnonVM](https://anonvm.wtf)**: Best privacy focused hosting provider
---
