# CONQUERING CRITICAL CARE — DEMO FIELD MANUAL

<p align="center"><strong>THE FIRST WATCH · THREE-CASTLE EDITION</strong></p>
<p align="center"><em>Windows and macOS setup, field instructions, clinical combat, and the opening legend of Continua</em></p>

```text
┌─────────────────────────────────────────────────────────────────┐
│ PRIORITY DISPATCH: TRIAGE KEEP                                  │
│ Three gates remain within reach. One commander has answered.    │
│ The first watch begins before the next bell.                    │
└─────────────────────────────────────────────────────────────────┘
```

## Before you take command

Conquering Critical Care is a tactical educational RPG about Intensive Care Medicine. The Windows installer and macOS portable ZIP contain the same self-contained opening campaign with three castles, one playable specialist, 50 clinical questions, automatic saving, music, video, and all required game assets.

> **Educational use only.** This game is not a medical device and does not provide patient-specific advice. Always follow current evidence, clinical judgement, local protocols, and appropriate senior or multidisciplinary support.

## Contents of this volume

- [The opening legend](#the-opening-legend)
- [What the demo includes](#what-the-demo-includes)
- [System requirements](#system-requirements)
- [Installing the Windows demo](#installing-the-windows-demo)
- [Opening the macOS portable demo](#opening-the-macos-portable-demo)
- [Starting and closing the game](#starting-and-closing-the-game)
- [Creating your commander](#creating-your-commander)
- [How to play](#how-to-play)
- [Reading the battle screen](#reading-the-battle-screen)
- [Clinical question formats](#clinical-question-formats)
- [Strategy for the first watch](#strategy-for-the-first-watch)
- [Saving and restarting](#saving-and-restarting)
- [Data and privacy](#data-and-privacy)
- [Troubleshooting](#troubleshooting)
- [Removing the demo](#removing-the-demo)

## The opening legend

### The world called Continua

There are worlds built from stone, worlds charted by oceans, and worlds held together by roads.

Continua is held together by **a promise**.

From the oldest Gateway infirmary to the highest tower of the Respiratory Ridge, every Unit entrusts its unfinished work to the next watch. This unbroken vigil is called **The Shift**. Its plans are written in the Handoff Scrolls, guarded by the Shift Oracle, and carried at dawn by teams who may never meet the people who began the night.

For generations, the promise held.

Then came the Pathologies.

They learned that a fortress did not need to fall if its warning could be delayed. They entered through the half-spoken concern, the unnamed owner, the plan copied without its reason. They turned isolated failures into provinces of permanent night.

The first alarm sounded at **Triage Keep**.

Beyond it, the Sepsis Plains had already begun to burn. Bacteremia Bluff sent contradictory signals across the valley. Source Control Stronghold sealed its gates while infection gathered beneath its foundations. The armies of Continua waited for a legendary host.

None came.

Instead, the Shift Oracle chose one specialist and a small field team.

That commander is you.

> **THE SHIFT ORACLE:** “Begin at Triage Keep. Make the patient safer, build a team that can inherit the watch, and leave no warning unspoken.”

## What the demo includes

| Feature | Demo content |
|---|---|
| Castles | Triage Keep, Bacteremia Bluff, Source Control Stronghold |
| Clinical questions | 50 approved questions restricted to the three demo castles |
| Playable class | Balanced Intensivist |
| Preview classes | Ventilator Strategist, Shock Commander, Sepsis Warden — visible but unavailable |
| Difficulty | Foundation, Advanced, Board Exam, Nightmare ICU |
| Saving | Automatic on both Windows and macOS; local to the browser profile on that computer |
| Completion | Secure all three castles to complete the First Watch |

The remaining specialists, castles, bosses, evolutions, and challenge modes belong to the full campaign.

## System requirements

- Windows 10/11, or macOS 11 or later.
- A modern browser such as Microsoft Edge, Google Chrome, Firefox, or Safari.
- A mouse or trackpad. All commands are shown on screen; a keyboard is not required for gameplay.
- Windows: approximately 250 MB after installation; allow at least 650 MB temporarily while running the installer.
- macOS: approximately 258 MiB for the ZIP and 405 MiB after extraction; allow at least 700 MiB while downloading and extracting.

Neither public package requires Node.js, Python, administrator access, or an Internet connection for ordinary play.

## Installing the Windows demo

### Download and install

Download the authorised installer from the [official MediaFire page](https://www.mediafire.com/file/ss3n1gwk8f0goao/Conquering-Critical-Care-Demo-Setup-0.4.0.exe/file):

```text
Conquering-Critical-Care-Demo-Setup-0.4.0.exe
```

1. Save the installer to a normal folder such as **Downloads**.
2. Verify the installer's SHA-256 value against the value published below before opening it.
3. Double-click the installer.
4. Confirm the installation prompt.
5. Open **Conquering Critical Care Demo** from the Desktop or Start menu shortcut.

The demo installs only for the current Windows user at:

```text
%LOCALAPPDATA%\Conquering Critical Care Demo
```

To open this folder at any time, press **Windows key + R**, paste the path above, and press **Enter**. Administrator privileges are not required. The installer also creates **Conquering Critical Care Demo** shortcuts on the Desktop and in the Start menu.

#### Verified demo installer checksum

For the authorised version 0.4.0 installer, the SHA-256 value is:

```text
92BC53BBC1A12B5B52081C3530684CBE0AE08F1B529425C0522D137CADBE053A
```

If the installer has been rebuilt, use the replacement value published in the [Manual Library](../README.md) rather than this archived value.

#### If Windows SmartScreen appears

The pilot installer may be unsigned and Windows can show **Unknown publisher** or **Windows protected your PC**.

Only continue when both conditions are true:

1. the file came directly from the authorised organiser; and
2. its SHA-256 value matches the value published in this manual.

If you trust that copy, choose **More info** and then **Run anyway**. Never bypass SmartScreen for an installer received from an unknown source.

## Opening the macOS portable demo

### Download and verify

Download the authorised ZIP from the [official MediaFire page](https://www.mediafire.com/file/ytitklcgq7vc81i/Conquering-Critical-Care-Demo-Mac-0.4.0.zip):

```text
Conquering-Critical-Care-Demo-Mac-0.4.0.zip
```

The package supports macOS 11 or later and contains native runtimes for both Apple Silicon and 64-bit Intel Macs.

Verified macOS ZIP SHA-256:

```text
B9F0CC8AC9F06D5396D350934B1236C7F05EDBCA079B4888994842FEE122A327
```

The public MediaFire file was downloaded again after upload and matched this checksum exactly.

### Open the demo

1. Download the ZIP to a normal folder such as **Downloads**.
2. Verify its SHA-256 value against the checksum above.
3. Extract the complete ZIP with the built-in macOS Archive Utility. Do not run the demo from inside the ZIP preview.
4. Open the extracted `Conquering-Critical-Care-Demo-Mac-0.4.0` folder.
5. Double-click **`Open Demo.command`**.
6. Keep the Terminal window open while playing.

The launcher selects the correct bundled runtime, starts a server only on `127.0.0.1:48173`, and opens the default browser. Keep `Open Demo.command`, the `app` folder, `launcher`, and `runtime` together inside the extracted demo folder.

### If macOS blocks the first launch

This first macOS package is not signed or notarized by Apple, so Gatekeeper may block an ordinary double-click.

Only continue when the ZIP came from the official link above and its SHA-256 value matches this manual. Then:

1. Control-click `Open Demo.command`.
2. Choose **Open**.
3. Confirm **Open** in the warning.
4. If the option is still unavailable, open **System Settings → Privacy & Security** and choose **Open Anyway** for this launcher.

Do not disable Gatekeeper globally and do not use `sudo`. A real-Mac smoke test remains recommended before broad institutional deployment, particularly on both Apple Silicon and Intel hardware.

## Starting and closing the game

The Windows launcher and macOS `Open Demo.command` both open the game in your default browser at:

```text
http://127.0.0.1:48173
```

This address is local to your own computer. It is not a public website, and the server is not exposed to other computers on the network.

Closing the browser tab does not stop the local launcher.

- **Windows:** right-click the Conquering Critical Care icon beside the clock and choose **Sair** (Exit). Double-clicking the icon reopens the game.
- **macOS:** keep the Terminal window open while playing. Close that window or press **Control+C** to stop the demo.

## Creating your commander

### 1. Participant notice

Read the notice and choose your data preferences. Optional sharing is not required to play. The public version 0.4.0 Windows and macOS packages have no remote analytics service configured: they continue locally and do not transmit gameplay answers.

Select **Enter Demo**.

### 2. Opening sequence

Watch or skip the introduction, then choose **Start** and **Begin Demo**.

### 3. Commander alias

Choose a callsign for this campaign. Do **not** enter:

- your real name;
- a patient's name, initials, dates, record numbers, or clinical details;
- confidential workplace information.

### 4. Institution

Choose the appropriate institution entry. This identifies the declared setting; it is not a request for patient information.

### 5. Specialist

The demo permits one class:

#### Balanced Intensivist — “The Generalist”

A flexible commander with a broad +1 demo bonus. In the full campaign, this bonus begins to scale after five secured castles; within the three-castle demo it remains +1. The Balanced Intensivist is designed to teach the central systems without locking the player into one clinical domain.

The three grey classes are a preview of the full campaign and cannot be selected in this edition.

### 6. Difficulty

| Difficulty | Starting ICU Resolve | Field description |
|---|---:|---|
| Foundation | 120 | Most forgiving; recommended for learning the system |
| Advanced | 100 | Standard challenge |
| Board Exam | 80 | Lower Resolve margin and less room for error |
| Nightmare ICU | 60 | Dangerous errors can decide the battle quickly |

Difficulty changes starting ICU Resolve, not the scientific meaning of an answer.

## How to play

The demo follows a repeating command cycle:

```text
WAR MAP → CASTLE → FORMATION → CLINICAL DECISIONS → FEEDBACK → VICTORY OR RETREAT
```

### Step 1 — Read the objective

The campaign panel names the remaining castles. Begin at **Triage Keep**. After the Gateway is secure, continue into the first contested ground of the Sepsis Plains.

### Step 2 — Select an available castle

Choose a highlighted castle on the map. Locked territories are full-game previews and cannot be entered from the demo.

### Step 3 — Choose your formation

Before ordinary combat, review the enemy force and choose an available formation. Formations modify:

- attack;
- defence;
- special-charge speed;
- special-move power;
- interaction with the enemy troop type.

The panel indicates advantage, disadvantage, and commander synergy. Do not treat the biggest attack number as automatically best; preserving ICU Resolve and team capacity can matter more than a fast opening strike.

### Step 4 — Choose a command

The battle menu contains three principal commands:

- **Clinical Decision** — opens the next case.
- **Special** — uses the equipped class move after enough charge has accumulated.
- **Call AI** — offers a fallible hint when recharged.

You may also **Retreat** from a battle.

> **COMPLIANCE WARNING:** Call AI is intentionally unreliable. Repeated use can reduce its accuracy while its displayed confidence remains persuasive. It represents a tool requiring human verification, not an answer key.

### Step 5 — Resolve the case

Read the entire question, select the requested option or sequence, and choose **Confirm**. Answer positions are shuffled, so memorising “option A” will not work.

### Step 6 — Study the result

After each decision, the game reports:

- correct, incorrect, or harmful outcome;
- damage dealt to the enemy;
- loss of ICU Resolve or troops;
- clinical explanation;
- available references;
- change in special charge and streak.

The explanation is part of the game. Read it even after a correct answer: victory identifies the decision, but the explanation carries the doctrine to the next watch.

### Step 7 — Secure the castle

Reduce Enemy HP to zero before ICU Resolve collapses. Victory grants XP and marks the castle as secured. Complete all three castles to finish the demo.

### Step 8 — Hand off and prepare

After the second newly secured castle, the demo opens a five-question **ISBAR Handoff**. Complete it, then visit the **Field Hospital** to spend XP under:

- **Special Moves** — acquire, equip, or improve an ability;
- **Army & Medics** — restore and strengthen team capacity.

Class evolutions and the **Class Upgrade** service are not available in the demo; they are reserved for the full campaign.

## Reading the battle screen

| Display | Meaning |
|---|---|
| Enemy HP | Reduce this to zero to win the battle |
| ICU Resolve | Overall clinical stability; reaching zero loses control of the case |
| Troops | Available team capacity; losses can persist between battles |
| Special charge | Builds through successful decisions and powers the special move |
| Streak | Consecutive correct answers; an error interrupts it |
| Tactical status | Current advantage, formation effects, warnings, and active modifiers |

Correct answers create offensive momentum. Incorrect answers reduce stability. Clinically dangerous selections can inflict a greater penalty because the game distinguishes an imperfect decision from a harmful one.

## Clinical question formats

### Single best answer

Select the one option that best answers the stem.

### Multiple correct

Select every correct option and no incorrect options. A partly correct set is not a complete answer.

### Sequencing

Select the interventions in the requested clinical order. The order is the answer.

### Avoid harm

Read the wording carefully. The stem may ask for the safest action or ask you to identify the dangerous action that must be avoided. Do not assume that every screen asks for “the treatment to give.”

## Strategy for the first watch

### Triage Keep — learn the rhythm

Use the Gateway to understand selection, confirmation, feedback, Resolve, and special charge. The quickest click is rarely the purpose of the case.

### Bacteremia Bluff — distrust the first signal

The Bluff rewards disciplined interpretation. Separate contamination, true bloodstream infection, severity, and source. When several facts compete for attention, return to the question actually asked.

### Source Control Stronghold — treat the hidden architecture

Antibiotics can fight on the walls while the source remains beneath the fortress. Look for the intervention that changes the underlying problem, its timing, and the circumstances in which medical therapy alone is incomplete.

### General field rules

1. Preserve enough Resolve to survive a difficult late question.
2. Read all options before confirming.
3. Reserve a charged special for a moment when its effect matters.
4. Treat harmful-option warnings as clinical lessons, not merely larger damage numbers.
5. If you lose, review the explanation and return with a different decision process.

## Saving and restarting

On both Windows and macOS, progress is saved automatically in the local storage of the browser profile used to play.

- Return with the same browser, browser profile, and local address.
- Avoid private or incognito mode if you want to keep progress.
- Clearing browser site data removes the save.
- Progress does not automatically move to another computer or browser.
- **Continue Demo** resumes an existing save.
- **New Demo**, or **RESET** followed by **CONFIRM RESET**, replaces current progress after confirmation.

After all three castles are complete, the campaign remains available so you can revisit the included cases.

## Data and privacy

The game remains playable when optional analytics are declined.

The public version 0.4.0 Windows installer and macOS ZIP have no remote analytics endpoint configured and **do not transmit gameplay answers**. Campaign progress and data choices remain in local browser storage.

In a future build that is explicitly configured by the organiser, and only when the participant accepts sharing, pseudonymous events may include:

- character class, difficulty, and declared institution;
- castle start and completion;
- selected answer and correct answer;
- correct/incorrect status, response time, and timeout;
- a random session identifier, app version, language, and time zone;
- rounded approximate location only after a separate choice and browser permission.

The telemetry system does not send the free-text commander alias. Never enter patient-identifiable or confidential information anywhere in the game.

Use **Data Choices** on the title screen to review preferences for future collection. Previously transmitted records must be handled through the organiser identified in the participant notice.

## Troubleshooting

### Nothing happens after opening the Windows shortcut

Exit any copy of the launcher still visible in the notification area and try the shortcut again. If the installation appears incomplete, run the official installer again.

### Nothing happens after opening `Open Demo.command`

Confirm that the complete macOS ZIP was extracted and that `Open Demo.command`, `app`, `launcher`, and `runtime` remain together. If macOS reports **Permission denied**, extract the ZIP again with the built-in Archive Utility. The official ZIP contains the required Unix executable permissions.

### The browser did not open

While the Windows launcher icon or macOS Terminal window is still present, manually open:

```text
http://127.0.0.1:48173
```

If neither launcher is running, start the demo again from the Windows shortcut or `Open Demo.command`.

### Port 48173 is already in use

Exit any other copy of the demo. If another application uses the port, close that application before restarting. The launcher deliberately keeps one stable address so that the browser can find the same save on later sessions.

### Music is silent

Click once inside the game, check the music control in the upper-right corner, and check system volume. Browsers can block audio until the first user interaction. The game remains playable without sound.

### Progress disappeared

Confirm that you are using the same browser and profile, that private browsing was not used, and that site data was not cleared.

### Closing the tab did not stop the game

On Windows, right-click the launcher icon in the notification area and choose **Sair** (Exit). On macOS, close the Terminal window that opened with the demo or press **Control+C** in that window.

### macOS still blocks the launcher

Control-click `Open Demo.command` and choose **Open**. If necessary, use **System Settings → Privacy & Security → Open Anyway**. Do not disable Gatekeeper globally. If organisational policy prevents opening an unsigned package, ask the organiser for an approved deployment method.

### The Windows installer is blocked by organisational policy

Do not attempt to bypass workplace security controls. Ask the organiser for an approved deployment method or use the demo only on an authorised device.

## Removing the demo

### Windows

The version 0.4.0 pilot installer does not create a separate entry in Windows **Installed apps**, so remove it as follows:

1. Right-click the demo icon beside the Windows clock and choose **Sair** (Exit).
2. Press **Windows key + R**.
3. Paste the following path and press **Enter**:

```text
%LOCALAPPDATA%\Conquering Critical Care Demo
```

4. Delete the entire **Conquering Critical Care Demo** folder.
5. Delete any **Conquering Critical Care Demo** shortcuts left on the Desktop or in the Start menu.
6. If you also want to erase local progress and data choices, clear the browser's site data for `http://127.0.0.1:48173` in the same browser profile used to play.

Deleting the installed folder removes the game files. It does not by itself erase browser storage; without optional step 6, the local save and preferences may return after reinstallation.

### macOS

The portable macOS demo is not installed into the system.

1. Close the Terminal window used by the demo, or press **Control+C** in that window.
2. Move the extracted `Conquering-Critical-Care-Demo-Mac-0.4.0` folder to the Trash.
3. Empty the Trash when convenient.
4. If you also want to erase local progress and data choices, clear the browser's site data for `http://127.0.0.1:48173` in the browser profile used to play.

Deleting the extracted folder removes the game files but does not by itself erase browser storage.

## End of the first watch

When Source Control Stronghold is secure, the dawn does not end the war. It reveals the map beyond it: the Cardiac Crest flashing beneath a red storm, the Respiratory Ridge moving like something alive, and distant towers where the Pathologies have learned to wear crowns.

The Shift Oracle closes the first scroll.

> “Three gates are not a kingdom. But three clear handoffs are the beginning of one.”

Your demo is complete.

The watch continues in the full campaign.

---

[Return to the Manual Library](../README.md) · [Open the Full Campaign Command Archive](FULL_GAME_MANUAL.md)
