# Gematria — Edge Node

**The Edge — TLS termination, public gateway**

| Spec | Value |
|------|-------|
| Device | DigitalOcean Droplet |
| Location | NYC3 |
| Role | Public TLS edge, DNS, VPN hub |

## Services

- [Caddy](caddy/) — automatic HTTPS for 151 domains
- [Ollama](ollama/) — 6 models for edge inference
- [PowerDNS](powerdns/) — ns1.blackroad.io authoritative DNS
- [WireGuard](wireguard/) — VPN hub connecting to all Pi nodes

## Notes

- Internet-facing edge — all public traffic enters here
- Caddy handles Let's Encrypt certificates automatically
- WireGuard mesh hub — routes traffic to Pi fleet via encrypted tunnels
