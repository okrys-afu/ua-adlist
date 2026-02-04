# 🇺🇦 MikroTik DFU AdList Hosts

Short adblock / DNS blocklists for the **Defence Forces of Ukraine**.

Purpose:
- Block moral-harming resources
- Block russian propaganda and hostile media (TODO)
- Block malware, phishing, tracking, and ad networks (TODO)
- Reduce attack surface and unwanted traffic (TODO)

Format:
- `hosts` (0.0.0.0 domain)

Intended use:
- DFU units and infrastructure
- Volunteer and support networks
- Secure personal setups of DFU personnel

Instructions
- For console setup run (replace with a desired filename at the end):
```routeros
ip/dns/adlist/add ssl-verify=no url=https://raw.githubusercontent.com/okrys-afu/ua-adlist/refs/heads/main/hosts/legal_casino.txt
```
