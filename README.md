# EverQuest Legends — Class Combination Guides

A collection of standalone static HTML files covering EverQuest Legends (EQL) class trio tier lists, cross-AI verdicts, and a definitive ranked guide. No build system, no framework — every file is a self-contained single-page app with embedded CSS and JavaScript.

## Files

| File | Purpose |
|------|---------|
| `EQL Ultimate Beta Guide.html` | The definitive 15-trio ranked guide — sticky nav, scroll progress bar, Chart.js radar charts, Font Awesome icons, structured data/SEO meta. **Start here.** |
| `CLAUD EQL.html` | Claude's Top 10 EQ Legends class trios — dark fantasy design, Cinzel/Spectral fonts, no charts |
| `Forge_Verdict_EQL.html` | Cross-AI verdict grading Claude's top 10 trios — Chart.js radar charts, ember particle effects |
| `GROK EQL.html` | Grok's tier list — Tailwind CSS, retro Press Start 2P font, neon green/purple palette |
| `GEMINI EQL.html` | Gemini's tier list — minimal Segoe UI, GitHub dark palette |

## The Guide

`EQL Ultimate Beta Guide.html` ranks all 15 builds using a weighted scoring methodology:

> **Solo 25% + DPS 25% + Survival 20% + Sustain 15% + Raid D4 10% + Control 5%**

S-tier ≥ 87 · A-tier 80–86 · B-tier 74–79. Cross-referenced against EQL community combo-builder data (patch v3.2, June 21 2026).

### Current Top 15 (v1.2)

| Rank | Trio | Nick | Tier |
|------|------|------|------|
| #1 | Shadow Knight / Monk / Shaman | The Dark Triumvirate | S |
| #2 | Cleric / Shaman / Monk | The Self-Sufficient Saint | S |
| #3 | Magician / Cleric / Enchanter | Tank-in-a-Box | S |
| #4 | Shadow Knight / Shaman / Enchanter | The Charm Reaver | S |
| #5 | Cleric / Shaman / Enchanter | The Immortal Controller | A |
| #6 | Warrior / Cleric / Enchanter | The Ironclad Charmer | A |
| #7 | Monk / Shaman / Enchanter | Speed-Farm Assassin | A |
| #8 | Beastlord / Cleric / Enchanter | The Swiss-Army Pet | A |
| #9 | Paladin / Bard / Rogue | The Stun Cascade | A |
| #10 | Paladin / Shaman / Monk | The Stunwall Bruiser | A |
| #11 | Warrior / Cleric / Monk | The Unkillable Wall | A |
| #12 | Shadow Knight / Necromancer / Shaman | The Immortal Reaver | A |
| #13 | Monk / Shaman / Necromancer | The Sustained Rot Brawler | A |
| #14 | Bard / Shaman / Monk | The Lazy-Genius Utility Build | B |
| #15 | Shadow Knight / Shaman / Berserker | The Ramping Monster | B |

## Key Confirmed Mechanics (Closed Beta, Jun 2026)

- **One active pet per player, all types** — charm counts against the cap; summoned pet and charmed mob cannot coexist
- **SK Soul Abrasion AA** = +200% lifetap *proc* damage (base lifetap scaling was nerfed, not the AA)
- **Channeler Stance** = flat 40% incoming damage cut for casters — confirmed mechanic, not a bug
- **Scream of Death** redesigned from single-target to AoE lifetap proc
- **Rogue** rework: Chaotic Stab autogranted at Lv 1, new poison system, Escape ability (aggro drop + invis)
- **Warrior** Heroic Leap = AoE taunt up to 8 targets; Cleave hits 3 additional targets on double/triple attacks
- **Enchanter slow** was the biggest single pre-beta scoring error — now properly credited in all builds

## Changelog

### v1.2 — June 24, 2026 — Ranking Restructure

Rankings rebuilt using the weighted composite formula above, cross-referenced against community combo-builder data.

**Re-ranked:**
- SK/Monk/Shaman promoted to **#1** (was #3) — community's confirmed top all-rounder; AoE pack farming, healer-less D4 viability, double FD
- Cleric/Shaman/Monk moves to **#2** (was #1) — still the gold standard for D4 safety specifically
- Magician/Cleric/Enchanter moves to **#3** (was #2)
- Cleric/Shaman/Enchanter drops from S-tier #4 to **A-tier #5** — DPS floor of 68 penalized under the methodology

**Added (3 new builds):**
- **#4 SK/Shaman/Enchanter "The Charm Reaver"** (S-tier) — highest burst DPS ceiling of any S-tier; dual slow redundancy, Soul Abrasion + Enchanter charm simultaneously
- **#6 Warrior/Cleric/Enchanter "The Ironclad Charmer"** (A-tier) — only tank with zero strippable mana; dual stun counters (Ogre immunity + Enchanter runes); highest D4 raid score in A-tier
- **#9 Paladin/Bard/Rogue "The Stun Cascade"** (A-tier) — best stun output of any build; Rogue rework payoff; Escape + Lay on Hands = two independent survival buttons

**Dropped (3 builds removed):**
- ~~Cleric/Monk/Necromancer~~ (#11) — excellent rez tool but worse solo scoring than incoming A-tier entries
- ~~Magician/Shaman/Enchanter~~ (#12) — outcompeted by both Mag/Cleric/Enc (#3) and SK/Shaman/Enc (#4)
- ~~Warrior/Bard/Cleric~~ (#14) — strong raid D4 but solo and DPS floor rank it below the new entries

---

### v1.1 — June 24, 2026 — Fact-Check & Closed-Beta Sync

**Corrected (prior version was factually wrong):**
- **Charm + Summoned Pet Cannot Coexist** — confirmed via official dev statement (Discord, Mar 2026) and Unofficial FAQ. Charm counts against the one-active-pet cap. Affected: Build #2 (now #3) framing, Build #12 (dropped) pro/con, Limitations cards, hero note, S-tier compare sidebar
- **SK Soul Abrasion AA was not gutted** — AA is confirmed at +200% lifetap proc damage. The nerf hit base lifetap scaling only. Retitled the Limitations card to "Base Only"
- **Magician Earth Pet is Warrior/Ranger** — all pets gain Warrior as base class + a secondary (Mag Earth = Warrior/Ranger, Enchanter animation = Warrior/Paladin, Beastlord Warder = Warrior/Berserker)
- **Druid's new lines are damage-role, not a heal line** — both new beta spell lines confirmed exclusive to damage roles
- **Berserker Stance provides double attack speed, not "no bonus"** — core message (Monk still out-hits Berserker) unchanged

**Confirmed (previously uncertain):**
- Berserker closed-beta buffs: Block added, DPS 88→93, mitigation 35→43, two stances (Striker: 5× skill damage; Berserker: double attack speed), Blood Rune AA no longer crits on normal spells
- Channeler Stance: flat 40% incoming damage cut, documented mechanic, caster durability scores officially raised
- Cleric Promise Renewal survived closed beta unchanged through Jun 21 patch notes
- Enchanter slow was the biggest single pre-beta scoring calibration error — now properly credited

**Updated:**
- Closed beta opened April 24, 2026 (not July 1 — July 1 is pre-order/open beta; July 21 wipe; July 28 full launch)
- Major class confirmations from June 2026 patch notes (Rogue, Ranger, Warrior, Enchanter)
- Magician/Cleric/Enchanter reframed as a **mode-switch build** (pet-tank mode vs. charm-DPS mode, not simultaneous)

---

### v1.0 — June 22, 2026 — Initial Publication

Original 15-trio guide synthesized from Claude Opus 4.8, Gemini 5.1, and Grok 4.3 independent theorycraft, cross-referenced against pre-beta community data.

## Sources

- Official [EverQuest Legends](https://www.everquest.com) site & FAQ
- Daybreak / Game Jawn dev streams & Insights episodes I–IV
- Closed beta patch notes (Apr 24–Jun 21, 2026) via EQL Wiki
- EQL Class Combo Builder Patch Notes (Thomas Van, v2.1–v3.2)
- EQL Unofficial FAQ
- Pixel Nomad: EQL Questions Answered (one-pet-per-player official dev statement)
- Massively OP May 2026 preview · MMORPG.com Beta Preview
- Beta creator coverage: Phlinger Phoo, Higher Thought Gaming, Slayheim, Classic EverQuest, Grimthole, Hammackj, Razman's Retro Realm

---

*EverQuest Legends is developed by Daybreak Game Company and Game Jawn. This is independent fan theorycraft, not official guidance. Pre-Kunark cap Level 50. All 16 classes, 560 possible trios.*
