## Question 010

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1k44vxw/can_we_discuss_armor_in_turnbased_games

Date: 2025-04-21

## Problem Description
Can we discuss "armor" in turn-based games? — CONTEXT: I'm writing a turn-based dungeon crawler (think, Eye of the Beholder, Might and Magic, Etrian Odyssey, Dungeon Master, etc).

I've seen a lot of armor systems in various games and wanted to discuss which of these you think have merit.

I've seen something like DnD, (THAC0) where armor is some kind of roll, where if it succeeds, you take no damage, but if it fails, you take 100% of the damage.

Then there is something like the first Final Fantasy, where you have "absorb" and "evade" in your armor. "absorb" subtracts from the amount of damage you take, and "evade" can negate the damage all-together.

You also have systems where armor is another layer over HP. First you lose your armor, and then you lose your HP. Some attacks then can "bypass" armor and go straight to HP.

In some games, "armor" is more like a damage resistance %. So maybe you get some armor, and then you take 50% damage from attacks. This could be like the blue ring in Zelda.

You also have systems where it depends where on your body you got hit, and different effects happen based on the armor there. I'm not really writing a game like this so let's ignore this case please.

Also this discussion can dip into how "HP" should work in a game. It seems most games do something similar to what DnD does, but I wonder if it could be improved without being over-complicated.

In some games armor actually doesn't protect you as such, but gives you a skill, which is usually a defensive skill that you can use in combat.

So what kind of armor system do you like in games like this? What should armor do in a game like this (game-mechanics-wise). What kind of armor systems lead to fun gameplay where you look forward to upgrading your armor?

Thanks!

## Best Human-rated Answer
For incremental stats, where the defense rating can vary greatly, use a damage resistance or evasion stat.

For more tactical use of defense with little change and smaller numbers, flat resistance is good.

Temporary health is good for resource management and encouraging aggressive playstyles.

## LLM Responses

### ChatGPT-5 Response
Excellent design question — this is a classic and rich topic in RPG systems. Let’s go through how you (as the developer) could *solve* or *refine* this design problem by looking at **the goals of armor** in a turn-based dungeon crawler, and then reviewing possible **systemic solutions** and **hybrid approaches** that balance realism, fun, and clarity.

---

## 🎯 Step 1. Clarify What Armor *Should Do* in Your Game

Before picking a system, decide the **design purpose** of armor in your particular game. Armor can:

1. **Reduce risk:** Make the player feel safer against stronger enemies.
2. **Add tactical choice:** Encourage decisions between heavy vs. light setups.
3. **Provide progression:** Reward exploration and upgrades.
4. **Shape pacing:** Control how fast HP attrition happens in a dungeon crawl.
5. **Enable build variety:** Let armor interact with skills, classes, or elements.

The *right* system depends on which of these you care about most.

---

## 🧮 Step 2. Evaluate Common Armor Models

### 1. **Binary Mitigation (DnD-style AC / “avoid or not”)**

* **Mechanic:** Attack rolls vs. Defense rolls decide hit or miss.
* **Pros:** Simple, tense, easy to understand.
* **Cons:** Highly swingy — armor can feel useless if unlucky, or too strong if lucky.
* **Best for:** Systems that emphasize uncertainty and dice tension (e.g., tabletop-feel dungeon crawlers).

✅ **Design Tip:** Combine it with a *“grazing” mechanic* — near-misses deal partial damage (like *Pillars of Eternity*). This keeps outcomes less binary while preserving DnD feel.

---

### 2. **Flat Damage Reduction (“absorb”)**

* **Mechanic:** Subtract armor from incoming damage.
* **Pros:** Easy to calculate; makes incremental upgrades feel tangible.
* **Cons:** Scales poorly — either too effective at low levels or irrelevant at high levels.
* **Best for:** Games with predictable damage numbers and limited scaling.

✅ **Design Tip:** Use **diminishing returns** — e.g. `EffectiveDamage = RawDamage * (100 / (100 + Armor))` to keep armor relevant across levels.

---

### 3. **Layered HP / Armor Pool**

* **Mechanic:** Armor acts as temporary HP or a “shield.”
* **Pros:** Very clear; adds tension as the armor breaks down mid-fight.
* **Cons:** Can feel too binary if all armor breaks early and becomes irrelevant.
* **Best for:** Dungeon crawlers that want visible attrition — e.g., “armor cracked” status as a tension cue.

✅ **Design Tip:** Let some attacks *bypass* armor or *damage both armor and HP*, adding enemy variety.

---

### 4. **Percentage Resistance**

* **Mechanic:** Armor reduces a % of incoming damage.
* **Pros:** Scales smoothly, easy to balance at high levels.
* **Cons:** Can feel bland — “more % reduction” lacks tactile satisfaction.
* **Best for:** Systems with multiple damage types (physical, elemental, etc.).

✅ **Design Tip:** Add **conditional resistances** — e.g. “plate reduces slashing but weak to magic.” Keeps decisions interesting.

---

### 5. **Skill-Granting Armor**

* **Mechanic:** Armor grants defensive abilities instead of pure stat boosts.
* **Pros:** Adds variety and synergy potential.
* **Cons:** Harder to balance and script AI around.
* **Best for:** Games emphasizing *buildcrafting* and *combo systems* (like Etrian Odyssey).

✅ **Design Tip:** Combine passive defense and active abilities. Example: *“Iron Mantle: +10% DR, Skill: Fortify – halve next attack’s damage.”*

---

## ⚙️ Step 3. Hybrid Systems That Work Well in Dungeon Crawlers

You don’t have to pick just one — here are **battle-tested hybrids**:

### **Hybrid A: % Resistance + Breakable Armor**

* Armor gives resistance but has *durability*. When durability breaks, resistance drops.
* Keeps armor meaningful over long crawls, adds resource tension.

### **Hybrid B: Damage Reduction + Avoidance**

* Combine “absorb” with “evade chance.”
* Light armor = high evade, low absorb; heavy armor = high absorb, low evade.
* Works great for party systems (rogue vs. warrior distinction).

### **Hybrid C: Armor as Temporary HP with Passive Bonus**

* Armor = buffer HP (like a shield), but also grants minor resistance.
* Makes armor visually impactful and tactically relevant — players *feel* when armor breaks.

---

## 🧩 Step 4. Make It *Feel* Good

Regardless of math:

* **Feedback matters:** Distinct sounds/visuals when armor deflects, grazes, or breaks.
* **Progression pacing:** New armor should *change the way fights feel*, not just numbers.
* **Synergy:** Consider how armor interacts with spells, items, and tactics.

Example:

> “Fire-resistant armor + Ice wand” encourages dual-class play and party synergy.

---

## 💡 Bonus Idea — “Armor Stress”

Add a mechanic where armor “absorbs” damage but gains *stress* (durability wear). Repairing costs resources. This reinforces dungeon attrition and decision-making (press deeper or retreat?).

---

## ✅ Summary Recommendation

For your **turn-based dungeon crawler**, a great balanced system could be:

> **Armor = Hybrid Damage Reduction + Breakable Layers**
>
> * Each armor piece provides a % damage reduction (5–50%).
> * It has *armor HP* that degrades per hit.
> * When armor breaks, reduction drops to a minimal value.
> * Light armor favors *evasion* instead.
> * Some skills or attacks can *bypass* or *target* armor directly.

That system provides:

* Clarity (players see armor “breaking”).
* Tactics (some enemies pierce, others wear down).
* Progression (new armor lasts longer and protects better).
* Dungeon tension (repairs or item management between fights).

---

Would you like me to outline a **specific formula** or example combat round using one of these hybrid systems (with numbers)? That can help you prototype and test the feel quickly.


### Gemini Response
Hello! This is a fantastic topic and one of the most critical design pillars for a turn-based dungeon crawler. The *feel* of combat, the *value* of loot, and the *importance* of a "tank" character all hinge on this one decision.

You've done a great job identifying the most common systems. The key to choosing the right one is to decide what you want the *player's experience* to be.

* Do you want them to feel **unpredictable, high-stakes tension**? (System 1)
* Do you want them to feel a **smooth, predictable power curve**? (System 4)
* Do you want them to make **hard tactical choices every turn**? (System 3)
* Do you want them to focus on **build-crafting and synergy**? (System 5)

Based on your references (especially *Etrian Odyssey* and *Might and Magic*), your game is likely party-based, with specialized roles. This means your armor system should **support character archetypes** (e.g., a "Tank" should feel different from a "Rogue") and make **loot drops exciting and build-defining.**

Here are three robust models that build on your research, designed to create fun gameplay and exciting upgrades.

---

### Model 1: The Modern Hybrid (The "Robust Tank")

This is my top recommendation. It's a blend of your **System 2 (Absorb/Evade)** and **System 4 (% Reduction)**, which creates the most balanced and strategically deep experience.

* **How it Works:** Every character has three core defensive stats:
    1.  **Evasion (or Dodge):** A percentage-based chance to avoid an attack entirely (0% damage). This is primarily driven by a character stat like *Agility* or *Dexterity* and enhanced by *Light Armor*.
    2.  **Defense (Flat Reduction):** A flat number subtracted from *all* incoming physical damage. This is the primary stat for *Heavy Armor*. This makes heavy-armor tanks immune to "death by a thousand cuts" from weak enemies.
    3.  **Resistance (% Reduction):** A percentage-based reduction that is calculated *after* flat Defense. This is typically used for *non-physical* damage (Fire, Ice, Magic, Poison) but can also be a stat on shields (e.g., "10% Physical Resistance").

* **Example Damage Calculation:**
    An Orc hits your Knight for 50 Physical damage.
    * **Step 1 (Evasion):** The Knight (low agility, heavy armor) has a 5% Evasion. You roll and *fail* to evade.
    * **Step 2 (Flat Reduction):** The Knight's Plate Armor + Shield provides 20 Defense. The damage is reduced: $50 - 20 = 30$.
    * **Step 3 (% Reduction):** The Knight's "Stalwart" passive gives 10% Physical Resistance. The remaining damage is reduced: $30 - (30 \times 0.10) = 27$.
    * **Final:** The Knight takes 27 HP damage.

    A Goblin hits the same Knight for 15 Physical damage.
    * **Step 1 (Evasion):** Fail.
    * **Step 2 (Flat Reduction):** $15 - 20 = -5$. Damage is floored to 0.
    * **Final:** The Knight takes 0 damage. They are unfazed by the weak attack.

* **Why it's Fun:**
    * **Creates Clear Roles:** A Rogue will stack Evasion (Light Armor) and hope to take 0 damage, but will be crushed if an attack lands. A Knight will stack Defense (Heavy Armor) and can confidently soak hits from many enemies. A Mage will have low Evasion and Defense, but can stack *Resistances* (Robes) to survive enemy spells.
    * **Solves Scaling:** Flat Reduction (Defense) is great against many small hits. % Reduction (Resistance) is great against single, massive hits. You need both!

* **Exciting Upgrades:**
    * Upgrades aren't just `+1`. A player might have to choose:
    * `Helmet A:` +10 Defense
    * `Helmet B:` +5 Defense, +10% Fire Resistance
    * `Helmet C:` +2 Defense, +5% Evasion
    * This makes loot a *situational choice*. "Oh, we're going into the Fire Cave? I'm equipping Helmet B on my tank."

---

### Model 2: The Strategic Layer (The "Etrian Odyssey" Model)

This model builds on your **System 5 (Armor Grants Skills)**. It assumes that the *real* value of armor isn't its raw stats, but the *new options* it gives you in combat.

* **How it Works:** Armor provides a basic, simple stat (like flat Defense or % DR) to establish a "tier." However, the *primary* feature is that **armor unlocks active or passive abilities.**
    * `Knight's Helm:` Provides +10 Defense. Grants the skill **"Taunt"** (Active: Force all enemies to target you for 2 turns).
    * `Rogue's Boots:` Provides +5 Defense. Grants the passive **"First Strike"** (Passive: On the first turn of combat, act first regardless of speed).
    * `Warlock's Robe:` Provides +2 Defense. Grants **"Retaliation: Fire"** (Passive: When hit by a physical attack, 50% chance to cast a weak `Fireball` on the attacker).

* **Why it's Fun:**
    * **Build-Crafting:** This system turns your equipment screen into your "skill tree." Combat becomes about finding powerful combinations. "If I give my tank the 'Taunt' helm and the 'Retaliation' robe, he becomes a perfect counter-puncher!"
    * **Synergy:** It encourages party synergy. You're not just equipping armor, you're building a "combo machine."
    * **Horizontal Progression:** A "Tier 1" piece of armor with an amazing skill might remain useful for the entire game. This prevents all old loot from becoming instant "vendor trash."

* **Exciting Upgrades:**
    * Finding a new piece of armor is *the most* exciting thing, because it's not just a stat boost—it's a new "toy" to play with.
    * A late-game `Legendary Plate` might have a basic +30 Defense, but its real power is the passive **"Last Stand"** (Once per battle, when HP drops to 0, instead drop to 1 HP and gain +100 Defense for 1 turn).

---

### Model 3: The Resource Management Model (Ablative Armor)

This uses your **System 3 (Armor as HP)**, but with a specific focus on making it a *regenerating resource* to create tactical tension. This is common in sci-fi (shields) but works great for fantasy (e.g., a "Magic Ward" or "Stamina").

* **How it Works:**
    * You have two health bars: **HP** (your life) and **Armor** (your guard/stamina).
    * **HP** does not regenerate between fights (or only slowly/with items). HP loss is *serious*.
    * **Armor** regenerates *fully* after every battle.
    * Most attacks hit **Armor** first. Once Armor is gone, they hit **HP**.
    * The "fun" comes from **enemy and skill design:**
        * `Standard Attacks:` Hit Armor.
        * `Piercing Attacks:` (from Stilettos, arrows, magic) **Bypass** Armor and hit HP directly.
        * `Sunder Attacks:` (from Maces, warhammers) Do *double damage* to Armor.
        * `Defend Skill:` Your "Defend" command in combat now restores 30% of your **Armor** bar instead of just reducing damage.

* **Why it's Fun:**
    * **Tactical Puzzles:** Every fight becomes a puzzle. "Who is the most dangerous enemy? The big Ogre doing Sunder, or the little Goblin with the 'Piercing' dagger?" The answer is almost always the 'Piercing' one.
    * **Clear Status:** The player has a very clear visual indicator of how "safe" they are. Full Armor = safe. No Armor = danger.
    * **Meaningful "Defend":** The "Defend" command, often useless in RPGs, becomes a critical part of your tank's rotation.

* **Exciting Upgrades:**
    * Upgrades are simple but feel great: `+100 Max Armor`.
    * The *most* exciting upgrades are ones that interact with the system:
        * `Shield:` Grants skill **"Brace"** (Restore 50% Armor, 1x/battle).
        * `Armor Enchantment:` "Your Armor now regenerates 10% per turn."

---

### A Note on HP

You're right to question HP. In your reference games, HP is an "attrition" resource. It's the "fuel" you spend to get deeper into the dungeon. The standard "pool of points" (like DnD) is the most proven model for this.

**My suggestion:** Stick with a simple, standard HP pool. Let your **Armor System** be the "fun, complex" part. If both HP and Armor are complex, the game can become a "spreadsheet" chore. The armor system's job is to *protect* the HP pool, which is the player's most valuable resource.

### Final Recommendation

For a game in the spirit of *Etrian Odyssey* and *Might and Magic*, a combination of **Model 1** and **Model 2** is ideal.

* Use the **Modern Hybrid (Model 1)** as your *base*. (Evasion/Defense/Resistance). This gives you a solid, understandable foundation for all characters and items.
* Then, layer in **The Strategic Layer (Model 2)** on *top* of it.
* This way, a `Steel Sword` is just `+10 Attack`. But a `Flame-Tongue Sword` is `+8 Attack, +5% Fire Resistance, Grants "Fire Slash" Skill`.

This gives you the best of both worlds: a clear sense of linear power progression (stats) *and* an exciting, build-defining horizontal progression (skills).

### DeepSeek Response
Of course! This is a fantastic and fundamental question for turn-based game design. The armor system is deeply intertwined with your game's core feel, strategic depth, and the player's sense of progression.

Let's break down the systems you mentioned, discuss their pros and cons, and then synthesize some recommendations for a fun and engaging system.

### Analysis of Common Armor Systems

#### 1. The D&D Model (Binary Hit/Miss with Armor Class)
*   **How it works:** Armor makes you harder to hit. A successful "to-hit" roll means you take 100% damage; a failed one means you take 0%.
*   **Pros:**
    *   **Clarity:** The outcome is simple and dramatic. A "clang" as the attack bounces off your shield is very satisfying.
    *   **Fast Resolution:** The math is usually front-loaded in the roll. Once a hit is determined, damage is quick to apply.
    *   **Emphasis on Avoidance:** Makes high-armor characters feel like unstoppable tanks against weak enemies.
*   **Cons:**
    *   **Frustrating "Whiffs":** A player can feel cheated when an enemy finally lands one hit and it's a massive, unmitigated critical.
    *   **Lack of Tactical Nuance:** There's no "soft" damage. Every attack that gets through is a full-power attack. This can make healing and risk assessment more binary.
    *   **Scalability Issues:** At high levels, if armor values don't scale perfectly, characters can become either untouchable or paper-thin.

#### 2. The Final Fantasy Model (Separate Evade & Absorb)
*   **How it works:** Two stats. "Evade" gives a chance to avoid the attack entirely. "Absorb" (or Defense) subtracts a flat number from the damage of any attack that does land.
*   **Pros:**
    *   **Clear Stat Roles:** Players intuitively understand that Evade is for avoiding damage, and Absorb is for reducing it.
    *   **Strategic Gear Choices:** Do you equip the armor with high Evade but low Absorb for a "dodge tank," or the heavy plate with high Absorb but low Evade for consistent damage reduction?
    *   **Reliability:** Even if you get hit, you know your Absorb will always shave off a chunk of damage, providing a safety net.
*   **Cons:**
    *   **Can Become Opaque:** If the calculations are hidden, players might not know if 10 Evade is better than 15 Absorb.
    *   **Math-Heavy:** The game is constantly doing two calculations (evade roll, then damage subtraction) for every attack.
    *   **Absorb Can Become Irrelevant:** If damage scales high into the late game, a flat +10 Absorb might become meaningless.

#### 3. The "Ablative Layer" Model (Shields over Health)
*   **How it works:** Armor is a separate health bar (like "Shields" in many sci-fi games). You must deplete the armor before you can damage HP. Some attacks bypass it.
*   **Pros:**
    *   **Extremely Intuitive:** The visual feedback is perfect. You see your armor bar deplete, creating a clear sense of your defenses weakening.
    *   **Great for Pacing:** Fights can have distinct phases: the "breach the armor" phase, followed by the more dangerous "attack the health" phase.
    *   **Encourages Variety:** Bypass mechanics force players to have answers for different types of threats.
*   **Cons:**
    *   **Can Feel Like a Grind:** Whittling down a massive armor bar can feel tedious if not balanced correctly.
    *   **All-or-Nothing:** Until the armor is broken, the character is functionally immune to HP-based status effects, which can reduce tactical options.
    *   **Bypass Mechanics can feel Unfair:** If overused by enemies, it can make the player's investment in armor feel worthless.

#### 4. The Damage Resistance % Model (The "Blue Ring")
*   **How it works:** Armor provides a percentage reduction to incoming damage. e.g., 50% resistance means you take half damage.
*   **Pros:**
    *   **Scales Perfectly:** A 50% reduction is equally valuable against an attack that does 10 damage and one that does 1000 damage. It never becomes obsolete.
    *   **Predictable and Reliable:** Players can accurately gauge their survivability. "With this armor, I can survive three hits from that boss instead of two."
    *   **High Perceived Value:** Getting a new armor that takes you from 30% to 40% resistance is a very tangible and exciting upgrade.
*   **Cons:**
    *   **Can Lead to "Sponginess":** If resistance values get too high, combat can slow to a crawl as both sides barely scratch each other.
    *   **Less "Exciting":** The binary "clang" of a miss is replaced with a smaller number, which can be less viscerally satisfying.
    *   **Complex Calculations:** Percentage math, while simple, is slower for humans to process than flat subtraction.

---

### Synthesis: Recommendations for Your Dungeon Crawler

The best systems often **hybridize** these ideas. Based on your context (a tactical, dungeon crawler where upgrading gear is a key motivator), here are some suggested paths:

#### **Recommendation 1: The "Layered Defense" Hybrid (My Top Pick)**

This system combines the best of **Evade/Absorb** and **Damage Resistance %** for deep tactical choices.

*   **Evasion (EV):** A percentage chance to avoid an attack entirely. Governed by agility, shields, and light armor.
*   **Armor (AR):** A flat damage reduction. "The attack hits for 12 damage, but your Armor of 5 reduces it to 7." Governed by heavy armor.
*   **Resistance (RES):** A percentage reduction applied *after* Armor. "The 7 damage is then reduced by your 20% Fire Resistance to 5." Governed by magical gear and specific materials.

**Why this works:**
*   **Fun Upgrades:** Finding a new piece of gear is always exciting. "This helmet gives +2 AR AND +10% Lightning RES? Amazing!"
*   **Clear Character Roles:**
    *   The **Rogue** stacks EV to avoid damage entirely.
    *   The **Knight** stacks AR to laugh off weak attacks.
    *   The **Mage** uses RES to specialize against elemental threats.
*   **Rich Enemy Design:** You can create enemies that challenge these roles. An enemy with high accuracy punishes the Rogue. An enemy that does many low-damage hits punishes the Knight. An enemy that does one big elemental hit punishes the unprepared.
*   **Strategic Depth:** Players must think about damage types and enemy attack patterns.

#### **Recommendation 2: The "Ablative Armor with a Twist"**

This modifies the "layer" model to avoid its pitfalls.

*   **Armor Points (AP):** A secondary health bar that is easier to restore than HP (e.g., through a skill or cheap potions).
*   **HP:** Your true health, hard to restore.
*   **Critical Hits/Piercing Attacks:** These bypass AP and go straight to HP. This is the "twist" that keeps players on their toes.

**Why this works:**
*   **Tactical Resource Management:** Do I use my turn to restore my AP, or do I press the attack? It adds a new dimension to turn-based combat.
*   **High Stakes:** The moment your armor breaks, the fight becomes dramatically more dangerous. This creates fantastic tension.
*   **Exciting Upgrades:** Increasing your max AP is a very clear and desirable power boost.

---

### How HP Fits In and How to Improve It

You're right to question HP. The classic "meat points" model is abstract. Consider giving HP more meaning:

*   **HP as Stamina/Morale:** Instead of physical health, HP represents the character's will to fight, their stamina, and their luck. When it reaches 0, *then* they suffer a real, debilitating wound. This explains why a "Cure" spell can fully restore them—it's restoring their vigor. This is how games like *The Darkest Dungeon* frame it.
*   **Wounds System:** When a character drops below 50% HP, they might suffer a "Wound" that applies a minor debuff (e.g., "-1 Strength"). This makes losing HP feel more impactful and dangerous, rather than just a number ticking down.
*   **Scaled Effectiveness:** A character's performance could degrade as they lose HP. For example, a character below 25% HP does -25% damage. This makes healing more important and prevents the "1 HP is the same as 100 HP" problem.

### Final Thoughts: What Makes Armor Fun to Upgrade?

A great armor system makes the player feel their investment. The upgrade should be:

1.  **Tangible:** The player should notice the difference. Enemies that were dangerous now barely scratch them. A 10% resistance increase should change survival calculations.
2.  **Strategic:** It should open up new tactical options, not just make numbers bigger. A new armor that grants immunity to "Poison" completely changes how the player approaches swamp areas.
3.  **Visual & Thematic:** The armor should look cooler and fit the character's fantasy. A knight in gleaming plate *should* feel more protected than one in leather.

For your dungeon crawler, I would strongly lean towards the **"Layered Defense" Hybrid**. It provides the deepest strategic pool for players to engage with and makes every piece of loot a potential game-changer, which is the heart of a great dungeon crawl. Good luck
