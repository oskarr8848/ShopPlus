# Security Policy

## Reporting Security Issues

Please do not open a public GitHub issue for private key leaks, token leaks, bypasses, or exploit reports.

Send the report privately to the MCNP Network owner/team first, then open a public issue only after the sensitive details are removed.

## Secrets

Never post these in GitHub issues:

- Merra API keys
- Discord bot tokens
- database credentials
- private backend server IPs
- private VPN IPs
- full server config files containing secrets

## Merra API Model

Public ShopPlus installs should communicate with the Merra API over HTTPS. The universal Merra database must stay private and should not be reachable directly by customer servers.
