# MikroTik

## Manual
- https://wiki.mikrotik.com/wiki/Manual:TOC

## Startup
- https://wiki.mikrotik.com/wiki/Manual:First_time_startup

## Security
- https://wiki.mikrotik.com/wiki/Manual:Securing_Your_Router

## Troubleshooting
- https://wiki.mikrotik.com/wiki/Manual:Troubleshooting_tools

## Configurations
- https://docs.google.com/document/d/1gdymxjQvyZmwu2C3FY7Uvb_VPnCCyKxwKYnDcLFv6aU/edit
- https://www.justinho.com/blog/2017/07/15/hap-ac-lite.html
- https://www.reddit.com/r/mikrotik/comments/7qz3d8/is_the_hap_ac_lite_or_hap_ac_a_legit_alternative/
- http://rickfreyconsulting.com/dns-filtering-using-mikrotik-pi-hole-and-opendns/

## DNS
### IP > DNS
- Servers: 1.1.1.1
    
### IP > DNS > Static
- Name: DNS Server
- Address: 1.1.1.1

## DHCP
- Change lease time to day+

## Services
### IP > Services
- Services running on router. If you disable ftp, you disable router's own ftp service.
- Disable everything but leave winbox enabled

### IP > Firewall > Service Ports
- Helpers for connection tracking and NAT. If you disable ftp, you won't be able to mark data connections as related and active mode won't work for clients behind NAT.

## Users
### System > Users
- Manage users

### System > Users > Active Users
- View active users

### SSID
- Name the same for 2.4 and 5 allows devices to choose