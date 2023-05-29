<div align="center">
  <a href="https://github.com/intergrav/vulkadrenaline">
    <img src="https://raw.githubusercontent.com/intergrav/Branding/main/vulkadrenaline/vulkadrenaline_text_256h.png" alt="Logo" height="90">
  </a>
  <br />
  <br />
  <p align="center">
    Experimental, testing-only branch of Adrenaline that replaces the Sodium renderer with Vulkan. Here be dragons!
    <br />
    <a href="https://github.com/intergrav/vulkadrenaline/issues">Report Bugs</a>
    ·
    <a href="https://github.com/intergrav/vulkadrenaline/issues">Request Features</a>
  </p>
  <a href="https://modrinth.com/modpack/vulkadrenaline"><img src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/compact-minimal/available/modrinth_vector.svg" alt="Available on Modrinth"></a>
  <a href="https://discord.gg/36Tv44cYte"><img src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/compact-minimal/social/discord-singular_vector.svg" alt="Chat on Discord"></a>
  <a href="https://gitpod.io/from-referrer/"><img src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/compact-minimal/supported/gitpod_vector.svg" alt="Ready for Gitpod"></a>
</div>

> **Here be dragons!**
> Vulkadrenaline is a *testing-only* branch of Adrenaline and should **not** be used in production. VulkanMod is currently in an alpha stage. Expect issues.

Vulkadrenaline is an experimental branch of Adrenaline that replaces Sodium with VulkanMod, with tested builds. Mod compatibility is not guaranteed, and incompatible mods are removed. For more information about Adrenaline, see the [Modrinth page](https://modrinth.com/modpack/adrenaline).

## 🔥 Performance

On my machine, Vulkadrenaline has lower framerates than Adrenaline in most cases. I am on an NVIDIA GTX 1080 TI, AMD Ryzen 5 3600, with 2 GB ram allocated to each instance. I am using Fedora Minimal + GNOME running on X11. **Keep in mind that this can heavily vary on some systems - I advise you test yourself if you are curious which runs better. You may score higher with Vulkadrenaline on your end.** These were done with Vulkadrenaline 1.0.0 and Adrenaline 1.13.0, both running on 1.19.4.

|  | Adrenaline | Vulkadrenaline |
|---|---|---|
| Plains | 1430-1445 | 1200-1215 |
| Jungle | 1200-1230 | 930-940 |

## ❌ Removed mods

Some mods are removed for VulkanMod to be compatible. Here they are:

- Sodium
- Indium
  - Depends on Sodium and is not needed because EBE is incompatible
- ImmediatelyFast
- EnhancedBlockEntities
- Exordium

## 🤔 Missing versions?

Since this modpack is only meant for testing, I will only be targetting the most popular versions and Fabric. It's not beneficial for me to test many versions at a time on a project like this, and simply wastes my time. Please don't ask for more. Currently, here is what's actively supported:

- 1.19.4
- 1.19.2
- 1.18.2

Versions before 1.18.x will not be supported as VulkanMod is not available for those. 1.19.3 is not available as *most* mods from 1.19.3 work fine on 1.19.4.

## 🍉 Sponsor
Need a fast, reliable Minecraft server? Use my code `devin` for 25% off your first month of any MelonCube server, supporting me in the process. Click this image for more information. You can also setup my server-side performance pack called [Adrenaserver](https://modrinth.com/modpack/adrenaserver) to improve your server's optimization while still allowing vanilla clients to join.

[![MelonCube Image](https://www.meloncube.net/partners/custom-banners/fc383dd6-4bb3-424f-b4fb-f540acb27e8b.png)](https://meloncube.net/devin)

> *This description was copied from the [Modrinth page](https://modrinth.com/modpack/vulkadrenaline). It may not be formatted correctly.*
