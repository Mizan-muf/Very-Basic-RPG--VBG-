# VBG: Game Master Resource v1.0

---

## 1. Setting Target Difficulties

The Target Difficulty (or Target Number) is the number the player's total roll (sum of all dice + flat Stat bonus) must meet or exceed.

**Transparency Rule:** Tell players the target difficulty before they roll, or give a narrative hint. Async play demands players know what they are attempting, not be surprised after the fact.

**Result Tiers (what happens after the roll):**

| Total vs. Target | Outcome |
|---|---|
| Miss by 5 or more | Failure — you do not achieve your goal, or do so with a disastrous consequence |
| Miss by 1–4 | Success with Cost — you succeed, but must pay (mark Strain, gain a Condition, lose gear, alert an enemy) |
| Beat by 0–5 | Clean Success — you achieve your goal without penalty |
| Beat by 6 or more | Critical — perfect success; regain 1 Strain OR gain a distinct narrative advantage |

---

## 2. Scene Framework

VBG uses a **scene-based structure**. Scenes are the unit of play, not rounds or turns.

### Scene Types

**Battle Scene**
- A physical confrontation or dangerous conflict.
- Has a defined end condition: enemy defeated, objective taken, players escape, or a side surrenders.
- Players post their action; GM responds with enemy reaction and the new state of the scene.
- Continues until the end condition is met.

**Social Scene**
- A clear social confrontation.
- Mostly narrative. Rolls happen only at key decision points or moments of genuine risk.
- The GM plays the opposing position. A DR can be set for persuasion, deception, or pressure.

**Rest Scene**
- Safe Haven downtime in a secure shelter or safe room.
- Strain and Armor do not automatically restore for free; recovery requires spending medical items (herbs, sprays, sutures) or rest under medical supervision.
- Can include narrative character interactions and maintenance.

**Exploration Scene**
- Characters move through the world, interact, and discover.
- Driven by narrative like a novel. Roll only when there is a real risk and a meaningful cost for failure.
- The GM describes the world; players write how their characters respond.

### Scene Economy Rules

- **Resource Attrition:** Strain and Armor persist across scenes until repaired or treated with medical supplies.
- **Conditions** persist across scenes until treated, stabilized, or surgically resolved.

---

## 4. Action Order in Battle Scenes

Action order is determined by **Finesse**.

**Default Order:**
1. Highest Finesse acts first.
2. Ties are broken by whoever posts first.
3. Enemies act after all players in a given exchange, or at GM discretion in between players if the narrative calls for it.

**Optional — Initiative Roll:**
Use when you want variance or to simulate a surprise/ambush opening:
- Each character rolls 1d10 and adds their Finesse as a flat bonus.
- Order is fixed for the entire scene.
- GM rolls once for each major enemy group (not individual mooks).

*Recommendation: Use Finesse order by default. Use the Initiative Roll only when a dramatic surprise opening matters.*

---

## 5. GM Moves (On Player Failure)

When a player rolls a Failure (misses DR by 5 or more), the GM must act. Choose one — do not repeat the same move twice in a row.

**Inflict Harm** — The enemy or environment strikes. The player must Soak (spend Strain or mark Armor) or accept a Condition.

**Introduce a Threat** — A new problem enters the scene: reinforcements arrive, the bridge cracks, an ally is targeted, a fire starts.

**Block Progress** — The player's goal is denied. The door won't open. The guard doesn't believe them. The target escapes.

**Complicate the Scene** — Something shifts that makes everything harder: lights go out, a third faction arrives, the weather turns violent, a key item is destroyed.

**Cost Time or Resources** — The failure burns a window of opportunity. Supplies are wasted. An ally must spend Strain to compensate.

**Turn the Environment** — Use the setting as a weapon: avalanche, flooding room, collapsing floor, crowd turning hostile.

---

## 6. Condition System

Conditions are **negative temporary Traits** gained from wounds, failed rolls, or narrative costs. They affect characters mechanically and must be resolved to be removed.

### Condition Categories

**Ongoing Strain Loss**
- *Poisoned / Bleeding / Burning* — Lose 1 Strain at the start of each new exchange until treated.
- Treatment: field medicine, clean bandages, or medical supplies.

**Maximum Strain Reduction**
- *Limb Damaged* — Maximum Strain reduced by 2 until stabilized and treated.
- *Limb Severed* — Maximum Strain permanently reduced by 2. Certain actions become impossible (climbing with no arm, sprinting with no leg). Requires emergency tourniquet and permanent adaptation/prosthetics.

**Action Restrictions**
- *Pinned / Restrained* — Cannot take movement or offensive actions until freed or an ally assists.
- *Blinded / Impaired Senses* — Target difficulties increase for any action requiring sight.
- *Stunned* — Skip next available action. Clears on their following turn.

**Narrative Penalties**
- *Concussed / Traumatized / Shaken* — Acts as a −1d10 penalty (one fewer die in the pool) to relevant rolls based on trauma.

### Removing Conditions

| Method | Conditions Removed |
|---|---|
| First Aid / Medical Supplies | Bleeding, Poisoned, Burning, Pinned |
| Rest & Medical Stabilization | Limb Damaged, Concussed, Shaken |
| Surgical Care / Long-Term Treatment | Severe physical trauma, chronic injuries |

---

## 7. Taken Out, Last Stand & Death

### When a Character at 0 Strain Takes Another Hit

They do not die immediately. The player must **immediately choose** one of two options:

---

**Option A — Go Unconscious**

- The character collapses. They cannot act or post actions.
- **Recovery by Allies:** An ally may spend 2 of their own Strain and make a DR 15 roll (during a Battle Scene) to revive them with 1 Strain.
- **Recovery by Rest:** Outside of active combat, unconscious characters revive automatically with 1 Strain after a scene ends.
- **Hostile Execution:** Any enemy with physical access to the unconscious character may choose to end them — no roll, no defense. This is a GM decision based on the enemy's nature and intent.

---

**Option B — Enter Last Stand**

- The character refuses to fall. They act on their next turn with everything they have left.
- They make **one final action roll** (any action of the player's choice).

| Roll Result | Outcome |
|---|---|
| Clean Success or Critical | They pull through. The action resolves dramatically. After it concludes, they immediately fall Unconscious (see above). |
| Failure or Success with Cost | The character **dies**. Permanently. The player narrates their final moment. |

**Last Stand Notes:**
- The player narrates what their character attempts — make it count.
- The GM should not inflate the DR unreasonably for a Last Stand. Match the drama, not the difficulty.
- A Last Stand that ends in death cannot be negated by enemies — the action itself was the final moment. The character's story closes there.

---

## 8. Tactical Gear, Scarcity & Vulnerabilities

Gear is not cosmetic in survival horror. Weapons, ammunition, light sources, and tools drive tactical decisions, risk assessment, and resource management.

### Firearm & Tool Principles
- **Noise & Heat:** Unsuppressed gunshots echo and raise local area threat, drawing nearby infected or alerting stalkers. Melee tools are quiet but force close-quarters exposure.
- **Ammunition Scarcity:** Ammo must be tracked by loose rounds or magazines. Running empty forces desperate retreats or tool swaps.
- **Tool Durability:** Improvised bludgeons and makeshift blades degrade or break on severe failed rolls.

### Biological Vulnerabilities & Target Profiles
Certain B.O.W.s and mutated strains have distinct biological weak points or elemental vulnerabilities:

| Creature Type | Vulnerability / Tactical Requirement |
|---|---|
| Basic Infected / Shambler | Headshot / Decapitation (stops V-ACT rebirth) or Incineration |
| Crimson Head / Sprinter | High-caliber stopping power, fire/acid, or heavy limb destruction |
| Licker | Hearing-reliant (stealth traversal), sensitive exposed brain tissue |
| Armored / Carapace B.O.W. | Armor-piercing munitions (Magnum/Rifles) or explosive shockwaves |
| Regenerative Tyrant / Stalker | High-voltage environmental traps, heavy ordnance, or temporary stunning |

**Signaling Weak Points:** The GM describes distinct visual cues ("a pulsing yellow eye on its shoulder joint" / "thick cranial carapace protecting its skull"). Discovering weak points under fire requires a FOCUS check or tactical experimentation.

### Protective Gear
Armor represents physical worn protection (tactical vests, riot gear, reinforced leather) providing discrete Armor boxes that absorb incoming trauma before breaking.

---

## 9. Multi-Domain Specializations

When a character activates **more than one specialization simultaneously** in a single action:

### Scale Cap Per Domain
- Combining disciplines caps individual scale at **Standard (1 Strain each)**.
- Total Strain spent is capped at **2 Strain maximum** (Major tactical impact).

### Rules

- The character makes **one roll** for the combined action.
- The result is **one unified outcome** — the GM narrates it as a single event, not separate actions.
- **On Failure:** A multi-specialization failure carries severe tactical risk — weapon jams, dropped gear, or exposing oneself to an immediate grab/attack.

---

## 10. Assist (No Direct Mechanics — GM Guidance)

VBG has no mechanical assist system, but the following approaches are recommended:

**Ability Setup:** A character uses their specialization to create conditions that directly benefit an ally's roll. The GM may lower the target difficulty for the follow-up action.

**Sacrificial Positioning:** A character spends their action helping narratively — drawing enemy attention, creating an opening, bracing an ally against a fall. No roll, no mechanical bonus, but the GM should honor it in how the scene state is described going forward.

**Domain Collaboration:** When two characters' domains naturally complement each other and both pay their own Strain cost independently, the GM may allow a combined effect that would otherwise require multi-domain — because two characters are involved, not one splitting their focus.

---

## 11. NPC & Threat Design

### Simple NPC Template

**Name / Concept:**
**Strain:** (Mook: 3–5 / Soldier: 8–12 / Elite: 15–20 / Boss: 25–40)
**Armor:** (Mook: 0 / Soldier: 1–2 / Elite: 2–3 / Boss: 4+)
**Attack DR:** The DR players must beat to avoid taking damage from this NPC's action.
**Material Weakness (if any):**
**Signature Move:** One notable thing this NPC does that makes it memorable.
**Conditions it can apply:** (e.g., a snake can apply Poisoned; a berserker can apply Stunned)

### Threat Scaling

| Enemy Type | Strain | Armor | Attack DR | Notes |
|---|---|---|---|---|
| Mook | 3–5 | 0 | 10–15 | Falls easily; threatening in numbers |
| Soldier | 8–12 | 1–2 | 15–20 | Professional fighter; uses tactics |
| Elite | 15–20 | 2–3 | 20–25 | Named foe; has a special ability or weakness |
| Boss | 25–40 | 3–5 | 25–30 | Anchor of a scene; multi-phase if desired |

**Boss Phases:** A Boss can have 2–3 phases. When their Strain drops below a threshold (e.g., half), their behavior, attack DR, or available actions change. Signal the phase shift with a dramatic description.
