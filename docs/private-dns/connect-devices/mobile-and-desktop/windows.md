---
title: Windows
sidebar_position: 5
---

To connect a Windows device to AdGuard DNS, first add it to *Dashboard*:

1. Go to *Dashboard* and click *Connect new device*.
1. In the drop-down menu *Device type*, select Windows.
1. Name the device.
    ![Connecting_device *mobile_border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/choose_windows.png)

You can set it up via [AdGuard](#use-adguard-ad-blocker-paid-option) or [AdGuard VPN](#use-adguard-vpn) apps, in [Windows settings](#configure-via-windows-settings), or using the [AdGuard DNS Client](#use-adguard-dns-client).

## Use AdGuard Ad Blocker (paid option)

The AdGuard app lets you use encrypted DNS, making it perfect for setting up AdGuard DNS on your Windows device. You can choose from various encryption protocols. Along with DNS filtering, you also get an excellent ad blocker that works across your entire system.

1. [Install the app](https://adguard.com/adguard-windows/overview.html) on the device you want to connect to AdGuard DNS.
1. Open the app.
1. Click *Settings* at the top of the app's home screen.
    ![Settings *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/windows_step3.png)
1. Select the *DNS Protection* tab from the menu on the left.
    ![DNS protection *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/windows_step4.png)
1. Click your currently selected DNS server.
    ![DNS server *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/windows_step5.png)
1. Scroll down and click *Add a custom DNS server*.
    ![Add a custom DNS server *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/windows_step6.png)
1. In the DNS upstreams field, paste one of the following addresses. If you’re not sure which one to prefer, choose DNS-over-HTTPS.
    ![DoH server *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/windows_step7_1.png)
    ![Create server *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/windows_step7_2.png)
1. Click *Save and select*.
    ![Save and select *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/windows_step8.png)
1. The DNS server you’ve added will appear at the bottom of the *Custom DNS servers* list.
    ![Custom DNS servers *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/windows_step9.png)

All done! Your device is successfully connected to AdGuard DNS.

## Use AdGuard VPN

Not all VPN services support encrypted DNS. However, our VPN does, so if you need both a VPN and a private DNS, AdGuard VPN is your go-to option.

1. Install AdGuard VPN.
1. Open the app and click *Settings*.
1. Select *App settings*.
    ![App settings *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_vpn/windows_step4.png)
1. Scroll down and select *DNS servers*.
    ![DNS servers *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_vpn/windows_step5.png)
1. Click *Add custom DNS server*.
    ![Add custom DNS server *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_vpn/windows_step6.png)
1. In the *Server address* field, paste one of the following addresses. If you’re not sure which one to prefer, select DNS-over-HTTPS.
    ![DoH server *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_vpn/windows_step7_1.png)
    ![Create server *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_vpn/windows_step7_2.png)
1. Click *Save and select*.
    ![Save and select *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_vpn/windows_step8.png)

All done! Your device is successfully connected to AdGuard DNS.

## Configure via Windows settings

:::note

Available only on Windows 11.

:::

1. In the *Search* bar on the taskbar, type **Ethernet settings** or **Wi-Fi settings**, depending on your connection type.
Click the network (Wi-Fi ID or Ethernet) you want to configure.
    ![Search *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/windows_settings_step_1.png)
1. Scroll to *DNS server assignment* and click *Edit*.
    ![DNS server assignment *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/windows_settings_step_2.png)
1. Change DNS settings to *Manual*.
1. Toggle the IPv4 switch to *On*.
1. Enter the following DNS server addresses:
    - Preferred DNS: `94.140.14.49`
    - Alternate DNS: `94.140.14.59`
1. Turn *DNS over HTTPS template* to *On (manual template)* and enter your personal DNS address. You can find it in the Dashboard under *Server settings* → *Devices* → *Devices settings* → DNS-over-HTTPS.
1. Click *Save*. That’s it — your device is now connected to AdGuard DNS!
    ![Save DNS settings *border](https://cdn.adtidy.org/content/kb/dns/private/new_dns/connect/windows_ab/windows_settings_done.png)

## Use AdGuard DNS Client

AdGuard DNS Client is a versatile, cross-platform console tool that allows you to connect to AdGuard DNS using encrypted DNS protocols.

More details can be found in [different article](/dns-client/overview/).

## Configure plain DNS

If you prefer not to use extra software for DNS configuration, you can opt for unencrypted DNS. You have two choices: using linked IPs or dedicated IPs.

- [Dedicated IPs](/private-dns/connect-devices/other-options/dedicated-ip.md)
- [Linked IPs](/private-dns/connect-devices/other-options/linked-ip.md)
