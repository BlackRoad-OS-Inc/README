# Vendors — 14 External Dependencies

Every vendor is a **tenant, not owner**. API keys are BlackRoad's permission tokens.

| Vendor | Relationship | Dependency Level |
|--------|-------------|-----------------|
| [Stripe](stripe/) | Payment processing | Only external payment dep |
| [Cloudflare](cloudflare/) | Edge infrastructure | Heavy (migrating to sovereign) |
| [GoDaddy](godaddy/) | Domain registrar | Registrar only |
| [DigitalOcean](digitalocean/) | 2 droplets | Edge + backup |
| [GitHub](github/) | Code mirror | Mirror of Gitea (primary) |
| [Google](google/) | Drive storage | 2 drives via rclone |
| [Anthropic](anthropic/) | Claude Code sessions | Work-for-hire, no IP |
| [OpenAI](openai/) | Cadence agent | Work-for-hire, no IP |
| [Meta](meta/) | LLaMA models | Open weights, forked |
| [xAI](xai/) | Gaia agent | Work-for-hire, no IP |
| [Microsoft](microsoft/) | GitHub parent, VS Code | Indirect |
| [Apple](apple/) | macOS (Alexandria) | Hardware only |
| [NVIDIA](nvidia/) | Benchmarked against | Zero dependency (Hailo-8) |
| [Amazon](amazon/) | AWS replaced | Zero dependency |
