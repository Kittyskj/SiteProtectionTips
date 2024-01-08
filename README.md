# My rules for Cloudflare and Tips how to protect your site/server.

## High tier Anti-DDoS providers

- ReactLabs (Paid) <a href="https://react.su/">click</a>
> Not recomended to use overprice + Russia, but defence good
- CloudFlare (Free/Paid) <a href="https://www.cloudflare.com/">click</a>	
- DDoS-Guard (Trial Request/Paid) <a href="https://ddos-guard.net/ru">click</a>	
- Stormwall (Trial Request/Paid) <a href="https://stormwall.pro/">click</a>
- NexusPipe (Paid) <a href="https://nexuspipe.com/">click</a>
> Protection Very good and cheap


## Medium tier Anti-DDoS providers
- Aeza (Free/Paid) <a href="https://aeza.net/protection">click</a>
> Not recomended to use after 03.02.2023 to many downtime on servers, not stable protect.
> Not recomended to use Russian owner and russian country hackers may scam you risk
- CasT-Security (Paid) <a href="https://cast-security.ru/">click</a>
> Not recomended to use overprice.
- GreyWeb (Paid) <a href="https://greyweb.cloud/ddos-protection/">click</a>

## Low tier Anti-DDoS providers
- Bytfend (Paid) <a href="https://bytefend.to/">click</a>	
> Not recomended to use. Because they resales ovh and have small network no own DC and poor protection methods

## CF Rules
1.[Challenge] Interactive Challenge (Fixed)

2.[ASN №1] Interactive Challenge

3.[ASN №2] Interactive Challenge 

4.[Standart Cheking for bads №1] Block 

5.[Standart Cheking for bads №2] Block

6.[Stupid Geo Block] Block "Don't use this rule xD"

7.[Protecion against bad browsers] Block/Manged chellange


## Scripts to protetc L7 

- PowShield <a href="https://github.com/RuiSiang/PoW-Shield">click</a>	
> Reverse Proxy, like baloo
- BalooProxy <a href="https://github.com/41Baloo/balooProxy">click</a>	
> Baloo proxy like CF but better then it. Highly recomend to use it.
For better attack blocking and site uptime use minimum 4core 8gb 1gb/s server
- vDDoS-Protection <a href="https://github.com/duy13/vDDoS-Protection">click</a>	
> Good but no updates and no new technologies.
For better attack blocking and site uptime use minimum 4core 8gb 1gb/s server
- Nginx-Lua-Anti-DDoS <a href="https://github.com/C0nw0nk/Nginx-Lua-Anti-DDoS">click</a>	
> Good but no updates and no new technologies.

## Scripts that prevent attacks on L3/L4
- YukiAntiDDoS <a href="http://github.com/yuk1c/antiddos">click</a>	
> Good waiting for new features
- China IPtables <a href="https://www.provgn.com/knowledgebase/4/Filtering-DDoS-Attacks-with-IPTables-.html">click</a>	
> Didn't check it yet
## Stresstest site using script's
- DDoSify (Free/Script) <a href="https://github.com/ddosify/ddosify">click</a>	
> DDoSify simple script to do virtual load test your site and create any scenarios
- MHDDoS (Free/Script) <a href="https://github.com/MatrixTM/MHDDoS">click</a>	
## Useful scripts
- Cyber-Shield <a href="https://github.com/voidptr2x/Cyber-Shield">click</a>	
>Monitoring and analyze packets income to server.
