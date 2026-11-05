# Hetzner Cloud

Auto-provision Hetzner Cloud from PeltyCMS orders

Official provisioning module for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Providers who sell hosting, VPS, game panels or cloud and need auto-create on payment.

## Features

- Create services on **Hetzner Cloud** when the customer pays
- Suspend, unsuspend and terminate follow the Pelty service lifecycle
- Map Pelty products to packages / plans on the remote panel
- API tokens stay in Pelty secrets
- MythicCloud panel linking for authenticated installs

## How it works

1. Install **Hetzner Cloud** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/provisioning-hetzner-cloud) inside Pelty Admin → Addons.
2. Open Pelty Admin → Products, map a product to the Hetzner Cloud module, and save API credentials.
3. Customers hit checkout / login / order flow as usual — Hetzner Cloud runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working Hetzner Cloud credentials
- Outbound HTTPS from your panel

## Get it

**[Hetzner Cloud on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/provisioning-hetzner-cloud)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
