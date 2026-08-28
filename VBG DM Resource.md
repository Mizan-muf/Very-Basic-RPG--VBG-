# VBG-Z: GAME MASTER SURVIVAL HORROR RESOURCE v2.0
*Guide for Asynchronous Play-by-Post Running Very Basic RPG: Zombie Survival Edition*

---

## 1. SETTING TARGET DIFFICULTIES (TN) & ADJUDICATION

In VBG-Z, players roll `1d20 + Stat + Traits` against a Target Difficulty (TN) set by the GM.

| Target | Risk Tier | Scenario Example |
| :--- | :--- | :--- |
| **TN 10** | **Routine** | Searching a quiet closet, forcing a wooden latch, basic field dressing in safety. |
| **TN 15** | **Risky** | Shooting a sprinting runner, picking a lock while footsteps approach, jumping a gap. |
| **TN 20** | **Desperate** | Shoving a Licker off an ally, blind-firing in darkness, emergency field surgery. |
| **TN 25+** | **Extreme** | Grappling a Tyrant solo, executing an impossible trick shot on a B.O.W. core. |

**Transparency Rule:** Always state the Target TN in your scene description or GM post so players can resolve their actions immediately in text without extra round-trips.

---

## 2. THE NOISE & THREAT CLOCK ENGINE

In Play-by-Post survival horror, noise management creates organic group tension.

### **Area Noise Clock (1 to 6 Ticks)**
Every location has an active **Noise Clock (0/6)**:
- **Melee Combat / Quiet Traversal:** +0 Noise ticks.
- **Unsuppressed Handgun Fire:** +1 Noise tick.
- **Shotgun / Rifle / Explosive Blast:** +2 Noise ticks.
- **Screaming / Metal Door Breaches:** +1 Noise tick.

**Clock Escalation Milestones:**
- **Noise 3:** Ambient cues (scratching in vents, distant groans, shadows crossing doorways).
- **Noise 6:** **BREACH EVENT.** A shambler horde or active B.O.W. Stalker immediately enters the room.

---

## 3. AMMO, FIREARM & EQUIPMENT CATALOG

### **Ammo Storage & Carrying**
- Ammunition is tracked in **Ammo Boxes / Magazines** (1 Ammo Slot = 1 Medium Inventory Slot).
- **Handgun (9mm):** 30 Rounds per slot (3 Magazines).
- **Shotgun (Shells):** 12 Shells per slot.
- **Rifle / Magnum:** 10 Rounds per slot.

### **Firearms & Reload Economy**
- **Handgun (Medium, 1 Slot):** Uses 9mm. Quietest firearm (+1 Noise). Reload 1 mag as part of an action.
- **Shotgun (Large, 2 Slots):** Uses Shells. High damage (+2 Noise). Bypasses 1 Armor box. Reloading shell-by-shell costs an action for 4 shells.
- **Rifle (Large, 2 Slots):** Uses Rifle ammo (+2 Noise). Ignores distance penalties.

---

## 4. WEAPON DURABILITY & PROTECTIVE GEAR

### **Melee Weapon & Tool Durability**
Every melee weapon and tool has **Durability Boxes**:
- **Improvised Weapon (Pipe, Board):** ⬜ (1 Box)
- **Combat Knife / Machete:** ⬜⬜ (2 Boxes)
- **Fireaxe / Crowbar / Steel Bat:** ⬜⬜⬜ (3 Boxes)

*Mechanic:* On a *Success with Cost*, a player can mark 1 Durability Box instead of Strain/Damage. On a *Failure*, the weapon automatically loses 1 Durability Box. When all boxes are marked, the weapon breaks.

### **Protective Armor Types**
- **Leather / Padding (⬜ 1 Box):** Takes 1 slot if not worn; single-use shred on hit.
- **Ballistic / Kevlar Vest (⬜⬜ 2 Boxes):** No encumbrance; soaks bullet/blade hits; repair with Kevlar kit.
- **Heavy Riot Gear (⬜⬜⬜ 3 Boxes):** -2 penalty to Finesse stealth rolls; high bite defense.

---

## 5. MEDICAL RECOVERY & INFECTION ENGINE

### **Medical Consumables Matrix**
- **Green Herb (1/4 Slot):** Restores 2 Strain.
- **Green + Green Herb (1/4 Slot):** Restores 4 Strain.
- **Green + Red Herb (1/4 Slot):** Restores full Strain (4/4).
- **Green + Blue Herb (1/4 Slot):** Restores 2 Strain and lowers Infection Track by 1 step.
- **First Aid Spray (1 Slot):** Instantly restores full Strain (4/4) and clears Bleeding.

### **Virus Infection Track (0–5)**
Gained when bitten, clawed, or exposed to B.O.W. fluids without sealed armor:
- **Stage 0 (Clean):** Healthy.
- **Stage 1 (Exposed):** Low fever. No mechanical penalty yet.
- **Stage 2 (Incubation):** Max Strain reduced by 1 (Cap: 3).
- **Stage 3 (Necrosis):** Max Strain reduced by 2 (Cap: 2). -2 penalty to all Focus rolls.
- **Stage 4 (Mutation):** Max Strain reduced by 3 (Cap: 1). Gain +2 Force, but must pass Focus TN 15 to avoid bloodlust.
- **Stage 5 (Terminal / B.O.W.):** Character succumbs to the virus and becomes an NPC monster.

---

## 6. ASYNCHRONOUS MONSTER BLUEPRINTS

Monsters **do not roll dice**. They declare actions and force player rolls.

```markdown
## SHAMBLER HORDE (Threat Tier: Standard)
**Description:** Rotting corpses driven by instinct to grab and bite.
**Armor:** ⬜⬜ (2 Armor Boxes)
**Actions:**
- Swarm Grab: Forces a Finesse TN 15 roll to avoid being pinned.
- Vicious Bite: Inflicts 1 Strain and increases Infection Track by +1 if target is grappled.
**Strengths:** Immune to non-lethal strikes; decapitation (TN 20) or fire required to bypass Armor.
**Weaknesses:** Slow movement; fire destroys corpses and prevents V-ACT resurrection.
```

```markdown
## LICKER (Threat Tier: Major)
**Description:** Blind quadrupeds with exposed brains and razor tongue spears.
**Armor:** ⬜⬜⬜ (3 Armor Boxes)
**Actions:**
- Tongue Spear: Long-range strike. Forces Finesse TN 20 roll; deals 2 Strain and Bleeding.
- Pounce & Maul: Pins target, dealing 1 Strain per exchange until shoved off by Force TN 15.
**Strengths:** Blind (relies on hearing). Silent movement grants stealth advantage.
**Weaknesses:** Complete stealth (Silent Step / Walking) allows players to pass unmolested.
```

```markdown
## THE PURSUER / STALKER (Threat Tier: Boss)
**Description:** Unstoppable mutated bio-weapon tracking party gunfire noise.
**Armor:** ⬜⬜⬜⬜⬜ (5 Armor Boxes)
**Actions:**
- Structural Wall Breach: Destroys cover and forces Focus/Finesse TN 20 roll to avoid crush trauma.
- Grab & Lift: Forces Force TN 20 roll to break free; inflicts 2 Strain per exchange.
**Strengths:** Cannot be permanently killed in standard scenes; footsteps build ambient horror.
**Weaknesses:** Heavy Explosives (Grenade Launchers / Rocket Launchers) stun it for 2 scenes.
```

---

## 7. PROGRESSION ECONOMY (PP SHOP)

The GM awards **PP (Progression Points)** for completing objectives and consistent posting:

- **[10 PP] Increase Strain Cap:** Increase Max Strain by +1 (Hard Cap: 10).
- **[15 PP] New Specialization Domain:** Unlock a new tactical discipline.
- **[20 PP] New Minor Trait:** Add a new +1 survival trait.
- **[20 PP] Upgrade Trait:** Upgrade a Minor Trait (+1) to a Major Trait (+2).
- **[25 PP] Stat Increase:** +1 to Force, Finesse, or Focus (Hard Cap: +5).

---

## 8. ASYNCHRONOUS SCENE PACING IN DISCORD

1. **Side-Initiative Pacing:** All players post within a 24-hour window. The GM resolves all player actions simultaneously, updates the Noise Clock, and describes enemy reactions.
2. **Conditional Scripting:** Encourage players to write conditional statements in their posts (*"If the zombie moves within 5ft, I fire my shotgun; if it stays back, I reload."*).
3. **Transparent Scene Cards:** Always include current room vitals at the top of GM posts:
   - **Location:** Hallway 2F | **Noise:** [3/6] | **Threats:** 2 Shamblers
