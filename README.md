# XOneFi Router Firmware

# XOneFi Firmware Installation Guide

This guide provides instructions on how to install the XOneFi firmware on a TP-Link Archer C7 V5 router.

## Prerequisites
- A TP-Link Archer C7 V5 router.

## Installation Options

### 1. Upgrading from an Existing OpenWRT Router

1. **Download the Sysupgrade Firmware:**
   - [openwrt-ath79-generic-tplink_archer-c7-v5-squashfs-sysupgrade.bin](https://github.com/xmeshlab/xonefi-firmware/blob/main/openwrt/bin/targets/ath79/generic/openwrt-ath79-generic-tplink_archer-c7-v5-squashfs-sysupgrade.bin)

2. **Log in to your OpenWRT router:**
   - Access your router via a web browser at `http://192.168.1.1` (default IP).
   - Enter your username and password.

3. **Navigate to the Firmware Upgrade section:**
   - Go to `System` > `Backup / Flash Firmware`.

4. **Upload the Sysupgrade Firmware:**
   - Under `Flash new firmware image`, click `Choose File` and select the downloaded `.bin` file.
   - Uncheck the box labeled `Keep settings` to ensure a clean installation.
   - Click `Flash Image`, then `Proceed` to start the upgrade process.

5. **Wait for the upgrade to complete:**
   - The router will reboot automatically. Do not power off the router during this process.
   - Reconnect to the router and log in.

### 2. Flashing a Factory Router

1. **Download the Factory Firmware:**
   - [openwrt-ath79-generic-tplink_archer-c7-v5-squashfs-factory.bin](https://github.com/xmeshlab/xonefi-firmware/blob/main/openwrt/bin/targets/ath79/generic/openwrt-ath79-generic-tplink_archer-c7-v5-squashfs-factory.bin)

2. **Access the Router's Web Interface:**
   - Connect your router to your computer using an Ethernet cable.
   - Access the router’s web interface by entering `http://tplinkwifi.net` or `http://192.168.0.1` in your browser.
   - Log in with the default credentials (usually `admin`/`admin`).

3. **Upload the Factory Firmware:**
   - Go to `Advanced` > `System Tools` > `Firmware Upgrade`.
   - Click `Browse`, select the downloaded `.bin` file, and click `Upgrade`.
   - Confirm the operation and wait for the flashing process to complete.

4. **Router Reboot:**
   - The router will reboot. Wait until it is fully operational.
   - Reconnect to the router using the default IP (usually `192.168.1.1`).

## Post-Installation

- Navigate to the configuration page ie 192.168.1.1/xonefi/configure.html 
- Enter your configuration settings


## Support

If you encounter any issues or need further assistance, please create an issue on this GitHub repository.

