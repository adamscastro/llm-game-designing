## Question 009

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1m33iei/alternatives_to_turn_based_rpg_combat_triangles

Date: 2025-07-18

## Problem Description
Alternatives to turn based RPG combat triangles? (i.e. Rock, Paper, Scissors) — Many turn based RPGs seem to fall into "combat triangles". The typical Rock Paper Scissors design where 3 attack types are given strength over one and a weakness to the other.

Examples of Combat Tringles:

Rock <- Paper <- Scissors

Fire <- Water <- Grass (Pokemon)

Data <- Virus <- Vaccine (Digimon)

In something like Final Fantasy, Chrono Trigger, or Dragonquest these elements are kind of a secondary system. But equipment and skills seem to be leaned into more.

What other alternatives are out there?

## Best Human-rated Answer
Damage types, the 'combat triangle' you're trying to avoid, are common because they are a solution to a common problem - first order optimal strategies (FOOS). In brief, if a single option is always the best one, then combat is dull because the player only does one thing for every fight. By adding damage types, a game entices players to use other moves.

A damage type can be either effective, ineffective, or neutral against any other given type. If a damage type is effective against everything, then it's a FOOS and you're back to square one. If no element is better than any other or worse than any other, then all of them are FOOS and you're back to square one. This, fundamentally, is why there are 'combat triangles' (or whatever shape you have) - so that you have another tool to force players to change their strategy depending on the situation.

There are effectively one alternative to type cycles that doesn't immediately result in a FOOS: type pairs. Chrono Chross and FFX use this - each element has only one element that it is both weak to and strong against, and is neutral to all others. For CC, that's Red/Blue, Yellow/Green, and Black/White; for FFX, it's fire/ice and water/lightning. This results in short fights if the player has the opposite element prepped, and much longer ones if they don't. Avoid leaving any element unpaired unless you intend it to be rare and powerful.

## LLM Responses

### ChatGPT-5 Response
That’s a great design question — and a common one among RPG developers who want to move beyond the *“Fire beats Grass beats Water”* paradigm. The **combat triangle** (a closed loop of counters) is popular because it’s easy to teach and quick to balance, but it can start to feel shallow or predictable.

Here are several **alternatives and variations** to consider — grouped by design philosophy:

---

## 🎲 1. **Expanded Relationship Systems**

### ➤ Elemental Webs

Instead of a simple triangle, create a **network of interrelations** — more like *Pokémon’s full type chart* or *Shin Megami Tensei’s weakness/resistance matrix*.

* Each element/attack type has multiple relationships (e.g., Fire strong vs Ice and Nature, weak vs Water and Earth).
* **Pros:** Adds depth and variety.
* **Cons:** Can become hard to learn; needs good UI feedback.

### ➤ Contextual Affinities

Element strengths depend on **environmental or situational factors**:

* Fire attacks are weaker in the rain or underwater zones.
* A "Light" attack is stronger if used after a "Darkness" debuff (synergy rather than hierarchy).
* Encourages *adaptation*, not memorization.

---

## ⚔️ 2. **Behavioral or Tactical Counters**

Make combat less about *types* and more about *intentions* or *styles*.

### ➤ Stance / Tempo Systems

Borrow from fighting games or *Dark Souls* poise mechanics:

* Aggressive → Punishes Defensive
* Defensive → Punishes Reactive
* Reactive → Punishes Aggressive
  But instead of fixed “types,” stances can be *chosen dynamically* in battle.

### ➤ Prediction and Reading

Systems like *Grandia* or *Child of Light* use turn timelines where you can interrupt or delay enemies.

* The counterplay becomes about **timing** rather than **type**.
* Focuses on reading the opponent’s behavior, not memorizing weaknesses.

---

## 🧮 3. **Stat and Resource Interplays**

Shift from categorical advantages to **strategic tradeoffs**.

### ➤ Resource Counters

Different attacks interact with **resources** rather than elements:

* Magic drains mana → affects ability economy.
* Heavy hits drain stamina → control enemy options.
* Poison or bleed affects healing efficiency.
  You’re not “countering” an element, you’re disrupting an *economy*.

### ➤ Positional or Spatial Systems

Borrow from tactical RPGs (*Fire Emblem*, *FFTactics*, *Into the Breach*):

* Advantage comes from *position*, not type.
* Flanking, cover, height, or zone control replace “Fire beats Grass”.

---

## 🧠 4. **Psychological or Narrative Systems**

If your RPG leans into story or character, combat strengths could depend on *emotional or narrative states*.

### ➤ Mood or Emotion States

As seen in *Omori*:

* Happy beats Angry, Angry beats Sad, Sad beats Happy.
* Ties emotion to both mechanical and storytelling meaning.

### ➤ Relationship Dynamics

In party-based games, synergy and affinity between characters could influence power:

* “Jealousy” reduces cooperative attacks.
* “Trust” improves combo effectiveness.
  This ties combat depth to roleplay choices.

---

## 🧩 5. **Procedural or Emergent Systems**

Let players *build* the counter systems dynamically.

### ➤ Combo / Reaction Chains

Borrow from *Chrono Trigger* or *Divinity: Original Sin 2*:

* Elements and states interact physically: Fire ignites Oil, Water conducts Electricity, Ice freezes Water.
* Encourages *experimentation* instead of memorization.

### ➤ Evolving Enemies

Enemies “learn” your habits and adjust resistances dynamically.

* Keeps battles unpredictable.
* Makes adaptation a core player skill.

---

## 🧭 6. **Meta or Hybrid Systems**

You can also layer systems together for richer depth:

* **Small triangle + positional mechanics** (Fire Emblem)
* **Elemental affinities + combo interactions** (Divinity)
* **Emotion + timeline management** (Omori + Grandia)

---

## ✅ Summary of Directions

| Category               | Core Idea                        | Example Inspiration       |
| ---------------------- | -------------------------------- | ------------------------- |
| Expanded relationships | Web of types, not a triangle     | SMT, Pokémon (full chart) |
| Tactical behavior      | Predict and counter actions      | Grandia, Child of Light   |
| Resource interplay     | Manage stamina/mana/synergy      | Darkest Dungeon           |
| Narrative emotion      | Emotions/relationships as states | Omori, Persona            |
| Physical interaction   | Environmental or element combos  | Divinity: OS2             |
| Dynamic adaptation     | Enemies evolve or learn          | Monster Hunter AI mods    |

---

Would you like me to focus on a **specific kind of RPG** (e.g., JRPG-style menu combat, tactical grid-based, or deck-builder/card combat)? I can tailor the alternative systems more precisely to your game’s format.


### Gemini Response
This is a fantastic game design question. You're right that the "combat triangle" is a very common (and sometimes restrictive) design pattern. Its goal is to force player diversification and create simple, clear strategic choices.

The alternatives you're looking for generally move the strategic focus away from a simple "elemental matching" game and toward other systems. As you noted, classics like *Final Fantasy* and *Chrono Trigger* use elements, but they are just one piece of a larger puzzle.

Here are several alternative systems and design philosophies to consider, many of which can be mixed and matched:

### 1. The "Soft Counter" System (Resistances & Vulnerabilities)

This is the system *Final Fantasy* and most WRPGs (Western RPGs) use. Instead of a hard "A beats B," it's a spectrum.

* **How it works:** Instead of Fire *beating* Grass, Fire simply does (for example) +50% damage to an Ice-type enemy, and Ice does -50% damage to that same enemy. An Earth spell might just do 100% neutral damage.
* **Why it's different:** It doesn't invalidate a character. Your Ice Mage isn't *useless* against the Ice monster; they're just suboptimal. They can still contribute with neutral spells or by focusing on healing/buffing. This allows players to win with their "favorite" party, even if it's not perfectly optimized.
* **Example:** In *Chrono Trigger*, hitting an enemy with its "weakness" just results in big damage numbers. It doesn't grant you an extra turn or negate the enemy's attack.

### 2. The "Status and Affliction" System

In this model, the *primary* effect of an "element" isn't damage, but a strategic status effect. The player's goal is to control the battlefield.

* **How it works:**
    * **Fire** attacks might inflict a `Burn` (damage over time).
    * **Ice** attacks might inflict `Slow` or `Freeze` (denying a turn).
    * **Lightning** attacks might inflict `Paralyze` (chance to skip a turn) or `Shock` (reduces defense).
    * **Water** attacks might inflict `Wet` (making the target vulnerable to Lightning and resistant to Fire).
* **Why it's different:** Strategy shifts from "Which element does the most damage?" to "Which *effect* do I need right now?" Do you need to stop a heavy-hitting boss from moving (Ice)? Or wear down a high-defense enemy (Fire)?
* **Example:** Many tactical RPGs lean on this. Applying `Poison` is often more strategically important than a single burst of damage.

### 3. The "Stagger & Break" System

This system creates a two-phase combat loop: first, you "break" the enemy, then you unleash damage.

* **How it works:** Enemies have a "Stagger," "Break," or "Shield" gauge. This gauge is *not* their HP. To deplete this gauge, you must hit them with their specific weaknesses. These weaknesses are often *weapon types* (Sword, Spear, Axe) or *elements* (Fire, Ice, etc.). Once the gauge is broken, the enemy is "Staggered" or "Broken"—they might lose turns, and they take *massively* increased damage from all sources.
* **Why it's different:** It's a "puzzle" to solve for each enemy. The goal isn't just to use the weakness, but to use it *repeatedly* to create a window of opportunity. This encourages a varied party (you need a Spearman, an Axeman, and a Fire Mage) and a sense of rhythm in combat.
* **Example:** *Octopath Traveler* (Shields), *Final Fantasy XIII* (Stagger), *Persona 5* (Hold-Ups after "Downing" an enemy).

### 4. The "Action Economy & Timeline" System

Here, the most important resource isn't your element, but your *turn*. Strategy is based on manipulating the turn order.

* **How it works:** Combat plays out on a timeline. You can see when your characters and the enemies are scheduled to act. Skills now have new properties:
    * **Quick Attacks:** Do low damage but execute instantly.
    * **Charge Attacks:** Do high damage but have a "cast time," pushing your turn back.
    * **Delay Attacks:** Do medium damage and push the *enemy's* turn back on the timeline.
    * **Buffs/Debuffs:** `Haste` (speeds you up) and `Slow` (slows enemies down).
* **Why it's different:** The core question becomes: "Can I kill the enemy before its next turn?" or "Can I delay that boss's ultimate attack long enough for my healer to act?"
* **Example:** *Grandia* (the gold standard for this), *Child of Light*, *Final Fantasy X*'s CTB (Conditional Turn-Based) system.

### 5. The "Positional" System

This system, common in dungeon crawlers, makes *where* you are standing the most important strategic choice.

* **How it works:** Your party is in a formation (e.g., a 1x4 line).
    * **Front Ranks (1-2):** Can hit enemies with melee attacks, and will be hit by enemy melee attacks.
    * **Back Ranks (3-4):** Can only use ranged/magic attacks, and can only be hit by enemy ranged/magic attacks.
* Skills are tied to position. Your Knight's "Shield Slam" only works from Rank 1. Your Archer's "Snipe" only works from Rank 3 or 4. The strategy comes from enemies who can *disrupt your formation* (e.g., "Pull" your healer to the front rank, "Push" your knight to the back).
* **Why it's different:** Party composition is about building a *formation* that can protect itself while executing its game plan.
* **Example:** *Darkest Dungeon*, *Slay the Spire*.

### 6. The "Combo & Synergy" System

You mentioned *Chrono Trigger*—this was its *real* system. The elements were secondary to the "Techs."

* **How it works:** The game is designed to reward you for using specific skills from different characters in sequence or at the same time.
* **Why it's different:** It shifts the focus from individual character actions to *party-wide strategy*. The player is constantly looking for new combinations. This makes every party member feel valuable, as they are a "key" to unlocking new, powerful moves with their teammates.
* **Example:** *Chrono Trigger* (Dual and Triple Techs), *Persona*'s "All-Out Attack" (a reward for exploiting weaknesses, which is a *result* of the Break system, not the *system* itself).

### Summary: Ask "What is the Core Strategic Question?"

A "Combat Triangle" asks the player: **"Do I have the right 'key' for this 'lock'?"**

The alternatives ask different questions:

* **Soft Counters:** "What's the *most efficient* way to win?"
* **Status:** "How can I *control* the battlefield?"
* **Stagger/Break:** "How do I *create an opening*?"
* **Timeline:** "How can I get *more turns* than the enemy?"
* **Positioning:** "Is my *formation* safe and effective?"
* **Combos:** "How can my *team* work together?"

By focusing on one of these other questions, you'll naturally move away from the Rock-Paper-Scissors design.

### DeepSeek Response
Of course! This is an excellent question that gets to the heart of turn-based RPG design. Moving beyond the classic "combat triangle" is a great way to create a more unique and engaging tactical experience.

The core strength of the RPS triangle is its **simplicity and predictability**. Players can easily understand and internalize the rules. The key to designing alternatives is to replace that simple predictability with other forms of strategic depth.

Here are several alternatives, categorized by the core mechanic they replace or enhance.

---

### Category 1: Shifting from "Damage Types" to "Combat Roles & States"

Instead of elements, think about the *function* of an attack or the *state* it imposes on the battle.

#### 1. The "Aggression, Defense, Control" Triangle
This focuses on the intent of an action rather than an elemental affinity.
*   **Control Beats Aggression:** A "Sleep" or "Paralyze" spell stops a high-damage, aggressive attacker in their tracks.
*   **Aggression Beats Defense:** A "Armor Break" or "Defense Pierce" skill overwhelms a heavily fortified defender.
*   **Defense Beats Control:** A "Cleanse" or "Barrier" skill can nullify or block a controlling status effect before it takes hold.
*   **Example:** An enemy Barbarian (Aggression) is charging a powerful attack. You use a Bard's "Lullaby" (Control) to put it to sleep. On its next turn, an enemy Priest (Defense) uses "Dispel" to wake the Barbarian, countering your control.

#### 2. Status Effect & Ailment Synergy
Make the primary goal of combat not to deplete HP, but to apply and exploit status effects.
*   **Combo-Based System:** "Douse" an enemy with Water, then hit them with a Lightning spell for "Electrocuted" (damage over time). Apply "Brittle" (increased physical damage taken), then hit with a blunt attack to "Shatter" them for massive damage.
*   **Ailment as a Win Condition:** Some enemies could be highly resistant to direct damage but vulnerable to being "Poisoned" and "Slowed" until they expire. Others might be immune to ailments but susceptible to being "Taunted" into wasting turns.
*   **Example (Like *Slay the Spire*):** The player builds a deck/loadout around applying "Vulnerable" and "Weak," then uses a specific finisher move that deals extra damage to debuffed enemies.

---

### Category 2: Resource Management & Action Economy

Focus the battle on managing finite resources beyond just HP and MP.

#### 3. The "Stamina" or "Posture" System
Popularized by games like *Sekiro* and *Library of Ruina*, this can be adapted for turn-based play.
*   **Mechanic:** Attacks build up an enemy's "Strain" gauge. When the gauge is full, the enemy is "Broken" for a turn, becoming vulnerable to a powerful, guaranteed critical hit. However, the enemy also has skills to reduce their own Strain.
*   **Tactical Depth:** The battle becomes a push-and-pull. Do you use a fast, low-damage attack to quickly build Strain, or a slow, high-damage one that risks being blocked? Do you break the enemy now, or wait until you have more party members ready to exploit the break?
*   **Alternative:** A "Guard" meter that must be depleted before you can affect HP.

#### 4. Action Point Economy
Instead of "1 move per turn," characters have a pool of Action Points (AP) to spend each round.
*   **Mechanic:** A basic attack costs 1 AP, a special skill costs 2 AP, and a powerful spell costs 3 AP. You can also "Store" AP for future turns.
*   **Tactical Depth:** This creates fascinating decisions. Do you make three weak attacks now, or save up for one devastating spell next turn? Do you use your last point for a minor heal, or let it carry over? Enemies can have skills that drain or "lock" your AP.

#### 5. Cooldowns and "Overheat"
Replace MP with cooldown timers or a risk-reward system.
*   **Cooldown System:** Every skill has a number of turns before it can be used again. This encourages players to rotate through a variety of abilities rather than spamming the most powerful one.
*   **Overheat/Charge System:** Using powerful skills builds "Heat." If the heat gauge maxes out, the character becomes "Overloaded" and is stunned for a turn. This adds a layer of risk management to using your best attacks.

---

### Category 3: Spatial & Positional Awareness

Bring a tactical RPG (TRPG) element into a classic turn-based format.

#### 6. Positioning and Zones
Even without a grid, you can define combat zones: **Frontline** and **Backline**.
*   **Mechanic:** Melee attacks are only effective on the Frontline. Ranged attacks can hit the Backline, but are weaker. Some spells can hit all enemies. "Push" and "Pull" abilities can move enemies between lines.
*   **Tactical Depth:** Do you use a skill to pull their fragile mage from the Backline to the Frontline where your warrior can hit it? Do you have your own tank "Hold the Line" to protect your backline from being pushed?

#### 7. Combo Fields and Environmental Interaction
The battlefield itself becomes a tool.
*   **Mechanic:** Certain attacks leave behind a "effect field" on the enemy or on the ground (e.g., a Grease puddle, an Electric field, a Blessed area). Other attacks interact with these fields.
*   **Example:** A "Fireball" spell shot into a Grease puddle causes it to explode for area damage. A "Lightning Bolt" shot through an Electric field chains to additional enemies.

---

### Category 4: Proactive and Adaptive Systems

Systems where the player and enemy must constantly adapt.

#### 8. The "Telling" or "Telegraph" System
Enemies clearly signal their intent for their next turn.
*   **Mechanic:** A text box or visual cue appears: "Dragon is gathering energy for a Fire Breath!" or "Goblin is preparing to throw a net!"
*   **Tactical Depth:** The player must react *proactively*. Do you have your tank "Defend" to mitigate the Fire Breath? Do you use an "Interrupt" skill on the Goblin? Do you try to kill it before its turn? This shifts the focus from "what is it weak to?" to "what is it going to do?"

#### 9. Adaptive Enemy AI and "Learning"
Enemies that change their behavior based on player actions.
*   **Mechanic:** If you use Fire magic twice in a row, the enemy might cast "Fire Resistance" on itself. If you always start with a buff, the enemy might use a "Dispel" skill.
*   **Tactical Depth:** This forces the player to vary their strategies and not rely on a single winning formula. The optimal strategy becomes *adaptation* itself.

### How to Implement These Ideas:

*   **Don't Throw Out the Baby with the Bathwater:** You can *layer* these systems. A game can have a *weak* elemental triangle, but have combat primarily driven by a **Stamina system** and **Telegraphed attacks**.
*   **Clarity is Key:** Whatever system you choose, it must be easily communicated to the player. Use clear icons, tooltips, and visual/audio feedback.
*   **Start Simple:** Introduce one new mechanic at a time in early-game battles to tutorialize it properly.

By adopting one or a combination of these alternatives, you can create a turn-based combat system that feels fresh, deep, and rewards strategic thinking beyond simply memorizing a chart of strengths and weaknesses.
