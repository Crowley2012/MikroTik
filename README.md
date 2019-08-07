# MikroTik

## Security
https://wiki.mikrotik.com/wiki/Manual:Securing_Your_Router

## DNS
IP > DNS
- Servers: 1.1.1.1
IP > DNS > Static
- Name: DNS Server
- Address: 1.1.1.1

## Services
IP > Services
    Services running on router. If you disable ftp, you disable router's own ftp service.
    Disable everything but leave winbox enabled

IP > Firewall > Service Ports
    Helpers for connection tracking and NAT. If you disable ftp, you won't be able to mark data connections as related and active mode won't work for clients behind NAT.

## Users
System > Users
    Manage users

System > Users > Active Users
    View active users
