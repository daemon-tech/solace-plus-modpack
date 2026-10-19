<div align="center">

# Solace Plus

**A cozy vanilla-plus modpack built around Solace Shaders. Warm light, soft textures, living mobs and smooth, high FPS.**

**[Solace Shaders](https://modrinth.com/shader/solace-shaders)** · **[Whimscape](https://modrinth.com/resourcepack/whimscape)** by kavast · **[Fresh Animations](https://modrinth.com/resourcepack/fresh-animations)** by FreshLX · **[Discord](https://discord.gg/N2GBXFuBvG)**

</div>

---

This repository holds the [packwiz](https://packwiz.infra.link) source of Solace Plus for **Minecraft 26.3 · Fabric · client-only**. Every mod, resource pack and the shader pack are referenced from Modrinth; no third-party files are stored here.

## Build

```sh
packwiz refresh
packwiz mr export
```

This produces `Solace Plus-<version>.mrpack`, which can be imported into the Modrinth App or any `.mrpack` launcher.

## Layout

- `pack.toml`, `index.toml` – pack metadata and file index
- `mods/`, `resourcepacks/`, `shaderpacks/` – Modrinth references
- `config/yosbr/` – first-install defaults (enabled resource packs, Solace on). Applied once, never overwrites player settings.

## Credits

See [CREDITS.md](CREDITS.md). Solace Shaders by Daemon · Whimscape by kavast · Fresh Animations by FreshLX · all mods belong to their authors.

**License:** All Rights Reserved for the pack configuration. Included projects keep their own licenses.
