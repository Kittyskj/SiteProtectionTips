# My Rules for Cloudflare and Tips on How to Protect Your Site/Server

## High-Tier Anti-DDoS Providers

- **ReactLabs (Paid)** <a href="https://react.su/">click</a>  
  > **Not recommended to use** – overpriced and based in Russia, but the protection is good.
- **Cloudflare (Free/Paid)** <a href="https://www.cloudflare.com/">click</a>  
- **DDoS-Guard (Trial Request/Paid)** <a href="https://ddos-guard.net/ru">click</a>  
- **Stormwall (Trial Request/Paid)** <a href="https://stormwall.pro/">click</a>  

## Medium-Tier Anti-DDoS Providers

- **Aeza (Free/Paid)** <a href="https://aeza.net/protection">click</a>  
  > **Not recommended to use after 03.02.2023** – too much downtime, unstable protection.  
  > **Not recommended** due to Russian ownership, as Russian hackers may scam you.  
- **CasT-Security (Paid)** <a href="https://cast-security.ru/">click</a>  
  > **Not recommended** – overpriced.  
- **GreyWeb (Paid)** <a href="https://greyweb.cloud/ddos">click</a>  

## Low-Tier Anti-DDoS Providers

- **Bytfend (Paid)** <a href="https://bytefend.to/">click</a>  
  > **Not recommended** – resells OVH, has a small network, no own data center, and poor protection methods.  

## Cloudflare Rules

1. **[Challenge]** Interactive Challenge (Fixed)  
2. **[ASN #1]** Interactive Challenge  
3. **[ASN #2]** Interactive Challenge  
4. **[Standard Check for Bad Traffic #1]** Block  
5. **[Standard Check for Bad Traffic #2]** Block  
6. **[Stupid Geo Block]** Block *(Don't use this rule xD)*  
7. **[Protection Against Bad Browsers]** Block/Managed Challenge  

## Scripts to Protect L7  

- **PowShield** <a href="https://github.com/RuiSiang/PoW-Shield">click</a>  
  > Reverse proxy, similar to Baloo.  
- **BalooProxy** <a href="https://github.com/41Baloo/balooProxy">click</a>  
  > A proxy like Cloudflare but better. **Highly recommended.**  
  > For better attack mitigation and uptime, use at least a **8-core, 16GB RAM, 2.5Gbps server**.  
- **vDDoS-Protection** <a href="https://github.com/duy13/vDDoS-Protection">click</a>  
  > Good, but lacks updates and modern technologies.  
  > For better attack mitigation and uptime, use at least a **8-core, 16GB RAM, 2.5Gbps server**.  
- **Nginx-Lua-Anti-DDoS** <a href="https://github.com/C0nw0nk/Nginx-Lua-Anti-DDoS">click</a>  
  > Good, but lacks updates and modern technologies.  

## Scripts to Prevent L3/L4 Attacks  

- **YukiAntiDDoS** <a href="https://github.com/yuk1c/antiddos">click</a>  
  > Good, waiting for new features.  

## Stress Testing Scripts  

- **DDoSify (Free/Script)** <a href="https://github.com/ddosify/ddosify">click</a>  
  > A simple script to simulate virtual load testing on your site and create custom attack scenarios.  
- **MHDDoS (Free/Script)** <a href="https://github.com/MatrixTM/MHDDoS">click</a>  

## Useful Scripts  

- **Cyber-Shield** <a href="https://github.com/voidptr2x/Cyber-Shield">click</a>  
  > Monitors and analyzes incoming packets to the server.  
