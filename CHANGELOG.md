# Update log

## 0.4.1 — 7 September 2026

Updated public downloads and manuals for the demo packages rebuilt on 6 September 2026.

### Demo downloads and installation

- New Windows installer and Mac ZIP, with the same **62-question, three-castle** campaign and **Balanced Intensivist** as the playable starting class.
- Windows now includes an uninstaller, available through **Installed apps** or **UNINSTALL_DEMO.bat**.
- Mac includes **Install Demo.command** and **Uninstall Demo.command**, alongside the portable launcher, for both Apple Silicon and Intel.
- Uninstalling keeps browser progress and preferences.
- Updated download links, filenames, checksums and instructions throughout both manuals.

### Presentation and sound

- Refined Triage Keep, opening video and presentation screens, with presentation adapted to the selected commander.
- Improved combat readability, attack direction and special-move animation timing.
- Refined allied and enemy troop poses and boss-phase transitions, including the six visual states of Shift from Hell in the full campaign.
- Added **REGULAR** and **ALTERNATE** arrangements across the game's music contexts, with rotating map/battle tracks, quieter playback options, pauses and resume support.
- Removed retired media, unused sprites, duplicate resources and superseded distribution packages. The release uses the project's own artwork and soundtrack arrangements.

### Questions and campaign consistency

- Demo question bank increased from **50 to 62** questions.
- Full campaign bank expanded from **684 to 810** source-linked questions, with castle-specific additions, revised explanations and improved question/answer variation.
- Checked commander, formation and special-move consistency across the full campaign; refined castle balance.
- The full campaign remains a preview in this repository, not a public download. Its additional classes, castles and bosses are not unlocked by the demo.
- Source links and automated validation do **not** constitute clinical approval: human review of recently added or revised items remains pending.

### Validation and remaining limits

- Game builds, gameplay/data tests, animation tests and checks for retired release assets passed.
- The final Windows EXE was installed in an isolated test folder, its files compared with the release, and its uninstaller tested. Tests also covered unsafe-path refusal, same-folder reinstallation and preservation of added files.
- Both ZIP archives matched the demo build. Mac runtime hashes and executable permissions were checked; the included server was tested using Node on Windows. **This release has not yet been run on a real Mac.**
- Packages remain unsigned; the Mac package is not notarized. See the [Demo Field Manual](manuals/DEMO_MANUAL.md) for first-launch instructions.
- Published SHA-256 values identify the locally validated packages. The replacement MediaFire uploads have not been independently downloaded again for hash verification.

[Download the demo](README.md#official-demo-downloads) · [Demo Field Manual](manuals/DEMO_MANUAL.md) · [Full Campaign Command Archive](manuals/FULL_GAME_MANUAL.md)
