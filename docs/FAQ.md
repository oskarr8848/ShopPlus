# FAQ

## Is ShopPlus open source?

No. This repository publishes the jar, documentation, checksums, and issue tracker. Source code is not included.

## Is it free?

The current public build is free early access. Commercial licensing may be added later.

## Does ShopPlus require Merra?

No. Normal shops use Vault economy. Merra is optional and is used for global points, linking, placeholders, and Merra-specific rewards.

## Why do purchases fail even though a player has money?

Usually Vault is missing, the economy provider is not connected to Vault, or the shop item is configured to use a different currency than the player balance shown on the scoreboard.

## Can I use it on a Velocity network?

Yes, but ShopPlus itself is a backend server plugin. Voting, proxy routing, and public network security should be handled by your proxy and backend server setup.

## Where do I report bugs?

Open a GitHub issue and include:

- Paper version
- ShopPlus version
- Vault economy plugin
- relevant console logs
- steps to reproduce

Do not include private keys, tokens, private IPs, or database credentials.
