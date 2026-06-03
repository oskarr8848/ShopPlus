# Configuration

ShopPlus creates its config files in `plugins/ShopPlus/` after the first startup.

## Economy

ShopPlus uses Vault for normal money transactions. Install Vault plus one economy provider before enabling server shops or player listings.

## Merra

Merra is optional for normal shop usage. If enabled, ShopPlus should talk to the hosted Merra API instead of any direct universal database.

Expected production shape:

```text
ShopPlus server plugin
  -> Merra API over HTTPS
  -> Merra service validation
  -> Merra database
```

## Voting

ShopPlus can be configured to listen to vote reward hooks and apply:

- temporary discounts
- LuckPerms rank duration hooks
- Merra point rewards
- server money rewards
- external flight-time reward commands

Exact vote reward wiring depends on the backend voting plugin used by your server.

## Reloading

Use:

```text
/shopreload
```

Prefer `/shopreload` for ShopPlus config edits. Only restart the whole server when updating the jar or changing dependencies.
