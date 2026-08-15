# CONQUERING CRITICAL CARE

<p align="center"><strong>TACTICAL CLINICAL LEARNING RPG</strong></p>
<p align="center"><em>Player Manuals · Command Archives · The World of Continua</em></p>

```text
╔══════════════════════════════════════════════════════════════════╗
║                  THE NIGHT WATCH COMMAND EDITION                ║
║  Read the brief. Learn the field. Keep the handoff unbroken.    ║
╚══════════════════════════════════════════════════════════════════╝
```

Welcome, Commander.

This repository is the public bookshelf for **Conquering Critical Care**, a tactical educational RPG set in the besieged clinical world of **Continua**. These books are written in the spirit of the substantial console manuals of the 1990s: part instruction booklet, part strategy guide, part world almanac — the sort of manual worth reading even when the machine is switched off.

> **Educational use only.** Conquering Critical Care is not a medical device and does not provide patient-specific advice. Always use current evidence, clinical judgement, local protocols, and appropriate senior or multidisciplinary support.

## Choose your manual

| Volume | Best for | Contents |
|---|---|---|
| **[Demo Field Manual](manuals/DEMO_MANUAL.md)** | First-time players and demo participants | Windows and macOS setup, three-castle campaign, controls, question formats, saving, privacy, troubleshooting, and a spoiler-light introduction to Continua |
| **[Full Campaign Command Archive](manuals/FULL_GAME_MANUAL.md)** | Players curious about the complete game | A spoiler-light preview manual: full campaign scale, classes, formations, special moves, realm atlas, selected boss dossiers, advanced modes, strategy, and deeper lore |

## The legend in one page

Continua was never ruled by a crown. It survived through **The Shift**: an unbroken clinical vigil passed from one watch to the next.

Then the great Pathologies crossed the borders.

They did not arrive as a single army. They occupied the gaps between Units: a concern omitted from a handoff, an escalation delayed until dawn, an intervention remembered without its indication, a plan known by one team and absent from the next. The provinces of Continua fell into a broken night. Triage Keep closed its gates. The Sepsis Plains burned with false signals. The Respiratory Ridge disappeared beneath an impossible tide.

The **Shift Oracle**, keeper of the Handoff Scrolls, has called one specialist to command a small field team. You are not a distant general. You will stand beside the roster, make the decisions, document the warning signs, and leave every captured Unit safer than you found it.

Your enemy is not ignorance alone. It is knowledge that fails to travel.

Your oath is simple:

> **Make the patient safer. Make the plan clearer. Leave the next watch stronger.**

## At a glance

### Demo edition

- **3 castles:** Triage Keep, Bacteremia Bluff, and Source Control Stronghold.
- **50 clinical questions** restricted to those castles.
- **1 playable class:** Balanced Intensivist.
- Four difficulty settings and automatic local saving on both Windows and macOS.
- Official Windows and macOS packages distributed through MediaFire; no Node.js or administrator access required.

### Full campaign

- **15 clinical realms** and **45 castles**.
- **22 boss encounters**.
- **8 classes**: four starting disciplines and four advanced evolutions.
- **16 equipable special moves, plus the separate Call AI command**.
- **684 approved clinical questions**.
- Tactical formations, persistent troop reserve, Field Hospital upgrades, handoffs, spaced review, campaign fronts, counterattacks, story choices, daily challenges, the Toxicology Codex, Research Academy, and real-time ultimate encounters.

## Obtaining the game

This repository contains **player documentation only**. The playable packages are hosted separately so the GitHub page remains a light, readable home for the manuals.

### Official demo downloads

The Windows installer and macOS portable ZIP contain the same version 0.4.0 demo; choose the package for your operating system.

| Platform | Package | Official download |
|---|---|---|
| Windows 10/11 | Per-user installer | [Download `Conquering-Critical-Care-Demo-Setup-0.4.0.exe` from MediaFire](https://www.mediafire.com/file/ss3n1gwk8f0goao/Conquering-Critical-Care-Demo-Setup-0.4.0.exe/file) |
| macOS 11 or later | Portable ZIP for Apple Silicon and Intel | [Download `Conquering-Critical-Care-Demo-Mac-0.4.0.zip` from MediaFire](https://www.mediafire.com/file/ytitklcgq7vc81i/Conquering-Critical-Care-Demo-Mac-0.4.0.zip) |

The full campaign is previewed in the Command Archive but is not yet offered as a public download from this repository. Do not download GitHub's automatically generated **Source code (zip)** expecting it to behave like the game.

> **Data note for version 0.4.0:** these public demo packages have no remote analytics service configured and do not transmit gameplay answers. Progress and preferences remain local to the player's browser profile. Any future data-enabled build must be identified and documented separately.

### Windows setup and launch

The Windows package installs only for the current user and creates Desktop and Start menu shortcuts. It does not require Node.js, Python, administrator privileges, or an Internet connection for ordinary play.

Validated Windows installer SHA-256:

```text
92BC53BBC1A12B5B52081C3530684CBE0AE08F1B529425C0522D137CADBE053A
```

The installation folder is:

```text
%LOCALAPPDATA%\Conquering Critical Care Demo
```

To remove it, exit the launcher from the icon beside the Windows clock, delete that folder, and remove any remaining shortcuts. The pilot installer does not create a separate entry in Windows **Installed apps**.

### macOS setup and launch

The macOS download is a portable ZIP, not a `.dmg` or `.pkg` installer. It includes native runtimes for both Apple Silicon and 64-bit Intel Macs and does not require Node.js, Python, administrator privileges, or an Internet connection for ordinary play.

1. Download and extract the complete ZIP with the built-in macOS Archive Utility.
2. Open the extracted `Conquering-Critical-Care-Demo-Mac-0.4.0` folder.
3. Double-click **`Open Demo.command`**.
4. Keep the Terminal window open while playing.
5. To stop the demo, close that Terminal window or press **Control+C**.

Validated macOS ZIP SHA-256:

```text
B9F0CC8AC9F06D5396D350934B1236C7F05EDBCA079B4888994842FEE122A327
```

This first macOS package is not signed or notarized by Apple. If macOS blocks it, Control-click `Open Demo.command`, choose **Open**, and confirm. If required, use **System Settings → Privacy & Security → Open Anyway**. Only do this for the file downloaded from the official link above after verifying its checksum.

To remove the macOS demo, close its Terminal window and move the extracted demo folder to the Trash. Clearing browser site data for `http://127.0.0.1:48173` is optional and removes local progress and preferences.

Read the [Demo Field Manual](manuals/DEMO_MANUAL.md) for complete platform-specific instructions, saving behaviour, privacy information, and troubleshooting.

## The commander's promise

Conquering Critical Care turns clinical knowledge into game systems, but it does not treat medicine as trivia. Correct answers create momentum because good decisions stabilise a team. Harmful choices carry greater consequences because not every error is equivalent. Explanations and references are part of the reward loop, not decoration after the score.

The campaign is designed around five habits:

1. **Read before acting.** The stem defines the battlefield.
2. **Recognise dangerous options.** Avoiding harm matters as much as identifying the ideal intervention.
3. **Manage resources.** Resolve, people, time, and attention are finite.
4. **Review failure.** Missed questions return through spaced review and handoff.
5. **Communicate continuity.** A correct plan that does not survive the next shift is not yet a complete victory.

## A note on fiction and clinical content

The Pathologies, kingdoms, commanders, and military language belong to the fictional world of Continua. Clinical explanations, question answers, and references are educational content and should be read literally rather than as lore.

No fictional victory overrides real-world guidance. Where a game explanation and a current local protocol differ, follow the current protocol and qualified clinical leadership.

## Credits and licence

Concept, clinical curriculum, and scientific supervision: **João Frutuoso, MD**.

- Game code: MIT.
- Clinical content: CC BY-NC-SA.
- Manual text and original lore: copyright retained by the project author; no separate reuse licence is granted unless explicitly stated.
- The clinical questions and game assets belong to this project.
- No ROMs, ROM hacks, or assets extracted from commercial games are included.

---

<p align="center"><strong>THE WATCH IS SACRED — AND THE WATCH IS MEANT TO BE HANDED ON.</strong></p>
