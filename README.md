# Reese Royster

Linux tinkerer and self-hoster: Omarchy (Arch + Hyprland) on the desktop, Omarchy Server on the home server, Python and shell glue in between.

## What I'm Working On

- 🖥️ Omarchy/Hyprland tooling, and keeping a whole machine reproducible as a git repo
- 📱 Android: a native ZQuest Classic port. [v0.2.0-alpha](https://github.com/reeseroyster/ZQuestClassic-Mobile/releases/tag/v0.2.0-alpha) ships touch controls, Bluetooth gamepads, quick saves
- 🗄️ Self-hosting on one box: Jellyfin/arr media stack, Obsidian LiveSync, Proton VPN exit node, all Podman

## Stack

Python, Bash, C++/Gradle, JavaScript/TypeScript · Arch/Omarchy, systemd, Podman, Tailscale, Neovim, Git

## Projects

| Project | What it is | Stack |
| --- | --- | --- |
| [bootdev-guided-projects](https://github.com/reeseroyster/bootdev-guided-projects) | Boot.dev course projects, one folder each, including the [webflyx](https://github.com/reeseroyster/webflyx) Git-course repo | Python, Git |
| [ZQuestClassic-Mobile](https://github.com/reeseroyster/ZQuestClassic-Mobile) | Unofficial native Android port of ZQuest Classic; releases tagged `vX.Y.Z` | Gradle, C++ |

**Boot.dev certs:** [Python](https://www.boot.dev/certificates/24635134-df98-448c-9aff-253cd3d9bb6d) · [Linux](https://www.boot.dev/certificates/b44dbc7f-2d4d-4d46-927b-d778b719048a) · [BookBot](https://www.boot.dev/certificates/b845a655-9fa2-472f-8014-8b138a763284) · [Git](https://www.boot.dev/certificates/2296fb40-7254-43f0-95b9-2a0e74bbe271) · [OOP](https://www.boot.dev/certificates/817bf81a-9ae7-4a71-919b-622cc2b85b4f)

## Contributions

**Merged upstream:** [omamail](https://github.com/huacnlee/omamail), helper script paths for scoped Omarchy 4.x plugins · [lastbook](https://github.com/jonnyace/lastbook), Arch packaging, AV1 dependency, bundled AI runner, `lib/` path, pip probe order.

**Reports that landed as fixes:**

- [omarchy-server #688](https://github.com/MyOwnDataCenter/Server/issues/688): a listing's `userns_mode` was requested as a system permission, then silently dropped by the Podman engine; fixed on main in #844
- [omarchy-server #870](https://github.com/MyOwnDataCenter/Server/issues/870): an app's card said *running* while its container was dead; fixed on main in #874
- [flea #456](https://github.com/thisisgm/flea/issues/456): non-deterministic parallel test runs · [omaplug #29](https://github.com/fross100/omaplug/issues/29): silent marketplace-catalog fetch failures

**Open upstream:** [omarchy](https://github.com/omacom/omarchy) (trackpad phantom contacts after lid resume, idle wake while locked), [xpadneo #640](https://github.com/atar-axis/xpadneo/pull/640) (Xbox Nano support), [omarchy-proton-drive](https://github.com/placq/omarchy-proton-drive), [omaproton-vpn](https://github.com/grichard99/omaproton-vpn) (keyring corruption), plus the odd patch wherever a bug bites.
