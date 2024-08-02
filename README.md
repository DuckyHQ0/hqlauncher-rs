![hqlauncher.rs cover](./assets/hqlauncher-cover.png)

## Planning stages - 0.0-alpha

**Experimental** build of HQLauncher for making a Minecraft launcher from scratch in Rust, using Tauri.

!! - This is a Cargo workspace, see individual projects in their folders.

### msmc.rs

A Microsoft and Minecraft authentication library in Rust.

Fast, simple, secure. Uses Tao and Wry to create a window for authentication, and reqwest.
[(auth api docs)](https://mojang-api-docs.gapple.pw/authentication/msa)

Inspired by the original JS [MSMC](https://github.com/Hanro50/MSMC)

### mcln.rs

A Minecraft launcher library in Rust. Fast, and easy.

Will support easy instance creation:

- Vanilla
- Fabric
- Forge
- Quilt
- Modrinth
- Curseforge

And other useful features.

### hql

Frontend for the HQLauncher app. Uses Tauri, React, Vite, and MorphUI.

### Licenses & Contributing

Feel free to contribute. Each license is in their own folder, and they're all `GPL-3.0`.
