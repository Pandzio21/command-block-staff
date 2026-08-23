# Badges

Paste under the banner/logo on each page. All nine are verified to resolve to live data.

CurseForge project id **1585146**, Modrinth slug **command_block_staff_addon**.

The `<div align="center">` wrapper centres them under the logo on GitHub. Modrinth and CurseForge may
strip the wrapper - if they do the badges still render, just left-aligned, so it is safe to paste the
same block everywhere.

## GitHub (README.md)

```markdown
<div align="center">

[![Download from Modrinth](https://img.shields.io/modrinth/v/command_block_staff_addon?style=flat&logo=modrinth&logoColor=white&label=Download%20from%20Modrinth&color=00af5c)](https://modrinth.com/mod/command_block_staff_addon/versions)
[![Download from CurseForge](https://img.shields.io/badge/Download_from-CurseForge-f16436?style=flat&logo=curseforge&logoColor=white)](https://www.curseforge.com/minecraft/mc-mods/command-block-staff-addon/files)
[![Modrinth downloads](https://img.shields.io/modrinth/dt/command_block_staff_addon?style=flat&logo=modrinth&logoColor=white&label=downloads&color=00af5c)](https://modrinth.com/mod/command_block_staff_addon)
[![CurseForge downloads](https://img.shields.io/curseforge/dt/1585146?style=flat&logo=curseforge&logoColor=white&label=downloads&color=f16436)](https://www.curseforge.com/minecraft/mc-mods/command-block-staff-addon)
[![Minecraft](https://img.shields.io/modrinth/game-versions/command_block_staff_addon?style=flat&label=Minecraft&color=54ba58)](https://modrinth.com/mod/command_block_staff_addon/versions)
![Loaders](https://img.shields.io/badge/loaders-Fabric_%7C_NeoForge-dbb18a?style=flat)
[![Requires AvM Staff Mod](https://img.shields.io/badge/requires-AvM_Staff_Mod-9b59d0?style=flat)](https://modrinth.com/mod/avm-staff)
[![Report a bug](https://img.shields.io/github/issues/Pandzio21/command-block-staff?style=flat&logo=github&label=Report%20a%20bug&color=24292f)](https://github.com/Pandzio21/command-block-staff/issues)
[![Docs](https://img.shields.io/badge/Read_the-docs-8ca1af?style=flat&logo=readthedocs&logoColor=white)](https://pandzio21.github.io/command-block-staff/)

</div>
```

## Modrinth description

Without the "Download from Modrinth" badge - on the Modrinth page it links to the page you are on.

```markdown
<div align="center">

[![Download from CurseForge](https://img.shields.io/badge/Download_from-CurseForge-f16436?style=flat&logo=curseforge&logoColor=white)](https://www.curseforge.com/minecraft/mc-mods/command-block-staff-addon/files)
[![Modrinth downloads](https://img.shields.io/modrinth/dt/command_block_staff_addon?style=flat&logo=modrinth&logoColor=white&label=downloads&color=00af5c)](https://modrinth.com/mod/command_block_staff_addon)
[![CurseForge downloads](https://img.shields.io/curseforge/dt/1585146?style=flat&logo=curseforge&logoColor=white&label=downloads&color=f16436)](https://www.curseforge.com/minecraft/mc-mods/command-block-staff-addon)
[![Minecraft](https://img.shields.io/modrinth/game-versions/command_block_staff_addon?style=flat&label=Minecraft&color=54ba58)](https://modrinth.com/mod/command_block_staff_addon/versions)
![Loaders](https://img.shields.io/badge/loaders-Fabric_%7C_NeoForge-dbb18a?style=flat)
[![Requires AvM Staff Mod](https://img.shields.io/badge/requires-AvM_Staff_Mod-9b59d0?style=flat)](https://modrinth.com/mod/avm-staff)
[![Report a bug](https://img.shields.io/github/issues/Pandzio21/command-block-staff?style=flat&logo=github&label=Report%20a%20bug&color=24292f)](https://github.com/Pandzio21/command-block-staff/issues)
[![Docs](https://img.shields.io/badge/Read_the-docs-8ca1af?style=flat&logo=readthedocs&logoColor=white)](https://pandzio21.github.io/command-block-staff/)

</div>
```

## CurseForge description

Same idea, minus the CurseForge one. Paste in the editor's **Markdown** mode.

```markdown
<div align="center">

[![Download from Modrinth](https://img.shields.io/modrinth/v/command_block_staff_addon?style=flat&logo=modrinth&logoColor=white&label=Download%20from%20Modrinth&color=00af5c)](https://modrinth.com/mod/command_block_staff_addon/versions)
[![Modrinth downloads](https://img.shields.io/modrinth/dt/command_block_staff_addon?style=flat&logo=modrinth&logoColor=white&label=downloads&color=00af5c)](https://modrinth.com/mod/command_block_staff_addon)
[![CurseForge downloads](https://img.shields.io/curseforge/dt/1585146?style=flat&logo=curseforge&logoColor=white&label=downloads&color=f16436)](https://www.curseforge.com/minecraft/mc-mods/command-block-staff-addon)
[![Minecraft](https://img.shields.io/modrinth/game-versions/command_block_staff_addon?style=flat&label=Minecraft&color=54ba58)](https://modrinth.com/mod/command_block_staff_addon/versions)
![Loaders](https://img.shields.io/badge/loaders-Fabric_%7C_NeoForge-dbb18a?style=flat)
[![Requires AvM Staff Mod](https://img.shields.io/badge/requires-AvM_Staff_Mod-9b59d0?style=flat)](https://modrinth.com/mod/avm-staff)
[![Report a bug](https://img.shields.io/github/issues/Pandzio21/command-block-staff?style=flat&logo=github&label=Report%20a%20bug&color=24292f)](https://github.com/Pandzio21/command-block-staff/issues)
[![Docs](https://img.shields.io/badge/Read_the-docs-8ca1af?style=flat&logo=readthedocs&logoColor=white)](https://pandzio21.github.io/command-block-staff/)

</div>
```

## Left out on purpose

Three badges that look obvious but render broken text on this project:

- `github/v/release/...` - **"no releases found"**. This repo is the source-less issue tracker; the
  jars live on Modrinth and CurseForge, not in GitHub releases.
- `github/languages/top/...` - **"none"**, for the same reason: no source is published here.
- `github/stars/...` - reads 0. Add it once there are stars worth showing.

And one that works but looks wrong: `curseforge/v/1585146` prints the latest FILE's display name, so
it renders **"Command Block Staff 0.4.0 For NeoForge"** and comes out 419px wide against Modrinth's
209px. Hence the plain CurseForge button. If you rename the CurseForge file display names to just the
version number, the live badge becomes usable:

```markdown
[![Download from CurseForge](https://img.shields.io/curseforge/v/1585146?style=flat&logo=curseforge&logoColor=white&label=Download%20from%20CurseForge&color=f16436)](https://www.curseforge.com/minecraft/mc-mods/command-block-staff-addon/files)
```

Shields has no `minecraft`, `fabricmc` or `neoforge` logo, which is why those two badges carry text only.
