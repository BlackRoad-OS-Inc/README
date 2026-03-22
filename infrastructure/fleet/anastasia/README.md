# Anastasia — Backup Node

**The Backup — redundancy, failover**

| Spec | Value |
|------|-------|
| Device | DigitalOcean Droplet |
| Location | NYC1 |
| Role | Backup edge, DR failover |

## Services

- [Caddy](caddy/) — backup TLS edge
- [WireGuard](wireguard/) — backup VPN tunnel

## Notes

- Failover node — takes over if Gematria goes down
- Different datacenter (NYC1 vs NYC3) for geographic redundancy
