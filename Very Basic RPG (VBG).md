# VERY BASIC RPG: ZOMBIE SURVIVAL EDITION (VBG-Z) v2.0
*A Lightweight, Low-Latency System for Asynchronous Play-by-Post Survival Horror*

---

## 1. THE CORE ENGINE

### **The Resolution Roll**
Whenever you attempt a risky or dangerous action, roll:

$$\mathbf{Result = 1d20 + Stat\ Bonus + Trait\ Bonus}$$

1. **Stat Bonus:** Add Force, Finesse, or Focus.
2. **Trait Bonus:** Add **+2** for a relevant **Major Trait**, and **+1** for a relevant **Minor Trait** (Max +3 from traits).
3. **Compare to Target TN:** Roll 1d20 + bonuses against the Target Difficulty set by the GM.

---

### **Target Difficulty & Outcomes**

| Target | Tier | Example |
| :--- | :--- | :--- |
| **TN 10** | **Routine** | Searching a quiet closet, forcing a wooden latch, basic field dressing. |
| **TN 15** | **Risky** | Shooting a runner, picking a lock under pressure, jumping a gap. |
| **TN 20** | **Desperate** | Shoving a Licker off an ally, blind-firing in pitch dark, emergency surgery. |
| **TN 25+** | **Extreme** | Grappling a Tyrant solo, executing an impossible trick shot on a B.O.W. core. |

| Margin vs. TN | Outcome | Narrative & Mechanical Result |
| :--- | :--- | :--- |
| **Miss by 5+** | **FAILURE** | Goal fails. GM inflicts damage, advances threat, or breaks gear. |
| **Miss by 1–4** | **COST** | Goal succeeds, but pay a price: 1 Strain, 1 ammo/durability box, or noise. |
| **Beat by 0–5** | **CLEAN** | Goal succeeds cleanly with no penalty. |
| **Beat by 6+** | **CRITICAL** | Perfect success. Regain 1 Strain OR gain a major tactical advantage. |

---

## 2. CHARACTER CREATION

### **A. Stats (Distribute 3 Points)**
- **FORCE:** Melee strikes, shoving, dragging casualties, enduring trauma (Max +2 at creation).
- **FINESSE:** Firearm accuracy, stealth traversal, lockpicking, dodging (Max +2 at creation).
- **FOCUS:** Senses, diagnosing infection, scavenging, repair, resisting panic (Max +2 at creation).

### **B. Survivor Traits**
- **1 Major Trait (+2 Bonus):** Pre-collapse archetype (e.g., *S.T.A.R.S. Operative, Trauma Surgeon, Combat Engineer, Urban Scavenger*).
- **1 Minor Trait (+1 Bonus):** Secondary skill or perk (e.g., *Steady Aim, Cold-Blooded, Field Chemist, Silent Step*).

### **C. Vitals & Capacity**
- **Starting Strain:** 4 (Hard Cap: 10). Represents health, stamina, and composure.
- **Starting Armor:** 0 Boxes. Armor is granted only by equipped protective gear.
- **Inventory Capacity:** 4 Base Slots (Small items stack 4 per slot; Medium items 1 slot; Large items 2 slots).

---

## 3. SPECIALIZATIONS & DAMAGE

### **Tactical Specialization (Abilities)**
Pick 1 Specialization Domain (e.g., *Close-Quarters Defense, Precision Marksmanship, Field Triage*):
- **MINOR (0 Strain):** Basic tactical utility or minor maneuvers. *Just Roll.*
- **STANDARD (1 Strain):** Focused tactical feats (knife counter during a grab, combat suture). *Spend 1 Strain + Roll.*
- **MAJOR (2 Strain):** Desperate emergency maneuvers (dragging an ally out of a swarm under fire). *Spend 2 Strain + Roll.*

### **Encountering Enemies**
- **Read the scene:** The GM states enemy numbers, distance, exits, cover, and hazards. Include an intent and a fallback in your post.
- **Distance matters:** Melee is quiet but risks grabs; firearms work at range but create Noise.
- **Survive first:** Retreat, block routes, and use cover when safer than fighting.
- **Aim for the stop:** Headshots, fire, or identified weak points end infected; body shots may only buy time.
- **Treat grabs as urgent:** Break free or get help before a bite. Never leave a Downed survivor beside a hostile.
- **Track your shots:** Unsuppressed gunfire raises Noise; declare reloads and track ammo.

### **Taking Damage & Incapacitation**
1. **Soaking Harm:** When taking a hit, mark **1 Strain** or mark **1 Armor Box** from equipped gear.
2. **Incapacitation (0 Strain & 0 Armor):** You collapse. You are **Downed** and **Bleeding Out**.
3. **Bleeding Out Clock:** Allies have **1 Round / 24-Hour Post Window** to stabilize you with first aid or medical supplies. If untreated, your character dies or is executed by hostiles.

---

## 4. SURVIVAL CHARACTER DOSSIER

```text
==================================================
RESIDENT EVIL VBG-Z: SURVIVOR DOSSIER
==================================================
Name:
Callsign / Profession:

STATS (3 Points. Max +2 at creation.)
Force:   +0
Finesse: +0
Focus:   +0

TRAITS (Flat bonuses to 1d20 rolls)
[Major Trait] (+2 Bonus): 
[Minor Trait] (+1 Bonus): 

SPECIALIZATION
Domain Name: 
Description: 

VITALS & PROTECTION
Strain:    [X][X][X][X] (4/4)
Armor:     [ ][ ] (0/0 - Granted by equipped gear)
Infection: [0/5] Stage 0 (Clean)

ACTIVE CONDITIONS: None

INVENTORY (4 Base Slots)
[Slot 1]: 
[Slot 2]: 
[Slot 3]: 
[Slot 4]: 
==================================================
```
