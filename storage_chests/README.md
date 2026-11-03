# Storage Chests (content mod for Horizon)

Five storage blocks, each with 27 slots, facing, and an open/closed look.

| Block | Recipe | Mining |
|---|---|---|
| Iron Storage Chest | 8 iron ingots around a vanilla chest | Pickaxe, stone or better |
| Gold Storage Chest | 8 gold ingots around an Iron Storage Chest | Pickaxe, iron or better |
| Diamond Storage Chest | 8 diamonds around a Gold Storage Chest | Pickaxe, iron or better |
| Netherite Storage Chest | Smithing table: Diamond Storage Chest + netherite ingot + netherite upgrade template | Pickaxe, diamond; very tough (hardness 50, blast resistance 1200) |
| Crystal Storage Chest | 8 amethyst shards around an Iron Storage Chest | Pickaxe, iron or better; glows (light 6) |

Contents spill out when a chest is broken. Custom names are kept on the dropped item.

## Try it
Launcher > Settings > Game arguments:  --dev-mod "/path/to/storage_chests"   then Play.

## Package it
    cargo install --git https://github.com/horizon-rust/horizon cargo-horizon-mod
    cd storage_chests
    cargo horizon-mod build
    cargo horizon-mod check target/horizon-mod/storage_chests.hmod
Put the .hmod in your horizon-mods folder and enable it in Options > Mods.
