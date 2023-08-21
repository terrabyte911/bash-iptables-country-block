# ipblock.sh
This bash script will add a rule to ban entire countries using iptables and ipset.

Just add the required country codes to script and run.

The script will download ip's from http://www.ipdeny.com into a ipset set called 'blockall'

A rule is added that blocks all ports except http/https.

## Installation

Download: `wget https://raw.githubusercontent.com/terrabyte911/bash-iptables-country-block/main/ipblock.sh && chmod +x ipblock.sh`

Execute: `./ipblock.sh`


