# VBG-Z: GAME MASTER SURVIVAL HORROR RESOURCE v2.0
*Guide for Asynchronous Play-by-Post Running Very Basic RPG: Zombie Survival Edition*

---

## 1. SETTING TARGET DIFFICULTIES (TN)

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

## 3. ASYNCHRONOUS MONSTER DESIGN

In VBG-Z, **monsters do not roll dice**. They declare threat actions and force player resolution rolls.

### **Threat Tiers & Monster Blueprints**

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
**Description:** Blind, quadrupeds with exposed brains and razor tongue spears.
**Armor:** ⬜⬜⬜ (3 Armor Boxes)
**Actions:**
- Tongue Spear: Long-range strike. Forces a Finesse TN 20 roll; deals 2 Strain and Bleeding.
- Pounce & Maul: Pins a target, dealing 1 Strain per exchange until shoved off by Force TN 15.
**Strengths:** Blind (relies on hearing). Silent movement grants stealth advantage.
**Weaknesses:** Complete stealth (Silent Step / Walking) allows players to pass unmolested.
```

```markdown
## THE PURSUER / STALKER (Threat Tier: Boss)
**Description:** Unstoppable mutated bio-weapon tracking party gunfire noise.
**Armor:** ⬜⬜⬜⬜⬜ (5 Armor Boxes)
**Actions:**
- Structural Wall Breach: Destroys cover and forces a Focus/Finesse TN 20 roll to avoid crush trauma.
- Grab & Lift: Forces a Force TN 20 roll to break free; inflicts 2 Strain per exchange.
**Strengths:** Cannot be permanently killed in standard scenes; footsteps build ambient horror.
**Weaknesses:** Heavy Explosives (Grenade Launchers / Rocket Launchers) or environmental traps stun it for 2 scenes.
```

---

## 4. INVENTORY & ITEM MANAGEMENT GUIDANCE

### **Handling Ammo & Scavenging**
- **Scavenge Rolls:** Focus TN 10 (Routine) to find basic supplies; TN 15 (Risky) for military crates.
- **Failure on Scavenge:** Finding 0 ammo or finding 1 ammo box at the cost of ticking the area Noise Clock.
- **Weapon Jams:** A Natural 1 on a firearm roll jams the gun. The player must use a full action and pass a Focus TN 10 check to clear it.

### **Medical Triage & Treatment**
- **Infection Treatment:** Blue Herbs / Suppressants lower the Infection Track by 1 step. They do not grant immunity.
- **Stabilizing Downed Allies:** Requires an action and Focus TN 15 (or expending a First Aid Spray / Bandage) before the 24-hour post window closes.

---

## 5. ASYNCHRONOUS SCENE PACING IN DISCORD

1. **Side-Initiative Pacing:** All players post within a 24-hour window. The GM resolves all player actions simultaneously, updates the Noise Clock, and describes enemy reactions.
2. **Conditional Scripting:** Encourage players to write conditional statements in their posts:
   - *"If the zombie moves within 5ft, I fire my shotgun (Finesse +0); if it stays back, I reload."*
3. **Transparent Scene Cards:** Always include current room vitals at the top of GM posts:
   - **Location:** Hallway 2F | **Noise:** [3/6] | **Threats:** 2 Shamblers
