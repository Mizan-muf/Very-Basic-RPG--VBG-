# VERY BASIC RPG: ZOMBIE SURVIVAL EDITION (VBG-Z) v2.0
*A lightweight d20 ruleset for asynchronous Play-by-Post survival horror.*

---

## 1. THE CORE ENGINE

### The Resolution Roll
When your survivor takes a risky, uncertain, or contested action under pressure:

**Roll:** `1d20 + relevant Stat bonus + applicable Trait bonus`

1. **Stat Bonus:** Add Force, Finesse, or Focus (-1 to +2).
2. **Trait Bonus:** Add **+2** for a relevant **Major Trait**, and **+1** for a relevant **Minor Trait** (max one of each per roll).
3. **Compare to Target TN:**
   * **TN 10 (Routine):** Low-stress action, basic survival task.
   * **TN 15 (Risky):** Standard combat shot, evasion, prying a door under threat.
   * **TN 20 (Desperate):** Life-or-death shot, jumping across a collapsed fire escape.
   * **TN 25+ (Extreme):** Staggering a massive B.O.W., escaping a closing hydraulic blast door.

### Result Tiers & Outcomes
* **Failure (Miss by 5+):** You fail and suffer serious consequences (take 1 Strain or lose 1 Armor box, gain a Condition, alert enemies, or advance the Noise Clock).
* **Success with Cost (Miss by 1–4):** You achieve your objective, but pay a price: mark 1 Strain or Armor box, lose 1 weapon Durability box, consume ammunition, or gain a Condition.
* **Clean Success (Beat by 0–5):** You achieve your goal cleanly without penalty.
* **Critical Success (Beat by 6+):** Perfect execution. You achieve your goal and gain an extra advantage: bonus damage, stagger an enemy, or lower the local Noise Clock by -1.

---

## 2. CHARACTER CREATION

### A. Stats (Distribute 3 Points)
Allocate 3 points across the three core stats (Max +2 at creation):
* **FORCE:** Physical power, melee strikes, shoving, lifting debris, enduring trauma.
* **FINESSE:** Agility, precision marksmanship, sprinting, lockpicking, silent movement.
* **FOCUS:** Awareness, diagnosing infection, searching rooms, mental composure under horror.

### B. Survivor Traits
* **1 Major Trait (+2 Bonus):** Your pre-collapse profession or primary archetype (e.g., S.T.A.R.S. Operative, Beat Cop, Trauma Surgeon, Combat Engineer, Wasteland Hunter).
* **1 Minor Trait (+1 Bonus):** A specific habit, combat reflex, or survival perk (e.g., Steady Aim, Quick Draw, Silent Step, Tourniquet Specialist, Pack Optimizer).

### C. Vitals & Starting Capacity
* **Strain (Max 10):** Begins at **4 Strain**. Strain represents shock, stamina, blood loss, and will to survive.
* **Armor Boxes:** Begins at **0 Armor Boxes**. Armor is gained only by finding and equipping protective gear.
* **Inventory Capacity:** Strictly **4 Inventory Slots**.

---

## 3. SURVIVAL ACTION ECONOMY & SCENES

### Action Economy (Per Post Turn)
Each survivor post during an active scene allows:
* **1 Major Action:** Attack/Shoot, Sprint/Zone Move, Apply Full Medical Treatment (G+R, Spray), Breach/Force a door, Reload an empty firearm, or Clear a jammed weapon.
* **1 Minor Action:** Ingest a single herb (G or B), Draw/Holster a weapon, Trade an item with an adjacent ally, Latch/Unlock a door, or Brace/Take Cover (+1 to next shot/defense).
* **Free Actions:** Dropping carried items, brief radio/tactical speech, or defensive knife grab counters.

### Scene Framework
* **Exploration Scene:** Searching rooms, investigating lore, and solving environmental puzzles. The Noise Clock only advances on loud actions.
* **Combat Scene (Side-Initiative):** GM declares incoming enemy threats $\rightarrow$ all players post Major + Minor actions within the 24h window $\rightarrow$ GM resolves all outcomes simultaneously.
* **Safe Room (Rest Scene):** Fortified sanctuary. Immune to the Noise Clock. Free 4-slot inventory & Item Box management, medical treatments, and Typewriter checkpoint logs.
* **Sector Transition:** Moving to a new zone without active pursuit reduces the Noise Clock by -1.

---

## 4. DAMAGE, INJURIES & INFECTION

### Taking Harm
1. **Armor Soaks First:** If you wear armor, mark 1 Armor Box (⬜) to negate 1 instance of physical damage. When all boxes are marked, the armor is ruined.
2. **Strain Loss:** Unmitigated hits mark 1 Strain.
3. **Downed / Bleeding Out:** When you reach **0 Strain & 0 Armor**, you collapse. Allies have 1 full 24-hour round to apply a medical item. If hit again or left untreated, your survivor dies.

### Standard Conditions
* **Bleeding:** Lose 1 Strain at the end of each combat scene until treated. Cured by Green Herb mixtures or First Aid Spray.
* **Poisoned:** Lose 1 Strain whenever you take a physical action. Cured by Blue Herb mixtures or First Aid Spray.
* **Limb Damaged:** Leg (-2 Finesse, cannot sprint) or Arm (-2 Force, cannot wield 2-handed weapons). Cured by Full-Heal (G+R) or First Aid Spray.
* **Panicked:** Cannot spend Strain on Specializations. Cured by reaching a Safe Room or an ally passing a Focus TN 10 check.

### Virus Infection Track (0 to 5)
Zombie bites and biological critical failures advance the track by +1 Stage:
* **Stage 0 (Clean):** Healthy.
* **Stage 1 (Exposed):** Low fever.
* **Stage 2 (Tremors):** -1 to Focus rolls.
* **Stage 3 (Cellular Breakdown):** Max Strain capped at 6; -1 to all rolls.
* **Stage 4 (Terminal Agony):** Max Strain capped at 3; cannot sprint.
* **Stage 5 (Transformation):** Death. The survivor turns into a hostile B.O.W.
*(Infection can be reduced by -1 Stage using Blue Herb combinations, or stalled for 24h with Antiviral Serums).*

---

## 5. GEAR & NOISE

### Weapons & Durability
* **Handgun (1 Slot):** 15-round mag. +1 Noise per shot. Nat 1 jams the gun (1 Major Action to clear).
* **Shotgun (2 Slots):** 6 shells. +2 Noise per shot. Close-range stagger / spread.
* **Tactical Rifle (2 Slots):** 5 rounds. +2 Noise per shot. Extreme range armor penetration.
* **Combat Knife (1 Slot, ⬜⬜⬜ 3 Durability):** Close defense & grab counters. Breaks permanently when all 3 boxes are marked (no repairs).
* **Heavy Tools (2 Slots, ⬜⬜⬜ 3 Durability):** Fireaxe, Crowbar. +1 to Force breaching rolls.

### Medical Items
* **Green Herb (G, 1/4 Slot):** Restores 1 Strain, cures Bleeding.
* **Green + Green (G+G, 1/4 Slot):** Restores 3 Strain, cures Bleeding.
* **Green + Blue (G+B, 1/4 Slot):** Restores 1 Strain, cures Bleeding & Poisoned, reduces Infection by -1 Stage.
* **Green + Red (G+R, 1/4 Slot):** Full Strain recovery, cures Bleeding & Limb Damaged.
* **Green + Red + Blue (G+R+B, 1/4 Slot):** Full Strain recovery, cures all conditions, reduces Infection by -1 Stage.
* **First Aid Spray (1 Slot):** Full Strain recovery, cures all physical conditions.

---

## 6. SURVIVOR DOSSIER TEMPLATE

Identity
Name: ____________    Callsign / Profession: ____________

Stats (3 Points Allocated)
Force: +__    Finesse: +__    Focus: +__

Traits & Abilities
Major Trait (+2): ________________________
Minor Trait (+1): ________________________
Tactical Specialization: __________________

Vitals & Status
Strain: [ ][ ][ ][ ] /4 (Max 10)
Armor: ⬜ / 0 Boxes
Infection Track: [0] Clean (0/5)
Active Conditions: None

Inventory (Strict 4 Slots)
1. [Handgun - 15/15 rds (1 Slot)]
2. [Combat Knife - ⬜⬜⬜ (1 Slot)]
3. [9mm Ammo Box - 15 rds (1/4 Slot) / Empty]
4. [Empty Slot]
