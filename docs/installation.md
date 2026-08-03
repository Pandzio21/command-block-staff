# Installation

This is an add-on, so it needs the base **AvM Staff Mod** underneath it. Minecraft **1.21** or **1.21.1**,
Java **21**.

Grab the jar for your loader — `commandblockstaff-<version>-fabric.jar` or `-neoforge.jar`.

=== "Fabric"

    | Required | Minimum |
    |---|---|
    | [AvM Staff Mod](https://modrinth.com/mod/avm-staff) | 1.0.0-beta.1 |
    | [Fabric API](https://modrinth.com/mod/fabric-api) | 0.102.0+1.21 |
    | [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin) | 1.11.0+kotlin.2.0.0 |
    | [Architectury API](https://modrinth.com/mod/architectury-api) | 13.0.8 |

=== "NeoForge"

    | Required | Minimum |
    |---|---|
    | [AvM Staff Mod](https://modrinth.com/mod/avm-staff) | 1.0.0-beta.1 |
    | [NeoForge](https://neoforged.net/) | 21.0.164 |
    | [Kotlin for Forge](https://modrinth.com/mod/kotlin-for-forge) | 5.4.0 |
    | [Architectury API](https://modrinth.com/mod/architectury-api) | 13.0.8 |

Those are minimums — anything newer in the same 1.21.x line is fine.

## Nice to have

- **[GeckoLib](https://modrinth.com/mod/geckolib)** 4.5.0+ — only for the animated model when you
  **[ride the staff](ride.md)**. Flying works without it; you just don't get the animation.
- **[Mod Menu](https://modrinth.com/mod/modmenu)** (Fabric) — puts a config button in the mod list.
- **[Cloth Config](https://modrinth.com/mod/cloth-config)** — a nicer settings screen. Without it you get
  the built-in one, which does the same job.

None of these ship inside the jar, so install whichever you want yourself.

!!! warning "GeckoLib on 1.21.1"

    GeckoLib's **1.21** build says it supports 1.21.1, but one of its own mixins finds nothing to attach to
    there and crashes the game while it's loading resources. That happens without this add-on installed at
    all — it's not ours to fix.

    On 1.21.1: either skip GeckoLib, or use a build made for 1.21.1. On 1.21 the normal one is fine. This
    is exactly why it's optional here.

## Getting the staff

Put a **command block** into a Royal Staff or Scepter of Friendship — that's the base mod's insert key,
**R** by default — and hold it:

<figure markdown="span">
  ![Command block in the staff](assets/staffview3d.png){ width="150" }
</figure>

**Z + scroll** picks an ability and you're away.
