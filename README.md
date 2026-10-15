# Enterprise Network Security & Firewall Lab

**Status:** Planned; implementation and testing pending.

A lab plan for pfSense firewall policies, network segmentation, traffic inspection, and authorized validation.



## Objectives
- Configure isolated WAN, LAN, and DMZ virtual networks.
- Document and test allow/deny firewall policies.
- Analyze traffic using Wireshark and verify permitted services using Nmap.
- Record sanitized logs, findings, and remediation recommendations.

## Proposed topology
```text
Virtual NAT / WAN
      |
   pfSense
   /     \
 LAN     DMZ
client  server
```

## Roadmap
- [ ] Deploy pfSense in an isolated virtual lab
- [ ] Record software versions, interfaces, and network addressing
- [ ] Configure LAN and DMZ and test routing
- [ ] Implement and verify firewall rules
- [ ] Capture and analyze Wireshark traffic
- [ ] Run authorized Nmap validation
- [ ] Document findings and redacted evidence

## Documentation
- [Lab setup](docs/lab-setup.md)
- [Firewall policy register](docs/firewall-policy-register.md)
- [Test results](docs/test-results.md)
- [Security findings](docs/security-findings.md)

## Attribution
Inspired by [varunmajmudar-ctrl/pfSense-Network-Security-Lab](https://github.com/varunmajmudar-ctrl/pfSense-Network-Security-Lab). Original screenshots, reports, and other source materials belong to their author and are not presented here as my own work. Verify license and permissions before reusing original content. These documentation templates are independently written.

## Scope
Use only isolated systems and networks you own or are authorized to test. Never commit secrets, private credentials, or sensitive logs.
