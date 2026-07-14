# DadaSMPTools 1.4.5

<p align="center"><img src="assets/dadasmp-logo.png" alt="DadaSMP" width="180"></p>


> Custom Minecraft plugin with dedicated commands and server-side features.

![Minecraft](https://img.shields.io/badge/Minecraft-1.20%2B-green?style=for-the-badge)
![Paper](https://img.shields.io/badge/Paper%20%2F%20Spigot-Compatible-blue?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.4.5-purple?style=for-the-badge)

## Overview

**DadaSMPTools 1.4.5** is a custom Minecraft plugin for Paper/Spigot servers.

Custom Minecraft plugin with dedicated commands and server-side features.

| Field | Value |
| --- | --- |
| Plugin | `DadaSMPTools` |
| Version | `1.4.5` |
| Category | Gameplay and Utilities |
| Main class | `it.dadasmp.tools.DadaSMPTools` |
| Dependencies | `depend: [Vault]; softdepend: [BetterEconomy, LuckPerms]` |

## Features

| Feature | Description |
| --- | --- |
| Clean package | Public jar name without server-specific labels. |
| Server ready | Designed for Paper/Spigot Minecraft servers. |
| Configurable | Uses Bukkit/Paper plugin configuration where supported. |
| Commands | Includes in-game commands documented below. |
| Permissions | Includes permission nodes documented below. |

## Commands

| Command | Description | Usage | Permission | Aliases |
| --- | --- | --- | --- | --- |
| `/pay` | Paga un giocatore | `/pay <giocatore> <importo>` | `dadasmptools.pay` | None |
| `/tpa` | Richiede un teletrasporto o gestisce il TPA automatico | `/tpa <giocatore|auto>` | `dadasmptools.tpa` | None |
| `/tpaccept` | Accetta una richiesta TPA | `/tpaccept` | `dadasmptools.tpa` | `[tpyes]` |
| `/tpdeny` | Rifiuta una richiesta TPA | `/tpdeny` | `dadasmptools.tpa` | `[tpno]` |
| `/claim` | Protegge il chunk corrente | `/claim` | None | None |
| `/unclaim` | Rimuove il claim corrente | `/unclaim` | None | None |
| `/trust` | Autorizza un giocatore nel claim | `/trust` | None | None |
| `/untrust` | Rimuove un giocatore dal claim | `/untrust` | None | None |
| `/claiminfo` | Mostra le informazioni del claim | `/claiminfo` | None | None |
| `/dbackup` | Crea un backup completo | `/dbackup` | None | None |
| `/dpregen` | Pregenera i chunk | `/dpregen` | None | None |
| `/dlag` | Mostra diagnostica TPS e memoria | `/dlag` | None | None |
| `/dlookup` | Cerca modifiche ai blocchi vicine | `/dlookup` | None | None |
| `/dinspect` | Attiva ispezione blocchi stile CoreProtect | `/dinspect` | None | `[dinspectore, inspect]` |
| `/drollback` | Ripristina modifiche ai blocchi | `/drollback` | None | None |
| `/dflags` | Mostra i flag anti-cheat | `/dflags` | None | None |
| `/ss` | Avvia e gestisce un controllo staff | `/ss <player|panel|back|pass|cancel|ban>` | None | None |
| `/serverping` | Mostra ping e prestazioni del server | `/serverping [player]` | None | None |
| `/bug` | Segnala e gestisce i bug del server | `/bug report <descrizione>` | None | `[bag]` |
| `/dtools` | Mostra i comandi DadaSMPTools | `/dtools` | None | None |
| `/withelist` | Gestisce la whitelist di manutenzione DadaSMP | `/withelist <true|false|add|remove|list|status> [giocatore|motivo]` | None | `[dwhitelist, manutenzione]` |

## Permissions

| Permission | Default | Description |
| --- | --- | --- |
| `dadasmptools.pay` | `true` | Permission node. |
| `dadasmptools.tpa` | `true` | Permission node. |
| `dadasmptools.tpa.receive` | `true` | Permission node. |
| `dadasmptools.claim` | `true` | Permission node. |
| `dadasmptools.claim.limit.4` | `true` | Permission node. |
| `dadasmptools.claim.unlimited` | `op` | Permission node. |
| `dadasmptools.claim.bypass` | `op` | Permission node. |
| `dadasmptools.claim.admin` | `op` | Permission node. |
| `dadasmptools.anticheat.bypass` | `op` | Permission node. |
| `dadasmptools.anticheat.alerts` | `op` | Permission node. |
| `dadasmptools.anticheat.admin` | `op` | Permission node. |
| `dadasmptools.backup` | `op` | Permission node. |
| `dadasmptools.pregen` | `op` | Permission node. |
| `dadasmptools.lag` | `op` | Permission node. |
| `dadasmptools.audit.lookup` | `op` | Permission node. |
| `dadasmptools.audit.rollback` | `op` | Permission node. |
| `dadasmptools.staff` | `op` | Permission node. |
| `dadasmptools.ss` | `op` | Permission node. |
| `dadasmptools.serverping` | `op` | Permission node. |
| `dadasmptools.bug.report` | `true` | Permission node. |
| `dadasmptools.bug.staff` | `op` | Permission node. |
| `dadasmptools.whitelist` | `op` | Permission node. |

## Installation

1. Download the jar from the `release` folder.
2. Put it inside your server `plugins` folder.
3. Restart the server.
4. Configure the plugin if it creates a configuration folder.

Compiled jar:

`release/DadaSMPTools-1.4.5.jar`

## Support

For support, bug reports or setup help, join the Discord server:

https://discord.gg/yXrDpKCGAs

## License

All rights reserved. Redistribution, resale or modification is not allowed without written permission from DadaSMP.
