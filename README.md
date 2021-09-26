# Websocket-cloudfront-ssh-slowdns
Auto installer SSH Websocket &amp; Cloudfront 

ssh+ovpn+websocket+slowdns+cloudfront only you can check my repo

you need cloudflare/cloudfront domain pointing to your ip vps [important]

# Command Install
Copy this code & paste in your vps terminal

```
apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/dopzone/Websocket-cloudfront-ssh/main/install.sh && chmod +x install.sh && screen -S setup ./install.sh
```

## About

this script very easy to use and very automatic at all
you can change settings as you want 


### Port

------------------------------------------------------------
   > Service & Port    
 - OpenSSH                 : 22    
 - OpenVPN                 : TCP 1194, UDP 2200, SSL 442    
 - Stunnel4                : 442, 777    
 - Dropbear                : 109, 143    
 - Websocket               : 2082   
 - WS SSL               : 2082   
 - Cloudfront              : 2081 (use vps & account amazon & PM Admin For setting)   
 - Squid Proxy             : 3128, 8080 (limit to IP Server)    
 - Badvpn                  : 7100, 7200, 7300    
 - Nginx                   : 81    
 - Wireguard               : 7070    
 - L2TP/IPSEC VPN          : 1701    
 - PPTP VPN                : 1732    
 - SSTP VPN                : 444    
 - Shadowsocks-R           : 1443-1543    
 - SS-OBFS TLS             : 2443-2543    
 - SS-OBFS HTTP            : 3443-3543    
 - V2RAY Vmess TLS         : 8443    
 - V2RAY Vmess None TLS    : 80    
 - V2RAY Vless TLS         : 2083    
 - V2RAY Vless None TLS    : 8880    
 - Trojan                  : 2087    
 - Slowdns                 : 53, 2222   

 > Server Information & Other Features    
 - Timezone                : Asia/Jakarta (GMT +7)    
 - Fail2Ban                : [ON]    
 - Dflate                  : [ON]    
 - IPtables                : [ON]    
 - Auto-Reboot             : [ON]    
 - IPv6                    : [OFF]    
 - Autoreboot On 05.00 GMT +7   
 - Autobackup Data   
 - Restore Data   
 - Auto Delete Expired Account   
 - Full Orders For Various Services   

### Contacts me

  Telegram                : t.me/Z0NEX    

------------------------------------------------------------
