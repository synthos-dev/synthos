# SynthOS

Operating system for VR users and general purpose gaming

<img alt="Discord" src="https://img.shields.io/discord/:serverId">


## Scope

- Non-conflicting patches and modifications that improve hardware support upon the Linux Kernel or userspace drivers included
- Small, upstreamable gaming-specific improvements that cannot be included easily outside of `/usr`
- LIMITED non-flatpaked apps, flatpak/homebrew _focus_ where possible (or cases where flatpaked mesa is a problem)
- Retroactively removing things out-of-scope in the future and moving them to flatpak/other methods if possible.
- Non-upstreamable patches are strictly not allowed

## Ideal workflow

1. Plug in your headset
2. (optionally) do a little bit of first-time/recurring setup specific to headset
3. Have fun!

Headsets like the Bigscreen Beyond 2e should work out of the box, instead of requiring manual kernel compilation, patched versions of libraries and others.

The goal is really to have as little setup and have the operating system be as boring as possible, no special apps, the more upstream things as possible, little to no things patched, small presets and things to make the system nicer to use but nothing specific to this image that you couldn't get by getting OpenGamingCollective packages

## Current Roadmap

- WayVR/SteamLinuxFixes built-in to the image
- PSVR2 ootb support with ignition
- Quest 2/3/Pro support OOTB with WiVRN
- Bigscreen Beyond 2e support
- Valve Index support
- Aarch64 builds (maybe)
- Steam Frame support (far future, if someone does it would be neat)

## Art!

- All of it is made by [Ashe](https://bsky.app/profile/did:plc:jjabohkerkwku5uukkz7sztq)! TYSM! :3
