# Firewall Policy Register
**Status: Example policies only; not deployed or verified.**

| ID | Source | Destination | Service | Proposed action | Implemented | Tested |
|---|---|---|---|---|---|---|
| P-01 | LAN | DMZ test server | TCP 80/443 | Allow | No | No |
| P-02 | DMZ | LAN | Any | Deny | No | No |
| P-03 | LAN | Authorized DNS | DNS | Allow selectively | No | No |

Record actual rule order, interface, direction, stateful behavior, logs, and evidence after deployment.
