<h1> Wat is HestiaCP? </h1>

![Test](https://camo.githubusercontent.com/7b2c9babb427264c2ea1e839df416840ad60baf5aa516146d804903520c540c6/68747470733a2f2f68657374696163702e636f6d2f696d672f73637265656e5f4865737469615365727665722d6461726b2e706e67)



Hestia Control Panel is ontworpen om beheerders een eenvoudig te gebruiken web- en opdrachtregelinterface te bieden, waarmee ze snel webdomeinen, mailaccounts, DNS-zones en databases kunnen implementeren en beheren vanuit één centraal dashboard, zonder het gedoe van het handmatig implementeren en configureren van afzonderlijke componenten of diensten.

<h1> Features en servicen </h1>

Apache2 en NGINX met PHP-FPM
Meerdere PHP-versies (5.6 - 8.1, 8.0 als standaard)
DNS-server (Bind) met clusteringmogelijkheden
POP/IMAP/SMTP maildiensten met Anti-Virus, Anti-Spam, en Webmail (ClamAV, SpamAssassin, Sieve, Roundcube, Rainloop)
MariaDB en/of PostgreSQL databases
Let's Encrypt SSL ondersteuning met wildcard certificaten
Firewall met brute-force aanvalsdetectie en IP-lijsten (iptables, fail2ban, en ipset).

<h1> Hoe kan je HestiaCP installeren? </h1>
**Stap 1: Zorg ervoor dat uw server een ondersteund besturingssysteem draait (amd64 of arm64):**

  * Debian 9
  * Debian 10
  * Debian 11
  * Ubuntu 18.04 LTS
  * Ubuntu 20.04 LTS

**Stap 2: Log in als de systeemgebruiker (root):**

U moet verbinding maken met uw server als root, ofwel rechtstreeks vanaf de console ofwel op afstand via SSH.

**Stap 3: Download de installer:**
```bash
wget https://raw.githubusercontent.com/hestiacp/hestiacp/release/install/hst-install.sh
```
**Stap 4: Start het installatieprogramma en volg de aanwijzingen:**
```bash
bash hst-install.sh
```
**Om een onbeheerde installatie uit te voeren (met standaardinstellingen):**
```bash
bash hst-install.sh --interactive no --email email@domain.tld --password p4ssw0rd --hostname hostname.domain.tld -f
```

# Special thanks to:

*     De makers van HestiaCP
* De HestiaCP Github