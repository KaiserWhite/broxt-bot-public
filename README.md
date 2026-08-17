# BROXT Discord Bot

BroXT Bot Invite Link: https://discord.com/channels/1430668121366069390/1525537876559921303/1525538021905141820

## Slash Commands

| Command | Type | Description | Permission (env var) |
| --- | --- | --- | --- |
| `/help` | Slash | Show the command list (ephemeral by default). | Open to everyone |
| `/rumor` | Slash | Open the Rumor post modal. | `RUMOR_ROLE_IDS` |
| `/news` | Slash | Open the News post modal. | `NEWS_ROLE_IDS` |
| `/goss` | Slash | Roll a `d8` GOSS outcome; always public. | `GOSS_ROLE_IDS` |
| `/seen` | Slash | Roll and post a `d10` SEEN result with modifiers. | `SEEN_ROLE_IDS` |
| `/uors` | Slash | Roll `2d6` for a UORS check plus SEEN modifier. | `UORS_ROLE_IDS` |
| `/distance` | Slash | Roll AD&D 1e encounter distance. | `DISTANCE_ROLE_IDS` |
| `/dunder` | Slash | Post a random image from `DUNDER_IMAGE_DIR`. | `DUNDER_ROLE_IDS` |
| `r <formula>` | Chat message | Roll dice (`2d6`, `1d20+5`, `4d6k3`, `m1`-`m4`). | `DICE_ROLE_IDS` |

 ** "ROLE_IDS" defaulted to @everyone **
