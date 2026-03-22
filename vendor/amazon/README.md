# Amazon (AWS)

**Zero dependency. Fully replaced.**

BlackRoad replaced every AWS service:
- EC2 → Raspberry Pis ($38/mo vs $185-700/mo)
- S3 → MinIO on Cecilia
- RDS → PostgreSQL on 3 nodes
- ElastiCache → Redis on Alice
- Route 53 → PowerDNS on Lucidia + Gematria
- Lambda → Cloudflare Workers (also being replaced)
- CloudFront → Caddy on Gematria

The "Illusion of Complexity" paper documents the full cost comparison.

→ [Sovereignty stack](../../infrastructure/sovereignty/)
→ [Research papers](../../research/papers/illusion-of-complexity/)
