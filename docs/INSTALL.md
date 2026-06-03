# Install ShopPlus

ShopPlus is installed like a normal Bukkit/Paper plugin. The public repository contains only the binary jar and documentation.

## Requirements

| Requirement | Notes |
| --- | --- |
| Paper | `1.21.1+` target |
| Vault | Required economy bridge |
| Economy plugin | Any Vault-compatible economy provider |
| PlaceholderAPI | Optional, needed for placeholders such as `%mcnp_merra_points%` |
| GriefPrevention | Optional, used by claim-related integrations |

## Steps

1. Download `ShopPlus-2.0.jar` from the latest release.
2. Put the jar in your server `plugins/` folder.
3. Make sure Vault and your economy provider are installed.
4. Restart the server.
5. Edit generated config files in `plugins/ShopPlus/`.
6. Run `/shopreload` after config changes.

## Verify

Run these commands in game:

```text
/shop
/sell
/playershop
/worthlist
```

If the shop opens but purchases fail, confirm that Vault is installed and that your economy provider is correctly hooked into Vault.

## Updating

1. Stop the server or schedule a maintenance reload.
2. Replace the old ShopPlus jar with the new jar.
3. Start the server.
4. Check console for the ShopPlus startup section.
5. Run `/shopreload` after reviewing any new config options.

Do not put database credentials in public configs. Merra servers should connect through the Merra API.
