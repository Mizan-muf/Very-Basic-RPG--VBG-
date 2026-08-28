# VERY BASIC RPG: ZOMBIE SURVIVAL EDITION (VBG-Z) v2.0
*A Lightweight, Low-Latency System for Asynchronous Play-by-Post Survival Horror*

---

## 1. THE CORE ENGINE

### **The Resolution Roll**
Whenever a survivor attempts a risky or dangerous action, make a single roll:

$$\mathbf{Result = 1d20 + Stat\ Bonus + Trait\ Bonus}$$

1. **Choose Your Stat:** Add your flat Stat bonus (**Force**, **Finesse**, or **Focus**).
2. **Add Applicable Trait Bonuses:**
   - **Major Trait:** Adds **+2** if relevant.
   - **Minor Trait:** Adds **+1** if relevant.
   - *(Traits stack if both apply to the same action, up to a maximum +3 from traits).*
3. **Roll 1d20 and Compare to the Target Difficulty (TN).**

---

### **Target Difficulty Scale**

| Target | Risk Tier | Scenario Example |
| :--- | :--- | :--- |
| **TN 10** | **Routine** | Searching a quiet closet, forcing a wooden latch, basic field dressing in safety. |
| **TN 15** | **Risky** | Shooting a sprinting runner, picking a lock while footsteps approach, jumping a gap. |
| **TN 20** | **Desperate** | Shoving a Licker off an ally, blind-firing in darkness, emergency field surgery. |
| **TN 25+** | **Extreme** | Grappling a Tyrant solo, executing an impossible trick shot on a B.O.W. core. |

---

### **Margin of Success Outcomes**

Compare your total roll to the Target Difficulty (TN):

| Total vs. TN | Outcome Tier | Mechanical & Narrative Result |
| :--- | :--- | :--- |
| **Miss by 5+** | **FAILURE** | The action fails completely. The GM inflicts damage, advances a horde clock, or breaks your gear. |
| **Miss by 1–4** | **SUCCESS WITH COST** | You succeed, but pay a price: mark 1 Strain, spend 1 extra Ammo/Durability box, make noise, or take a condition. |
| **Beat by 0–5** | **CLEAN SUCCESS** | You achieve your goal cleanly without penalty or extra cost. |
| **Beat by 6+** | **CRITICAL** | Perfect execution. Regain 1 Strain OR gain a major advantage (e.g., immediate free move, instant decapitation). |

**Rule Against Softballing (GM Veto):** The cost chosen for a *Success with Cost* must match the danger. Cornered by a Licker and choosing "I scuff my boots" will earn a GM veto. Make the cost hurt.

---

## 2. SURVIVAL CHARACTER CREATION

### **A. Stats (The Three F's)**
Distribute **3 Points** among your stats (Max 2 in any single stat at creation; Hard Cap of 5 through progression):

- **FORCE:** Raw physical power, melee strikes, shoving, dragging casualties, enduring trauma.
- **FINESSE:** Ranged firearm accuracy, stealth traversal, lockpicking, driving, dodging attacks.
- **FOCUS:** Environmental perception, diagnosing infection, scavenging, technical repair, resisting panic.

---

### **B. Survivor Traits (Flat Bonuses)**
Every survivor starts with **1 Major Trait** and **1 Minor Trait**:

- **1 MAJOR Trait (+2 Bonus):** Your pre-collapse archetype or primary survival training.
- **1 MINOR Trait (+1 Bonus):** A specific habit, secondary background skill, or tactical perk.

#### **Sample Major Traits (+2)**
- **S.T.A.R.S. / SWAT Specialist:** Trained in tactical room clearing, weapon control, and crisis response.
- **Combat Engineer / Mechanic:** Specialist in generator repair, hotwiring vehicles, traps, and barricades.
- **Trauma Surgeon / Field Medic:** Expert in wound stabilization, chemical synthesis, and emergency surgery.
- **Bio-Researcher / Virologist:** Knowledge of B.O.W. mutations, virus strains, and suppressant crafting.
- **Urban Scavenger:** Skilled in stealth traversal, spotting hidden supply caches, and navigating ruins.
- **Wasteland Pointman:** Specialist in tracking movement, silent takedowns, and long-range optics.

#### **Sample Minor Traits (+1)**
- **Steady Aim:** Bonus to firearm rolls when firing from cover or taking time to aim.
- **Cold-Blooded:** Bonus to Focus checks when resisting horror jump-scares and panic.
- **Field Chemist:** Extra yield when crafting/mixing herbs, medical chemicals, or gunpowder.
- **Gunsmith:** Can repair degraded firearms and salvage usable ammo/parts from broken guns.
- **Light Sleeper:** Cannot be ambushed while resting in semi-secure zones.
- **Silent Step:** Moving without triggering ambient noise checks.

---

### **C. Vitals: Strain & Armor**
- **Starting Strain:** 5 (Hard Cap: 10). Represents health, stamina, and mental composure.
- **Starting Armor:** 0 Boxes. Armor is not free; it must be looted or crafted.

---

### **D. Starting Inventory: 4 Base Slots**
Your base inventory capacity is strictly **4 Slots**.

---

## 3. TACTICAL SPECIALIZATIONS (ABILITIES)

Survivors choose 1 **Specialization Domain** (e.g., *Close-Quarters Defense, Precision Marksmanship, Field Triage, Structural Fortification*). Specializations modify actions using Strain:

| Scale Tier | Strain Cost | Tactical Effect & Limits |
| :--- | :--- | :--- |
| **MINOR** | **0 Strain** | Minor tactical utility (shoves, rapid vital checks, defensive repositioning). *Just Roll.* |
| **STANDARD** | **1 Strain** | Tactical feats (knife counter during a grab, double-tap, combat suture). *Spend 1 Strain + Roll.* |
| **MAJOR** | **2 Strain** | Desperate emergency maneuvers (dragging an ally out of a swarm under fire). *Spend 2 Strain + Roll.* |

*Note: The god-like "Miracle" scale is completely removed. Humans cannot alter reality.*

---

## 4. AMMO & FIREARM MANAGEMENT

In survival horror, guns are noisy, powerful, and limited by ammunition.

### **Ammo Storage & Carrying**
- Ammunition is tracked in **Ammo Boxes / Magazines**.
- **1 Ammo Slot = 1 Medium Inventory Slot.**
- **Standard Capacities per Slot:**
  - **9mm / Handgun Ammo:** 30 Rounds (3 Full Reloads / Magazines)
  - **Shotgun Shells:** 12 Shells
  - **Rifle / Mag Ammo:** 10 Rounds

### **Firearms & Reload Economy**
- **Handgun (Medium, 1 Slot):** Uses 9mm. Quietest firearm. Can reload 1 magazine as part of an action.
- **Shotgun (Large, 2 Slots):** Uses Shells. High close-range damage. Bypasses 1 Armor box on targets. Reloading shell-by-shell costs an action for 4 shells.
- **Rifle (Large, 2 Slots):** Uses Rifle ammo. Ignores distance penalties; high stopping power.

### **Gunfire Noise & Threat Clock (1–6)**
Every unsuppressed gunshot ticks the local area **Noise Clock** up by +1 (+2 for Shotguns/Magnums).
- **At Noise 6:** A roaming zombie horde or a B.O.W. Stalker (Mr. X / Nemesis archetype) enters the scene immediately.

---

## 5. WEAPON & TOOL DURABILITY

Melee weapons and survival tools degrade under heavy use.

### **Durability Boxes**
Every melee weapon and tool has **Durability Boxes**:
- **Improvised Weapon (Pipe, Board):** ⬜ (1 Box)
- **Combat Knife / Machete:** ⬜⬜ (2 Boxes)
- **Fireaxe / Crowbar / Steel Bat:** ⬜⬜⬜ (3 Boxes)

### **Degradation Mechanics**
- **On a Success with Cost (Miss by 1–4):** A player can choose to mark 1 Durability Box instead of taking Strain or Damage.
- **On a Failure (Miss by 5+):** The weapon automatically loses 1 Durability Box (or gets stuck in a target).
- **When all boxes are marked:** The weapon breaks or snaps and becomes useless.

### **Firearm Jamming & Wear**
- **Natural 1 on a Firearm Roll:** The gun **jams**. Clearing the jam requires a full action and a Focus TN 10 check.
- **Unmaintained Firearms:** Guns found in flooded/ruined zones start with 1 Wear box. If forced to soak damage, the gun breaks until repaired with spare parts by a *Gunsmith*.

---

## 6. PROTECTIVE GEAR & ARMOR

Characters start with **0 Armor**. Armor must be looted or crafted:

| Armor Type | Armor Boxes | Encumbrance / Penalty | Durability & Repair |
| :--- | :--- | :--- | :--- |
| **Leather / Padding** | ⬜ (1 Box) | Takes 1 Slot if not worn | Shreds after 1 soak; single use. |
| **Ballistic / Kevlar Vest** | ⬜⬜ (2 Boxes) | None | Soaks bullet/blade hits; repair with Kevlar kit. |
| **Heavy Riot Gear** | ⬜⬜⬜ (3 Boxes) | -2 penalty to Finesse stealth rolls | High bite defense; heavy and noisy. |

**Armor Rule:** Marking an Armor box completely negates 1 instance of incoming Strain/harm. Marked boxes represent shattered plates or torn material and require repair to restore.

---

## 7. INVENTORY CAPACITY & CONTAINERS

### **Base Capacity: 4 Slots**
Everything carried must fit into your slots.

- **Small Items (1/4 Slot):** Ammo boxes, keys, single herbs, lighter, batteries (up to 4 fit in 1 Slot).
- **Medium Items (1 Slot):** Handguns, combat knives, medical sprays, rations, flashlights.
- **Large Items (2 Slots):** Shotguns, rifles, crowbars, fuel cans.

### **Containers & Expansions**
- **Belt Pouch (+1 Slot):** Carries small items only.
- **Rucksack (+2 Slots, Hard Cap 7 Slots Total):** Expands capacity.
  - **Emergency Drop Mechanism:** If grappled by a zombie or B.O.W., a player can declare *"I drop my pack"* to automatically break free without taking damage, leaving the pack on the ground.

---

## 8. MEDICAL RECOVERY & INFECTION ENGINE

Strain and Armor do **not** recover automatically during rest scenes.

### **Medical Consumables Matrix**
- **Green Herb (1/4 Slot):** Restores 2 Strain.
- **Green + Green Herb (1/4 Slot):** Restores 4 Strain.
- **Green + Red Herb (1/4 Slot):** Restores full Strain (5/5).
- **Green + Blue Herb (1/4 Slot):** Restores 2 Strain and lowers Infection Track by 1 step.
- **First Aid Spray (1 Slot):** Instantly restores full Strain and clears Bleeding.

---

### **Virus Infection Track (0–5)**
Gained when bitten, clawed, or exposed to B.O.W. fluids without sealed armor:

- **Stage 0 (Clean):** Healthy.
- **Stage 1 (Exposed):** Low fever. No mechanical penalty yet.
- **Stage 2 (Incubation):** Max Strain reduced by 1 (Cap: 4).
- **Stage 3 (Necrosis):** Max Strain reduced by 2 (Cap: 3). -2 penalty to all Focus rolls.
- **Stage 4 (Mutation):** Max Strain reduced by 3 (Cap: 2). Gain +2 Force (unnatural strength), but must pass a Focus TN 15 check under stress to avoid bloodlust.
- **Stage 5 (Terminal / B.O.W.):** Character succumbs to the virus and becomes an NPC monster.

---

## 9. INCAPACITATION, BLEEDING OUT & DEATH

When reduced to **0 Strain** and holding no active Armor:

1. **Downed:** You collapse immediately and cannot move or take offensive actions.
2. **Bleeding Out Timer:** You have **1 Round / 24-Hour Post Window** for an ally to stabilize you (expending bandages, a herb, or a successful medicine roll). If untreated by the end of the window, the survivor dies.
3. **Swarm Execution / Coup de Grâce:** If a zombie or B.O.W. is in melee range of a downed survivor and no ally draws its aggression, the creature automatically executes or infects the downed character without requiring an attack roll.

---

## 10. PROGRESSION ECONOMY

The GM awards **PP (Progression Points)** for completing objectives, surviving encounters, and consistent posting:

- **[10 PP] Increase Strain Cap:** Increase Max Strain by +1 (Cap: 10).
- **[15 PP] New Specialization Domain:** Unlock a new tactical discipline.
- **[20 PP] New Minor Trait:** Add a new +1 survival trait.
- **[20 PP] Upgrade Trait:** Upgrade a Minor Trait (+1) to a Major Trait (+2).
- **[25 PP] Stat Increase:** +1 to Force, Finesse, or Focus (Hard Cap: 5).

---

## 11. SURVIVAL CHARACTER SHEET TEMPLATE

```text
==================================================
RESIDENT EVIL VBG-Z: SURVIVOR DOSSIER
==================================================
Name:
Callsign / Alias:
Pre-Collapse Profession:
Background Concept:

STATS (3 Points distributed at creation. Max 2. Hard Cap 5.)
Force:   +0
Finesse: +0
Focus:   +0

TRAITS (Flat bonuses to 1d20 rolls)
[Major Trait] (+2 Bonus): 
[Minor Trait] (+1 Bonus): 

TACTICAL SPECIALIZATION
Domain Name: 
Description: 

VITALS & PROTECTION
Strain:    [X][X][X][X][X] (5/5)
Armor:     [ ][ ] (0/0 - Granted by equipped gear)
Infection: [0/5] Stage 0 (Clean)

ACTIVE CONDITIONS
- None

INVENTORY (4 Base Slots)
[Slot 1]: 
[Slot 2]: 
[Slot 3]: 
[Slot 4]: 
==================================================
```
