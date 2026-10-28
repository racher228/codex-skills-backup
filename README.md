# Codex skills backup

This repository backs up the 13 user-installed skills found in `~/.codex/skills`
on 28 October 2026. It does not include Codex's built-in `.system` skills or
plugin-managed skills. Each folder under `skills/` is an installed copy, so this
repository is not a mirror of the upstream projects or their Git histories.

| Skills | Original source | License |
| --- | --- | --- |
| `check-ui-clean-roblox` | [TemporaryLooker22/Check-UI-Clean-Roblox](https://github.com/TemporaryLooker22/Check-UI-Clean-Roblox), restored separately [here](https://github.com/racher228/Check-UI-Clean-Roblox) | MIT, as stated in the original README; see the folder's `LICENSE` and `RESTORATION.md` |
| `stud-ui-clean-roblox` | [TemporaryLooker22/Stud-UI-Clean-Roblox](https://github.com/TemporaryLooker22/Stud-UI-Clean-Roblox) | MIT; see the folder's `LICENSE` and `THIRD_PARTY_NOTICES.md` |
| `roblox-vfx-animation` | [adnvli/vfxskill](https://github.com/adnvli/vfxskill) | MIT; see the folder's `LICENSE`, `CREDITS.md`, and `third_party/` |
| `router`, `roblox-luau`, `roblox-datastores`, `roblox-ui`, `roblox-networking`, `roblox-characters`, `roblox-physics`, `roblox-studio-workflow`, `game-feel`, `game-ui-ux` | [gamedev-skills/awesome-gamedev-agent-skills](https://github.com/gamedev-skills/awesome-gamedev-agent-skills) | Apache 2.0; see `licenses/awesome-gamedev-agent-skills/LICENSE` and `NOTICE` |

All original authors retain their rights. This repository is a personal backup
published under the upstream license terms; its GitHub owner is not claiming
original authorship.

## Restore on another computer

Copy the desired folders from `skills/` into your Codex skills directory, for
example `C:\Users\<you>\.codex\skills\` on Windows. Each copied folder should
contain its own `SKILL.md`. Restart Codex or start a new chat to load the skills.

The `router` skill references other skills from its upstream collection; only
the ten listed skills from that collection were installed and backed up here.
