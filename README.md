![GitHub last commit](https://img.shields.io/github/last-commit/hagezi/dns-blocklists)![GitHub issues](https://img.shields.io/github/issues/hagezi/dns-blocklists)![GitHub closed issues](https://img.shields.io/github/issues-closed/hagezi/dns-blocklists)[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fhagezi%2Fdns-blocklists&count_bg=%23754400&title_bg=%235F5F5F&icon=awesomelists.svg&icon_color=%23E7E7E7&title=visitors&edge_flat=false)](https://github.com/hagezi/dns-blocklists)[![shields.io Stars](https://img.shields.io/github/stars/hagezi/dns-blocklists)](https://github.com/hagezi/dns-blocklists/stargazers)
## DNS Blocklists - *For a better internet!*
### Table of Contents
1. [Overview](#overview)
2. [Multi light](#light) - *Hand brush: Light protection*
3. [Multi normal](#normal) - *Broom: All-round protection*
4. [Multi pro](#pro) - *Big broom: Extended protection*
5. [Multi pro++](#proplus) - *Sweeper: Maximum protection (more aggressive)*
6. [Fake](#fake) - *Protects against internet scams, traps & fakes!*
7. [Threat Intelligence Feeds](#tif) - *Increases security significantly!*
8. [DoH/VPN/TOR/Proxy Bypass](#bypass) - *Prevent methods to bypass your DNS!*
9. [Safesearch not supported](#safesearch) - *Prevent the use of search engines that do not support safesearch!*
10. [Dynamic DNS](#dyndns) - *Protects against the malicious use of dynamic DNS services!*
11. [Personal](#personal) - *My manually maintained blacklist*
12. [Native Tracker](#native) - *Broadband tracker of devices and operating systems*
13. [Credits](#credits)
14. [Supporter](https://github.com/hagezi/dns-blocklists/stargazers) - *Leave a star (top right)!*
15. [Recommendation](#recommendation)
16. [Online DNS Services](#dnsservices): [RethinkDNS](#rethinkdns) / [NextDNS](#nextdns)
17. [About](#about) / [Referral Domains](#referral)
18. [Sources/Statistics](usedsources.md)
19. [Raw data collection](https://github.com/hagezi/dns-data-collection) - *Data collection to generate the DNS blocklists*

### ***Multi - Cleans the Internet and protects your privacy!*** <a name="overview"></a>
*An all in one DNS blocklist in **various versions (light, normal, pro and pro++)**. It can be used as a stand alone blocklist. For every region. Blocks ads, affiliate, tracking, metrics, telemetry, fake, phishing, malware, scam, coins and other "crap". Based on [various blocklists](usedsources.md).*

#### ***Multi blocklist version and size overview:***
| Version | Hosts | Pro | Normal | Light | [Fake](https://github.com/hagezi/dns-blocklists#fake) | [TIF](https://github.com/hagezi/dns-blocklists#tif) | [Bypass](https://github.com/hagezi/dns-blocklists#bypass) | [Safesearch](https://github.com/hagezi/dns-blocklists#safesearch) | [DDNS](https://github.com/hagezi/dns-blocklists#dyndns) | [Personal](https://github.com/hagezi/dns-blocklists#personal) | 
|:--------|---:|:------:|:-----:|:----:|:---:|:------:|:----------:|:--------:|:--------:|:--------:|
| [Light](https://github.com/hagezi/dns-blocklists#light)             | 348293<br>138072     |   |   | = | X | P |   |   |   | X |
| [Normal](https://github.com/hagezi/dns-blocklists#normal)       | 1132757<br>296980     |   | = | X | X | P |   |   |   | X |
| [Pro](https://github.com/hagezi/dns-blocklists#pro)              | 1376331<br>395962         | = | X | X | X | P |   |   |   | X |
| [Pro++](https://github.com/hagezi/dns-blocklists#proplus)    | 1560324<br>443861 | ++ | X | X | X | P |   |   |   | X |
           
*X = contains the named lists in the column header*       
*P = partially contains the named list in the column header*       
*++ = more sources, more aggressive*
              
---
         
### ***Multi LIGHT*** - **Light protection** <a name="light"></a>
      
*Hand brush - Cleans the Internet and protects your privacy! Blocks Ads, Tracking, Metrics, some Malware and Fake.*
          
**Entries:** *348293 domains/hosts - 138072 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#light)         
         
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/light.txt) | PiHole, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/light.txt) | PiHole, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/light.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/light.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/light.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

### ***Multi NORMAL*** - **All-round protection** <a name="normal"></a>
      
*Broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
**Entries:** *1132757 domains/hosts - 296980 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#multi)        
          
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/multi.txt) | PiHole, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/multi.txt) | PiHole, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/multi.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/multi.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/multi.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

### ***Multi PRO*** - **Extended protection** <a name="pro"></a>
      
*Big broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
**Entries:** *1376331 domains/hosts - 395962 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#pro)        
           
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.txt) | PiHole, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/pro.txt) | PiHole, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/pro.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

### ***Multi PRO++*** - **Maximum protection** <a name="proplus"></a>

*Sweeper - Aggressive cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
*More aggressive version of the Multi PRO blocklist. It may contain false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains. Reported false positive domains are removed from the list!*

**Entries:** *1560324 domains/hosts - 443861 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#proplus)    
                                                
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.plus.txt) | PiHole, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/pro.plus.txt) | PiHole, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.plus.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/pro.plus.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro.plus.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.plus.txt) | DNSCrypt, DNSCloak, YogaDNS, ...  |
                         
**Expires:** *24 hours (update frequency)*

---

### ***Fake - Protects against internet scams, traps & fakes!*** <a name="fake"></a>
*An blocklist for blocking fake stores, -news, -science, -streaming, rip-offs, cost traps and co.*         
        
**Entries:** *11636 domains/hosts - 6076 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#fake)
       
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/fake.txt) | PiHole, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/fake.txt) | PiHole, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/fake.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/fake.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/fake.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/fake.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Threat Intelligence Feeds - Increases security significantly!*** <a name="tif"></a>
*An blocklist for blocking malware, crypto, coin, scam, spam and phishing. Blocks domains known to spread malware, launch phishing attacks and host command-and-control servers.*         
        
**Entries:** *1265094 domains/hosts - 646872 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#tif)
         
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/tif.txt) | PiHole, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/tif.txt) | PiHole, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt) | ~~AdGuard~~ (oversized, limited to 535000 rules!), AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/tif.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/tif.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/tif.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *24 hours (update frequency)*

---

### ***DoH/VPN/TOR/Proxy Bypass - Prevent methods to bypass your DNS!*** <a name="bypass"></a>

*Prevent method to bypass your DNS. To ensure the bootstrap is your DNS server you must redirect or block standard DNS outbound (TCP/UDP 53) and block all DNS over TLS (TCP 853) outbound.*
          
***The block list exists in two versions:***

#### ***Complete Edition - Encrypted DNS Servers, VPN, TOR, Proxies*** <a name="bypass_all"></a>
       
**Entries:** *971 domains/hosts - 884 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#doh-vpn-proxy-bypass)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/doh-vpn-proxy-bypass.txt) | PiHole, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/doh-vpn-proxy-bypass.txt) | PiHole, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/doh-vpn-proxy-bypass.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/doh-vpn-proxy-bypass.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh-vpn-proxy-bypass.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

#### ***Encrypted DNS Servers only*** <a name="bypass_dns"></a>
       
**Entries:** *352 domains/hosts - 287 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#doh)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/doh.txt) | PiHole, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/doh.txt) | PiHole, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/doh.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/doh.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Safesearch not supported - Prevent the use of search engines that do not support safesearch!*** <a name="safesearch"></a>
*An blocklist for blocking search engines that do not support safesearch.*         
        
**Entries:** *138 domains/hosts - 135 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#nosafesearch)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/nosafesearch.txt) | PiHole, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/nosafesearch.txt) | PiHole, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nosafesearch.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/nosafesearch.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/nosafesearch.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/nosafesearch.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Dynamic DNS blocking - Protects against the malicious use of dynamic DNS services!*** <a name="dyndns"></a>
*An blocklist for blocking dynamic DNS services to protect against malicious use in phishing campaigns and others.*         
        
**Entries:** *802 domains/hosts - 800 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#dyndns)
            
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/dyndns.txt) | PiHole, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/dyndns.txt) | PiHole, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/dyndns.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/dyndns.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/dyndns.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/dyndns.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Personal - My manually maintained blacklist*** <a name="personal"></a>
*Contains blockable hosts that I found during DNS monitoring. Ads, Tracking, Badware and more.*         
        
**Entries:** *896 domains/hosts - 593 compressed domains*
       
| Format | Link | Can be used for |
|:-------|:-----|:----------------|
| Domains  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/personal.txt) | PiHole, eBlocker, Diversion, OpenSnitch, PersonalDNSfilter, pfBlockerNG, PersonalBlocklist | 
| Hosts    | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/personal.txt) | PiHole, eBlocker, AdAway, uMatrix, DNS66, GasMask, HostFileEditor, OpenSnitch              |
| Adblock  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/personal.txt) | AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave |
| Unbound  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/personal.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/personal.txt) | DNSMasq                                                              | 
| Wildcard | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/personal.txt) | DNSCrypt, DNSCloak, YogaDNS, ...                                               |

**Expires:** *Updated regularly*

---

### ***Native Tracker - Broadband tracker of devices and operating systems*** <a name="native"></a>
*Blocks native broadband tracker from devices and operating systems that frequently run at the operating system level and track your activity.*         
                  
| Device | Domains | Hosts | Adblock | Unbound | DNSMasq | Wildcard |
|:-------|:--------|:------|:--------|:--------|:--------|:---------|
| Apple (iOS, macOS, tvOS) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.apple.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.apple.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.apple.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.apple.blacklist.conf) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.apple.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.apple.txt) |
| Microsoft (Windows, Office, MSN) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.winoffice.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.winoffice.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.winoffice.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.winoffice.blacklist.conf) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.winoffice.txt) | [RAW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.winoffice.txt) |

**Expires:** *Updated regularly*

---

### ***Credits*** <a name="credits"></a>

**A huge thank you to the following list maintainers of the [sources used](usedsources.md), alphabetical order:**

*abpindo, abpvn, abuse.ch, adaway, adguardteam, adroitadorkhan, amnestytech, anti-ad, anudeepnd, assoechap, azorult-tracker.net, badmojr, barbblock, bigdargon, bkrucarci, blahdns, bongochong, botvrij.eu, cats-team, cbuijs, cert-agid.gov.it, cmiksche, craiu, d3ward, dandelionsprout, davidonzo, developerdan, digitalside.it, drsdavidsoft, durablenapkin, easylist, easylist-lithuania, easylist-thailand, elliotwutingfeng, fademind, fanboy, firebog.net, frogeye.fr, gioxx, guardicore, hblock, hexxiumcreations, hole.cert.pl, hoshsadiq, hpthreatresearch, hufilter, iam-py-test, infinitytec, jawz101, jdlingyu, jkrejcha, joewein.net, kargig, kees1958, kevinthomas0, kriskintel.com, laicure, laniksj, lassekongo83, latvian-list, list-kr, logroid, malware-filter, marco-acorte, matomo-org, metamask, migueldemoura, mitchellkrogza, molinero.dev, mvps.org, netlab.360, nextdns, nitrohorse, notonmyshift, notracking, oisd.nl, olbat, oneoffdallas, ookangzheng, paulgb, perflyst, phishing.army, piperun, piquark6046, polishfiltersteam, prodaft, quidsup, rescure.me, scafroglia93, shadowwhisperer, shallalist, shreyasminocha, sjhgvr, smed79, someonewhocares.org, stamparm, stanev.org, stevenblack, stopforumspam.com, systemjargon, t145, th3m3, tiuxo, tomasko126, ublockorigin, ultimate-hosts, ut1, velesila, wally3k, yourduskquibbles, yous, yoyo.org, zerodot1, zoso.ro*

---

### ***Recommendation*** <a name="recommendation"></a>

*As a network-wide DNS blocker, I recommend using [Pi-Hole](https://pi-hole.net/), [Adguard Home](https://adguard.com) or [eBlocker](https://eblocker.org/). I prefer [Adguard Home](https://adguard.com).*
        
*DNS blocker offer a good protection of privacy by blocking tracking, metrics and telemetry. They can be used to block the vast majority of ads, malware, scam, fake and co, but not everything can be blocked at the DNS level!         
Therefore, I* ***additionally*** *recommend the use of a browser content blocker such as [uBlock](https://ublockorigin.com) or [AdGuard](https://adguard.com) with the appropriate block lists (EasyList, AdGuard, uBlock, ...) or the use of [eBlocker](https://eblocker.org/) with enabled pattern blocker as a network wide content blocker. I use [uBlock](https://ublockorigin.com) in my desktop browser and [AdGuard](https://adguard.com) on my mobile devices.*

### ***Online DNS Services*** <a name="dnsservices"></a>        

*If you don't run your own DNS server on your home network or if you are looking for additional protection for your mobile devices when they are not connected to the home network, then I recommend one of the following DNS services:*

#### ***RethinkDNS - free*** <a name="rethinkdns"></a>

*In [RethinkDNS](https://rethinkdns.com) you can use my blocklists:*

| Blocklists | DNS-over-HTTPS | DNS-over-TLS | Apple Mobileconfig |
|:-----------|:---------------|:-------------|:-------------------|
| PRO + TIF  | https://sky.rethinkdns.com/1:AAoACBAA | 1-aafaacaqaa.max.rethinkdns.com | [Visit](https://sky.rethinkdns.com/1:AAoACBAA) and click on the red apple  |
| PRO PLUS + TIF | https://sky.rethinkdns.com/1:AAoACAgA | 1-aafaacaiaa.max.rethinkdns.com | [Visit](https://sky.rethinkdns.com/1:AAoACAgA) and click on the red apple |

#### ***NextDNS - limited free/paid*** <a name="nextdns"></a>        

***Unfortunately, my blocklists have not yet been included in [NextDNS](https://nextdns.io/?from=jvpyfdfc).***
           
My blocklist recommendations for [NextDNS](https://nextdns.io/?from=jvpyfdfc) are:*          

| Profile | NextDNS Blocklists                                          |
|:--------|:----------------------------------------------------------------------------------------------------|
| Normal     | 1Hosts (Lite) + AdGuard DNS filter + Steven Black + oisd + notracking                            |
| Aggressive | 1Hosts (Pro) + AdGuard DNS filter + Steven Black + oisd + notracking + NoTrack Tracker Blocklist |

---

### ***About*** <a name="about"></a>

<p align="center"><a href="https://github.com/hagezi/dns-blocklists/graphs/contributors"><img src="https://contrib.rocks/image?repo=hagezi/dns-blocklists" /></a></p>
<p align="center"><i><b>"If the plan doesn‘t work, change the plan but never the goal."<br>There's no place like 127.0.0.1!</b></i></p>

*The blocklists are based on [various sources](usedsources.md) and my own [blacklists](https://github.com/hagezi/dns-data-collection/tree/main/data). They were designed to avoid [false positive domains](whitelist.txt) as much as possible without losing effectiveness and efficiency. [Dead hosts](deadlist.txt) are regularly removed from the lists to keep them as small as possible. Please [report false positive](https://github.com/hagezi/dns-blocklists/issues) domains.*         
*They are updated and maintained daily.*

#### Referral Domains <a name="referral"></a>

*Affiliate and tracking links (referral domains) that appear frequently on offer web pages, in emails or in search results are allowed in my lists.  These are mostly called only after manual clicking on a link and are not used to display advertising.
If these are blocked, the first hit links from search results, for example, no longer work.* 
          
*There are users who want to block referral domains anyway, so for each list I show the domains that were whitelisted because of referral. You can see them in the list of [used sources](usedsources.md) behind the link "whitelisted referral domains" per list.
This list can then be used as a blocklist to "undo" the whitelisting of referral domains.*
          
*Allowing referral domains in my lists is equivalent to the [NextDNS](https://nextdns.io/?from=jvpyfdfc) feature "Privacy > Allow Affiliate & Tracking Links".*
          
#### Support Me <a name="support"></a>

*If you like the project and you can benefit from it, leave a star (top right) and become a [stargazer](https://github.com/hagezi/dns-blocklists/stargazers)!*
         
***Thanks for your support!***

---

### ***Keep the internet clean!*** - Join the Matrix: [#dnsblocklists:matrix.org](https://matrix.to/#/#hagezi:matrix.org)

---
