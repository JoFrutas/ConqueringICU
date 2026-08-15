# CONQUERING CRITICAL CARE

<p align="center"><strong>FULL CAMPAIGN COMMAND ARCHIVE</strong></p>
<p align="center"><em>Preview Manual · World Almanac · Specialist Field Guide</em></p>

```text
╔══════════════════════════════════════════════════════════════════╗
║                     CONTINUA HIGH COMMAND                       ║
║ ARCHIVE STATUS: PARTIALLY DECLASSIFIED                          ║
║ Fifteen realms are known. The final handoff remains sealed.     ║
╚══════════════════════════════════════════════════════════════════╝
```

## A message before the seal is broken

This is a **spoiler-light preview manual** for the complete Conquering Critical Care campaign. It explains the world, player systems, classes, clinical combat, and the scale of the campaign while leaving final outcomes, late story turns, and most final mechanics classified.

The purpose is the same as the great console manuals of an earlier age: to make the journey feel larger before the first battle begins.

> **Educational use only.** Conquering Critical Care is not a medical device and does not provide patient-specific advice. Always follow current evidence, clinical judgement, local protocols, and appropriate senior or multidisciplinary support.

## Archive index

- [Release and platform status](#release-and-platform-status)
- [Prologue — The Unbroken Watch](#prologue--the-unbroken-watch)
- [Your campaign](#your-campaign)
- [Creating a commander](#creating-a-commander)
- [Specialist dossiers](#specialist-dossiers)
- [The atlas of Continua](#the-atlas-of-continua)
- [Clinical combat](#clinical-combat)
- [Formations](#formations)
- [Special moves and Call AI](#special-moves-and-call-ai)
- [The living campaign map](#the-living-campaign-map)
- [The Handoff and Field Hospital](#the-handoff-and-field-hospital)
- [Pathology dossiers](#pathology-dossiers)
- [Advanced and post-campaign trials](#advanced-and-post-campaign-trials)
- [Command doctrine](#command-doctrine)
- [Saving and troubleshooting](#saving-and-troubleshooting)
- [Glossary of the watch](#glossary-of-the-watch)
- [The sealed final page](#the-sealed-final-page)

## Release and platform status

The three-castle demo is publicly available for both **Windows** and **macOS**. The playable packages are hosted separately on MediaFire; this GitHub repository remains the home of the player manuals.

| Edition | Windows | macOS |
|---|---|---|
| Three-castle demo 0.4.0 | [Public per-user installer](https://www.mediafire.com/file/ss3n1gwk8f0goao/Conquering-Critical-Care-Demo-Setup-0.4.0.exe/file) | [Public portable ZIP for Apple Silicon and Intel](https://www.mediafire.com/file/ytitklcgq7vc81i/Conquering-Critical-Care-Demo-Mac-0.4.0.zip) |
| Full campaign | Not yet offered as a public download | Not yet offered as a public download |

The [Demo Field Manual](DEMO_MANUAL.md) contains the current system requirements, checksums, opening instructions, security guidance, and removal steps for both platforms.

When a full-campaign package is released for either platform, its official link, filename, system requirements, checksum, and platform-specific setup steps will be added here. Do not assume that either demo package unlocks the full campaign, and do not use GitHub's automatic **Source code (zip)** as though it were a playable game package.

The demo and full campaign use separate edition rules and separate saves. Opening the demo is an invitation to the First Watch, not an incomplete installation of the full game.

### Planned player setup workflow

When the full campaign receives an official public release:

1. follow only the download link published in this Manual Library;
2. choose the package made for your operating system, not GitHub's automatic source archive;
3. compare that package's SHA-256 value with the checksum published beside it;
4. close any running demo or older full-game launcher;
5. follow the release-specific Windows or macOS setup instructions;
6. start the game with the launcher documented for that package;
7. keep the demo only if you wish to retain it as a separate edition.

Final filenames, disk-space requirements, update behaviour, signing or notarization status, and supported operating-system versions are intentionally not invented in this preview. They will be documented separately after each full-game package has been built and validated.

## Prologue — The Unbroken Watch

### I. Before the night

Continua was not founded by conquest.

Its first cities grew around Units: places where the injured were received, the breathless were supported, and the unstable were watched when ordinary time no longer applied. No ruler could remain awake forever, so the people built a different kind of defence. Every plan would be spoken. Every warning would name its owner. Every watch would leave enough truth for the next.

They called this covenant **The Shift**.

The Shift Oracle kept no book of prophecy. The Oracle guarded the Handoff Scrolls: an immense living archive of unfinished plans, reasons, thresholds, and promises. Quartermaster Lira kept the Night Roster, ensuring that knowledge had hands to carry it.

For centuries, dawn followed dawn.

### II. How the Pathologies entered

The enemy did not cross Continua's walls in formation.

It came as disconnected detail.

A fever dismissed because the pressure was still acceptable. A rising oxygen requirement recorded without its direction. A source suspected by one Unit and invisible to the next. An artificial certainty repeated until nobody remembered the evidence beneath it.

From these fractures arose the great Pathologies. They took animal, royal, and spectral forms because fear gives shape to what teams struggle to name. The Septic Hydra grew a new head for every delayed intervention. The ARDS Leviathan made an ocean of the smallest alveolus. The Herniation Wraith moved faster whenever vigilance looked away.

The provinces fell into **the Broken Night**.

### III. The commander's appointment

The surviving Units asked the Oracle for an army large enough to retake the world.

The Oracle refused.

An army without judgement would repeat the failure at a larger scale. Instead, the Oracle chose one specialist to lead a small, accountable team across the map. Every member would matter. Every casualty would be felt. Every victory would create an obligation to the people left behind.

The commander would not win by knowing everything.

The commander would win by making uncertainty explicit, choosing under pressure, learning from failure, and handing the watch forward.

You have been appointed.

## Your campaign

The complete campaign contains:

- **15 clinical realms**;
- **45 castles**;
- **22 boss encounters**;
- **8 playable classes** across starting disciplines and advanced evolutions;
- **16 equipable special moves, plus the separate Call AI command**;
- **684 approved clinical questions**;
- tactical formations and enemy troop interactions;
- persistent ICU Resolve, troop reserve, XP, upgrades, and review history;
- a campaign map with multiple fronts, warnings, and counterattacks;
- story councils with consequential command choices;
- handoffs, spaced review, Field Hospital development, daily challenges, Toxicology Codex, Research Academy, and real-time ultimate trials.

The central loop is easy to read and difficult to master:

```text
READ THE MAP
    ↓
CHOOSE A FRONT
    ↓
PREPARE THE TEAM
    ↓
MAKE CLINICAL DECISIONS
    ↓
STUDY THE CONSEQUENCES
    ↓
REBUILD, HAND OFF, AND CHOOSE AGAIN
```

You do not need to clear one realm completely before visiting another. Once the Gateway opens, several fronts compete for attention. That freedom creates the campaign's strategic burden: every advance extends the roster, and every secured Unit becomes a promise somebody must keep.

## Creating a commander

### Commander alias

Choose a callsign, not a real identity. Never enter patient data, confidential clinical details, or personal information into the game.

### Starting discipline

Four specialists answer the first summons. Each changes the campaign's opening formation, clinical strengths, and signature move.

### Difficulty

| Difficulty | Starting ICU Resolve | Command profile |
|---|---:|---|
| Foundation | 120 | A forgiving field school for learning the systems |
| Advanced | 100 | The standard campaign |
| Board Exam | 80 | A narrow Resolve margin and shorter timed boss turns |
| Nightmare ICU | 60 | A dangerous decision can overturn the entire battle |

Difficulty alters game pressure. It does not make a clinically wrong answer correct or change the educational meaning of the case.

## Specialist dossiers

### Starting disciplines

#### Balanced Intensivist — The Generalist

**Signature move:** Code Team Response  
**Opening formation:** Assault Wedge  
**Doctrine:** Adapt to the Unit in front of you.

The Balanced Intensivist begins with a broad bonus and grows through accumulated conquest. This commander has no single kingdom to call home and no realm where learning can be postponed.

> “Master of none” is what distant courts call the generalist. On the night watch, it means the person who remains when several systems fail at once.

#### Ventilator Strategist — The Lung Whisperer

**Signature move:** Prone Protocol  
**Opening formation:** Precision Strike  
**Doctrine:** Read pressure, volume, recruitment, and time as one language.

Strongest on the Respiratory Ridge, the Strategist turns ventilatory precision into offensive momentum. The class rewards preparation and disciplined use of a powerful signature move.

#### Shock Commander — The Pressure Holder

**Signature move:** Vasopressor Surge  
**Opening formation:** Balanced Line  
**Doctrine:** Restore flow without losing sight of cause.

At home on the Cardiac Crest, the Shock Commander brings decisive haemodynamic force. Raw pressure is not enough; the class thrives when a fast intervention remains tied to physiology.

#### Sepsis Warden — The Hour-One Hunter

**Signature move:** Hour-1 Bundle  
**Opening formation:** Phalanx  
**Doctrine:** Find the source, control the clock, protect the host.

The Warden is strongest across the Sepsis Plains and Infection Islands. Its defensive formation favours disciplined survival while the source is identified and the decisive window preserved.

### Advanced evolutions

The Field Hospital can open four permanent class evolutions. Each preserves part of the commander's experience while changing domain strengths and tactical identity.

| Starting class | Evolution | Requirement | Signature doctrine |
|---|---|---|---|
| Balanced Intensivist | Researcher | Reach at least 300 XP | Evidence Burst — turn uncertainty into structured inquiry |
| Ventilator Strategist | Neurointensivist | Secure a Neuro Nexus castle | ICP Management — defend the injured brain under pressure |
| Shock Commander | Hepatologist | Secure a Hepatic Highlands castle | Liver Resuscitation — balance haemostasis, perfusion, and consequence |
| Sepsis Warden | Nephrologist | Secure a Renal Ravines castle | RRT Protocol — control accumulation, timing, and extracorporeal support |

Evolution is permanent for that save. Read the dossier before confirming. A new title is not a cosmetic reward; it changes how the commander meets the map.

## The atlas of Continua

### Gateway

**Triage Keep** is the first surviving gate and the campaign's field school. Here, the Oracle teaches the rhythm of decision, feedback, and handoff.

### Sepsis Plains

**Bacteremia Bluff · Source Control Stronghold · Antibiotic Arsenal**

A country of false horizons. Signals echo, sources hide below fortified ground, and every delay gives the enemy another road.

### Cardiac Crest

**Arrhythmia Atoll · Heart Failure Heights · ACS Advance**

Red storms circle the towers. Timing, perfusion, rhythm, and mechanical consequence are written in lightning across the ridge.

### Respiratory Ridge

**Hypoxemia Heights · Ventilator Valley · ARDS Abyss**

The air itself has become terrain. Pressure can protect or injure; oxygen can rescue while concealing the depth of the flood.

### Infection Islands

**Pneumonia Post · Fungal Fortress · Viral Vault**

Three islands, three kinds of uncertainty. The invader's identity matters, but so do host, timing, sampling, and the cost of treating shadows.

### Neuro Nexus

**Stroke Stronghold · TBI Tower · Seizure Spire**

Minutes become geography. A small delay can close an entire road, and the quietest change in examination may be the loudest alarm.

### Hematology Heights

**TTP Tower · DIC Domain · Transfusion Territory**

Here the army's own instruments of defence can turn against it. Clotting, bleeding, destruction, and replacement share the same narrow passes.

### Renal Ravines

**AKI Approach · Fluid Balance Fort · RRT Realm**

Everything entering the valley must eventually leave it. Accumulation becomes an enemy measured in chemistry, water, time, and tolerance.

### Hepatic Highlands

**Coagulopathy Crag · ALF Alcazar · HE Estate**

The Highlands trade in paradox: apparent bleeding risk beside thrombosis, damaged clearance beside toxic accumulation, a failing organ that alters the meaning of every other system.

### GI Basin

**Upper GI Gauntlet · Pancreatitis Pass · Intestinal Ischemia Isle**

The Basin can hide catastrophe behind pain, pressure, or silence. Its roads demand resuscitation without forgetting diagnosis and diagnosis without delaying rescue.

### Endocrine Empire

**DKA Domain · Thyroid Thunder · Adrenal Abyss**

Small messengers command enormous machinery. When signalling fails, temperature, circulation, electrolytes, and consciousness can all change allegiance.

### Toxicology Trenches

**Overdose Outpost · Antidote Arsenal · ECMO-CPR Escarpment**

Nothing here is only what it appears to be. The Trenches reward toxidrome recognition, supportive care, antidote discipline, and knowing when extracorporeal rescue is still possible.

### Autoimmune Archipelago

**Vasculitis Vault · ICI Island · Myositis March**

Defence has forgotten its target. The campaign becomes a negotiation between inflammation, infection, organ injury, and the consequences of suppressing the wrong battle.

### The Final Shift

**MODS Bastion · The Shift from Hell**

The roads converge. No single-organ doctrine is enough. Every resource, handoff, and habit developed across the campaign is called to the same watch.

### Research Academy

**Background Bastion · PICO Compass · Study Design Crossroads · Population Outpost · Statistics Sanctum · Ethics Checkpoint**

Beyond the war map stands a province where evidence itself is tested. The Academy asks not only “What is the answer?” but “How was the question built, whom does the answer represent, and what can the design truly support?”

## Clinical combat

### The battle resources

| Resource | Meaning |
|---|---|
| Enemy HP | The Pathology's remaining hold on the Unit; reduce it to zero |
| ICU Resolve | Overall stability; reaching zero loses control of the case |
| Troop reserve | The team's available capacity; casualties can persist across battles |
| Special charge | Energy earned through good decisions and used for the equipped special move |
| Streak | Consecutive correct decisions and the momentum they create |

### The command menu

- **Clinical Decision** opens the next case.
- **Special** uses or reviews the equipped move.
- **Call AI** requests a fallible consultation when charged.
- **Retreat** leaves the engagement.

### Question formats

- **Single best answer:** choose the best option.
- **Multiple correct:** choose all correct options and no incorrect ones.
- **Sequencing:** place interventions in the required order.
- **Avoid harm:** identify the safest action or the harmful action to avoid, exactly as the stem asks.

Answer positions are shuffled. The game remembers meaning, not letters.

### Consequence and feedback

Correct decisions damage the enemy and charge the special move. Incorrect decisions reduce Resolve. Options marked as clinically dangerous can cause a larger penalty and additional troop loss.

After each choice, read the explanation and available references. A result screen is not merely a score receipt; it is the page of doctrine earned in battle.

## Formations

| Formation | Tactical character |
|---|---|
| Balanced Line | Stable statistics without an extreme weakness |
| Assault Wedge | High attack and fast charge at the cost of defence |
| Phalanx | Strong defence with slower attack and charge |
| Precision Strike | Attack and charge above average without a defensive bonus |
| Consultant Circle | Exceptional special power in a fragile formation |

The commander's starting formation and the Consultant Circle can activate class synergy, improving attack, defence, charge, and special power. Troop types also interact with enemy types, so the strongest formation on paper may be the wrong formation for the castle ahead.

## Special moves and Call AI

### Special moves

Sixteen equipable moves form a branching command arsenal. Call AI is a separate transversal command. Special-move effects include:

- double attacks;
- blocking the next counterattack;
- restoring ICU Resolve;
- revealing an answer;
- accelerating special charge;
- creating a multi-turn shield;
- exposing the enemy to additional damage.

A class-matched move receives a synergy bonus. Exploiting a boss weakness can add a second multiplier. The dramatic animation is only the surface; timing and match-up create the real power.

### Call AI

Call AI is deliberately fallible. Early advice may be useful, but repeated use in the same battle can reduce accuracy while displayed confidence remains persuasive.

This is a mechanical lesson about clinical AI:

1. a suggestion is not validation;
2. confidence is not calibration;
3. repeated dependence changes risk;
4. responsibility remains with the human decision-maker.

Excessive or unsafe use can attract **The Compliance Archon**, a special encounter born not from technology itself but from undocumented trust.

> **ARCHIVE FRAGMENT:** “The machine did not open the gate. The commander stopped checking whether the gate was still there.”

## The living campaign map

### Multiple fronts

After the Gateway, the map opens. You may move between clinical realms and build a route that suits the commander's strengths or desired evolution.

### Threat and neglect

Secured Units still require continuity. Ignore an exposed front and pressure rises from watch to warning. Ignore the warning again and a counterattack can suspend new offensives until answered.

A failed defence does not erase conquered ground, unlocked knowledge, or campaign progress. It creates a costly handoff under pressure and asks what the command structure will repair.

### War councils

At major milestones, the Oracle and Quartermaster Lira convene the council. You may choose to:

- reinforce an exposed Unit;
- restore the field roster;
- convert momentum and after-action review into XP.

These are not morality buttons. Each protects something valuable and leaves something else exposed.

## The Handoff and Field Hospital

### The Handoff

After two new victories, the campaign presents a five-question ISBAR handoff. Recent cases, conquered material, and missed topics return in a structured transfer of responsibility.

Correct handoff decisions grant XP. More importantly, the system makes continuity playable: a castle is not truly secure until its lesson can survive another watch.

### Spaced review

Missed questions enter a review queue. Later handoffs and modes can bring them back. Failure therefore changes the future learning path instead of disappearing behind a score screen.

### Field Hospital

The Field Hospital contains three principal services:

- **Special Moves:** buy, equip, and improve abilities.
- **Army & Medics:** replace casualties and strengthen team capacity.
- **Class Upgrade:** review and confirm available evolutions.

XP left unspent cannot treat an empty roster. Before a difficult boss, inspect troop reserve, equipped move, ability level, and formation rather than trusting the victory that brought you there.

## Pathology dossiers

Only selected files have been declassified.

### The Septic Hydra

Every delayed priority allows another head to rise. The Hydra is not beaten by one correct buzzword but by coordinated timing, source, perfusion, antimicrobial judgement, and reassessment.

### The Cardiogenic Tyrant

A ruler who mistakes pressure for flow. The Tyrant punishes interventions that improve a number while worsening the system beneath it.

### The ARDS Leviathan

An ocean compressed into the lung. The Leviathan makes every breath a negotiation between recruitment, overdistension, oxygenation, haemodynamics, and time.

### The Herniation Wraith

The Wraith travels through lost minutes. It rewards vigilance, rapid recognition, protection of physiology, and a clear bridge to definitive control.

### The Nephron Lich

Collector of all that the body cannot clear. The Lich grows stronger when accumulation is measured without asking whether the patient can tolerate waiting.

### The Hepatic Basilisk

Its gaze turns simple rules into dangerous stone. Coagulation, metabolism, cerebral risk, infection, and transplant timing must be read together.

### The Autoimmune Seraph

Beautiful, radiant, and misdirected. The Seraph tests whether the commander can suppress destructive immunity without becoming blind to infection and mimicry.

### The Shift from Hell

```text
[CLASSIFIED]
Threat model: multi-system
Recommended preparation: everything you were told you could postpone
```

The final great Pathology is not a single chapter. It is the campaign asking whether your habits still hold when every chapter is open at once.

Six Research Academy trials, the Publication Guardian, cross-territory threats, and several ultimate encounter states remain sealed in this preview.

## Advanced and post-campaign trials

### Daily Challenge

A deterministic rotating challenge with personal streak tracking. It rewards return and recall without replacing the main campaign.

### Toxicology Codex

A rapid identification trial built around toxins, syndromes, and antidotal thinking. Personal best performance is saved locally.

### Research Academy

The Academy transforms research literacy into an adventure path: background, PICO, design, population, statistics, and ethics. Its mentor encounters do not simply ask for damage; they ask the player to build and defend a research plan.

### Test Your Might

Real-time ultimate encounters awaken after specific achievements. These battles replace the comfortable pace of a question list with changing clinical variables, intervention windows, complications, and rescue states.

The ordinary campaign teaches what to choose. Test Your Might asks whether you can recognise **when** the clinical state has changed enough to demand a different choice.

## Command doctrine

### Before deployment

1. Read the current campaign objective and front warnings.
2. Check troop reserve.
3. Review enemy type and formation interaction.
4. Confirm the equipped special move.
5. Decide whether this battle advances a class-evolution goal.

### During the case

1. Identify exactly what the stem asks.
2. Separate immediate stabilisation from definitive treatment.
3. Look for dangerous distractors, not only attractive answers.
4. Preserve resources when the battle has many cases remaining.
5. Use Call AI as a hypothesis requiring verification.

### After the result

1. Read the explanation.
2. Note why the wrong option was tempting.
3. Review references when the topic is unfamiliar or high-risk.
4. Carry the lesson into the next handoff.

### On the war map

1. A warning is cheaper than a counterattack.
2. XP is a resource only after it is spent wisely.
3. A specialist's strongest realm is not always the realm that most needs attention.
4. A defeat that produces a clear prevention plan can strengthen the campaign.

## Saving and troubleshooting

### Automatic save

The game saves campaign state in local browser storage, including class, difficulty, conquered castles, XP, bosses, troops, abilities, formation access, story choices, handoffs, review queue, daily challenge, and Codex record.

- Use the same browser, browser profile, and game address.
- Avoid private mode if you want persistence.
- Clearing site data removes the save.
- Saves do not automatically transfer between browsers or computers.
- **RESET**, followed by **CONFIRM RESET**, removes the current campaign after confirmation.

### Audio

Browsers may wait for a user interaction before starting music. Click inside the game, inspect the music control, and check system volume. The game remains playable if Web Audio is unavailable.

### Browser or game error

Use **Reload Game** if the error boundary appears. If the problem remains, preserve the displayed message, close the launcher cleanly, and restart.

### Missing progress

Confirm the same browser, profile, edition, host, and port. Demo and full-game saves are intentionally separate.

## Glossary of the watch

| Term | Meaning in Continua |
|---|---|
| The Shift | The unbroken clinical vigil passed between teams |
| Unit | A secured or contested clinical territory |
| Castle | A focused area of clinical decision-making |
| Pathology | A boss manifestation of a dangerous clinical process |
| Handoff Scrolls | The accumulated plans, warnings, and reasons carried between watches |
| ICU Resolve | The team's ability to maintain control of the case |
| Troops | Persistent team capacity rather than anonymous expendable lives |
| XP | Command experience spent on preparation and development |
| The Broken Night | The age of disconnected warnings in which the campaign begins |
| The First Watch | The three-castle demo campaign |
| The Last Handoff | The sealed convergence of the full campaign |

## The sealed final page

The oldest Handoff Scroll contains a line written in two inks.

The first belongs to the founder of Continua:

> “No watch can finish every task.”

The second was added centuries later, on the night the Pathologies crossed the map:

> “Then let every watch finish the truth.”

At the beginning of the campaign, you are asked to save three walls and the patients behind them.

By the end, the question has changed.

Can a world remain safe after its hero leaves the room?

The archive closes here.

The remaining pages must be earned in play.

---

[Return to the Manual Library](../README.md) · [Begin with the Demo Field Manual](DEMO_MANUAL.md)
