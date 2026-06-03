# Commands

## Player Commands

| Command | Permission | Description |
| --- | --- | --- |
| `/shop` | `shopplus.shop` | Open the main shop menu. |
| `/servershop` | `shopplus.shop` | Open server shop categories. |
| `/playershop` | `shopplus.playershop` | Open player marketplace. |
| `/sell` | `shopplus.sell` | Open sell menu. |
| `/worthlist [page]` | `shopplus.worthlist` | View live buy/sell prices. |
| `/list <price>` | `shopplus.playershop` | List the held item stack. |
| `/mylist` | `shopplus.playershop` | Show your active listings. |
| `/unlist <number>` | `shopplus.playershop` | Remove one active listing. |
| `/trade <player>` | `shopplus.trade` | Send a trade request. |
| `/tradeaccept [player]` | `shopplus.trade` | Accept a trade request. |
| `/tradedeny [player]` | `shopplus.trade` | Deny a trade request. |
| `/link discord <discord id or username>` | `shopplus.merra` | Start Merra Discord linking. |
| `/linkmerra <discord id or username>` | `shopplus.merra` | Compatibility linking command. |
| `/verifymerra <code>` | `shopplus.merra` | Verify a Merra link code. |

## Admin And Reward Commands

| Command | Permission | Description |
| --- | --- | --- |
| `/shopreload` | `op` / admin wiring | Reload ShopPlus configuration. |
| `/shopreport [label]` | `mcnp.report.generate` | Generate a market report. |
| `/generatereport [label]` | `mcnp.report.generate` | Compatibility report command. |
| `/resetshopprices` | `mcnp.shop.reset` | Reset live market prices. |
| `/shopplusvotereward <player>` | `shopplus.vote.reward` | Apply vote reward hooks. |
| `/shopplusmerrareward <player> <amount> [reason]` | `shopplus.merra.reward` | Grant Merra points through ShopPlus. |

## Compatibility Aliases

ShopPlus includes MCNP compatibility aliases such as `/mcnpshop`, `/mcnpsell`, `/mcnplist`, `/mcnpmylist`, `/mcnpunlist`, `/mcnptrade`, `/mcnptradeaccept`, `/mcnptradedeny`, `/mcnpworthlist`, `/mcnpresetshopprices`, and `/mcnpgeneratereport`.
