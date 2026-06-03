# Merra Integration

Merra is the global currency layer for ShopPlus. It is designed so multiple Minecraft servers can share one Merra balance system without exposing the universal database.

## Production Model

```text
Customer server
  -> ShopPlus plugin
  -> https://api.merra.network
  -> Merra API server
  -> Merra database
```

ShopPlus should never ship with direct Merra database credentials.

## Account Linking

Players can start linking from Minecraft:

```text
/link discord <discord id or username>
/verifymerra <code>
```

The Merra API verifies the link and returns only the data that ShopPlus needs.

## Placeholder

If PlaceholderAPI is installed, ShopPlus registers:

```text
%mcnp_merra_points%
```

Use this in scoreboards, TAB, holograms, or menus to show the linked player's Merra balance.

## Security Notes

- Keep Merra API keys private.
- Rotate API keys if a server is sold, transferred, leaked, or compromised.
- Use HTTPS for public Merra API traffic.
- Use timestamped signed requests for production deployments.
- Do not post keys in public GitHub issues.
