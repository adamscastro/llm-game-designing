## Question 029

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1l6gua8/would_a_purely_milestone_based_leveling_system

Date: 2025-06-08

## Problem Description
Would a purely milestone based leveling system work in an RPG? — I’ve been working on the combat and leveling systems for my game. At its heart, it’s just another point system where putting points into a stat unlocks different abilities based on the class of the character. Abilities can also be unlocked by equipment gear that increases a stat.

The way to gain points right now is to get experience points, just like most other games. But I feel like stepping away from that model. What I’m sorta thinking about is making it more a milestone based system. As you explore, defeat bosses, find treasure etc, you gain a point and can spend it on a stat.

The pros I see to this are that it encourages engaging with content you might not engage with, explore more, solve puzzles, etc… the cons would be around the combat system itself. It feels like removing XP makes progression less linear and potentially less satisfying. It also makes me think that combat would be less important than if I had just used experience points.

any thoughts?

Edit:

This gained a lot more traction than I was really expecting! Lot of good ideas and suggestions for games for me to take a look at and study.

## Best Human-rated Answer
It does work.

I can name several TTRPGs (Fate is the first one that comes to mind) that uses milestone-based progression; but a lot of other games that don't focus as much on combat do the same. It does make combat less important to the game - but if that's the game you're trying to build, good. Rewards should be for what you want the game to be about: if you are building a combat-based RPG, reward combat. If you aren't, don't. If your RPG is a mix of combat and non-combat things, make sure you reward all of it.

## LLM Responses

### ChatGPT-5 Response
That’s a great design question — and one that shows real thought about *player motivation* and *progression feel*, which are at the heart of RPG systems.

Here’s a breakdown of **possible solutions and approaches** to help the developer refine (or balance) a milestone-based system:

---

### 💡 1. **Hybrid Progression System (Milestones + XP-lite)**

Instead of abandoning XP entirely, consider **layering milestones over a simplified XP system**:

* Players get *small, incremental XP* for combat (so fights still feel rewarding).
* Major **milestones** (bosses, puzzles, exploration, story beats) give *big, meaningful stat points*.

✅ **Pros:** Keeps combat feeling valuable while still rewarding exploration.
❌ **Cons:** Slightly more complex to balance but often the most satisfying middle ground.

**Example:**

* *Hollow Knight* rewards combat with currency (for gear) but real progression comes from finding charms and defeating bosses.

---

### ⚔️ 2. **Milestone Tiers / Structured Milestone Levels**

Instead of XP numbers, you could design **progression tiers** like:

* Tier 1 → Complete 3 key exploration tasks or defeat your first boss.
* Tier 2 → Find a rare artifact or reach a new region.
* Each tier grants one “level-up” or ability unlock.

✅ **Pros:** Keeps progression goal-oriented and content-driven.
❌ **Cons:** Risk of making players feel “stuck” if they miss content.

💡 *Mitigation:* Make sure milestones exist in multiple gameplay styles — e.g. combat, exploration, crafting, social — so every player type can progress naturally.

---

### 🗺️ 3. **Exploration Currency or Token System**

Each milestone (boss, hidden chest, story event) gives a *“soul token”* or *“memory shard”* that acts as your stat currency.
This makes leveling feel more diegetic — your character *grows* through discovery and triumphs.

✅ **Pros:** Keeps the reward tangible and lore-friendly.
❌ **Cons:** Must ensure steady pacing; otherwise players might feel “starved” for upgrades.

**Example:**

* *Zelda: Breath of the Wild* → Spirit Orbs from shrines = heart or stamina upgrades.
* *Dark Souls* → Boss souls as special progression tokens.

---

### ⚙️ 4. **Combat-Driven Milestones**

If you’re worried combat might feel unimportant, tie **some milestones to combat feats**, like:

* “Defeat X enemies without healing.”
* “Win 10 battles using a specific strategy or weapon type.”
* “Defeat an elite enemy variant.”

✅ **Pros:** Keeps combat meaningful and skill-based.
❌ **Cons:** Needs careful tuning to avoid grindy or repetitive goals.

---

### 🎯 5. **Narrative or Thematic Progression**

If your game is story-heavy, tie stat growth to *story impact*:

* Gaining a new ability after a key plot revelation.
* Character growth represented mechanically (e.g., “Overcame fear” → unlocks resistance).

✅ **Pros:** Deeply immersive; connects story and mechanics.
❌ **Cons:** Less flexible for open-world or sandbox play.

---

### ⚖️ 6. **Balance Tip — Keep Feedback Loops Strong**

One big reason XP feels satisfying is **frequent feedback**.
If milestones replace XP, ensure:

* Players still get *frequent signals of progress* (notifications, sounds, animations, visual upgrades).
* Even small milestones feel rewarding (minor stat boost, new passive, lore snippet).

---

### 🧭 7. **Games to Study**

* **Hollow Knight** – Progress tied to exploration and items, not XP.
* **Zelda: Breath of the Wild** – Spirit Orbs = milestone rewards.
* **Dark Souls** – Hybrid: souls (XP/currency) + major boss souls = milestones.
* **Outer Wilds** – Pure knowledge-based progression (no stats, but growth through discovery).
* **Metroidvania genre in general** – Gating via ability unlocks rather than XP.

---

### 🔍 In Summary

A *pure milestone system* can absolutely work — it just needs:

* **Consistent, visible progression feedback**
* **Diverse milestone types** (combat, exploration, puzzle)
* **Good pacing** so players never go too long without feeling stronger

If done right, it can make your world feel more *authentic* and *player-driven* than an XP grind ever could.

---

Would you like me to sketch out a **sample milestone progression structure** (like a mock leveling curve or milestone table) to visualize how it might feel in gameplay pacing?


### Gemini Response
This is a fantastic line of thinking, and the short answer is: **Yes, a milestone-based system can absolutely work and is often incredibly effective.**

Many popular and critically acclaimed games use this exact philosophy, either fully or as a hybrid system. Your instincts about the pros (encouraging exploration, rewarding diverse engagement) are spot on.

Your cons are also valid, but they are *solvable design challenges*, not fundamental flaws. Let's break down how to solve them.

### The Core Solution: A "Dual-Channel" Progression System

The best way to solve your "cons" is to not put *all* progression into one basket. You're worried combat will feel pointless, and progression will be too "lumpy" (long plateaus, then a sudden jump).

Separate your progression into two distinct "channels":

1.  **Milestone Channel (Core Character Power):** This is exactly what you described. Players gain **Stat Points** (or "Ability Points," "Essence," whatever you call them) for major achievements:
    * Defeating a main quest boss.
    * Solving a major environmental puzzle.
    * Discovering a major hidden area.
    * Completing a significant side-quest line.
    * Finding a rare, hidden "Tome of Power" or equivalent.

2.  **Combat Channel (Gear & Resources):** This is how you make regular combat *essential* and provide that "steady" feeling of progression. Regular enemies don't drop XP; they drop:
    * **Currency:** Used to buy new equipment, consumables, and hints.
    * **Crafting Materials:** Used to *upgrade* weapons and armor.
    * **Rare Gear Drops:** The classic RPG loop.
    * **Consumables:** Potions, buff items, etc., that make tackling the *next* milestone possible.

### How This Solves Your "Cons"

#### 1. Con: "Combat would be less important."

**Solution:** In this dual system, combat is *critically* important, but for a different reason.

* Players can't just run past every enemy, because they'll be broke, have weak gear, and no potions.
* They'll *want* to fight enemies to get the materials to upgrade their "Iron Sword" to an "Iron Sword +1".
* This makes combat a **resource-gathering loop** that directly supports the **milestone-achieving loop**.
* You *need* to fight to get strong enough gear to *survive* the journey to the next boss or puzzle that grants you a Stat Point.

You mentioned gear can also increase stats and unlock abilities. This fits *perfectly*.
* **Milestones** give you base Stat Points (e.g., permanent Strength).
* **Combat** gives you the gear that *adds* Stat Points (e.g., "Gauntlets of Strength +2").

A player now has two clear goals: "I need to find the next milestone to get a new ability point" AND "I need to farm those golems to get the 'Ancient Gears' to upgrade my chest piece."

#### 2. Con: "Progression is less linear and less satisfying."

**Solution:** You're trading the "slow, steady drip" of an XP bar for the "exciting, punctuated burst" of a major achievement. This can be *more* satisfying if handled correctly.

* **Make Milestones Clear:** The player needs to know (or be ableto find out) *how* to get stronger. A quest log ("Defeat the Goblin King"), a map with points of interest, or clear environmental storytelling (a glowing statue in a hidden grove) all work.
* **Powerful Feedback:** When a player gets a Stat Point from a milestone, make it *feel* good. A bright visual effect, a satisfying sound, a clear "STAT POINT GAINED" UI popup. This is the "level-up" *ping* you're looking for, just tied to an achievement instead of a bar.
* **The "Linear" Problem is a "Pro":** A *less* linear progression is a *huge* selling point. It means player agency. If a player is stuck on a hard boss, they can leave and pursue other milestones instead: explore to find hidden treasures, solve puzzles, or do a side quest. They are *still progressing* and getting stronger, just on a different path. This is a hallmark of great design (think *Elden Ring* or *Zelda: Breath of the Wild*).

### Games to Study That Do This

You're in good company. Look at how these games handle progression—most use a system very close to what you're describing.

* **The Legend of Zelda (series):** The *classic* example. Your "level" is your number of **Heart Containers** (from bosses) and **Pieces of Heart** (from exploration, puzzles). Your "abilities" are the **Items** you find (Hookshot, Bombs). Combat gives you Rupees (currency) and consumables. It works perfectly.
* **FromSoftware Games (Dark Souls, Elden Ring):** This is a brilliant hybrid.
    * **Milestone Channel:** Finding **Estus Flask Shards** (more healing), **Golden Seeds** (more healing *charges*), and **Boss Souls** (Remembrances) are all milestone-based. These are arguably the *most* important upgrades.
    * **Combat Channel:** Regular enemies drop **Souls/Runes**, which act as *both* currency and XP. This keeps combat rewarding, but the biggest power spikes come from exploring and winning key fights.
* **Metroidvanias (Hollow Knight, Symphony of the Night):** Progression is almost *entirely* milestone-based. You find **Mask Shards** (health) and **Soul Vessels** (magic) by exploring and defeating mini-bosses. Your *real* progression is finding new **Abilities** (Double Jump, Dash) that unlock more of the map. Combat provides currency (Geo).
* **Guild Wars 2 (MMO):** While it has a traditional XP level, its *endgame* and *build-crafting* progression is heavily tied to **Hero Points**. You get these points by... you guessed it... completing milestones (called "Hero Challenges") scattered all over the world map. This directly encourages exploration.

### Summary: Your Idea is Strong

Stick with your milestone idea. It's a proven and compelling design. The key is to **not abandon combat rewards**, but to **change what combat rewards you**.

* **Use Milestones for:** Permanent Stat Points (Vertical Progression).
* **Use Combat for:** Currency, Crafting, and Gear (Horizontal Progression).

This creates a fantastic loop where both systems feed into each other, rewarding *all* types of engagement, just as you wanted. Good luck!

### DeepSeek Response
Of course! This is a fantastic design question that gets to the heart of what motivates players in an RPG. Moving away from a traditional XP system is a bold and potentially very rewarding choice.

A purely milestone-based system can absolutely work, but it requires careful design to address the potential downsides you've identified. The key is to not just *remove* XP, but to *replace* its psychological functions with other satisfying mechanics.

Here are several ways to approach this, from pure milestone to hybrid models.

### 1. The "Pure" Milestone System (And How to Refine It)

Your initial idea is solid. Instead of "XP per enemy," you grant "Level-Up Points" for completing significant objectives. To make this feel satisfying and address your concerns:

*   **Tier the Milestones:** Not all milestones are created equal. This creates a sense of progression and excitement.
    *   **Minor Milestones (Skill Points):** Finding a hidden treasure cache, solving an optional environmental puzzle, completing a minor side quest. These could grant a partial point or a point that can only be spent on non-combat skills (e.g., lockpicking, persuasion).
    *   **Major Milestones (Level-Up Points):** Defeating a boss, completing a major story quest, discovering a legendary location. These grant a full point to spend on any stat or a new ability.
*   **Make the Reward Ceremony Meaningful:** The moment of gaining a point should feel important. Don't just have a number tick up. Have a visual flourish, a unique sound effect, and force the player to a "Level Up" screen where they make their choice. This ritual replaces the satisfaction of watching an XP bar fill.
*   **Communicate Progression Clearly:** Use a Quest Log or "Deed Journal" that explicitly states: "For completing this task, you will earn a Level-Up Point." This sets clear goals and manages player expectations. They are always working towards a known, tangible reward.

**Games that do this well:** *The Legend of Zelda: Breath of the Wild/Tears of the Kingdom* (Spirit Orbs from Shrines), *Tunic* (raising your stats by finding specific items).

### 2. Hybrid Systems: The Best of Both Worlds?

This is often the most effective way to go, as it can preserve the "grindable" satisfaction of XP while maintaining the goal-oriented nature of milestones.

*   **XP for Skills, Milestones for Stats:** You gain traditional XP from combat, but it's only used to improve your combat skills or spell levels. Your core stats (Strength, Dexterity, etc.) are increased by finding "Ancient Tomes" or "Training Manuals" hidden in dungeons or granted by masters as quest rewards. This directly addresses your "equipment that increases a stat" idea and makes it core to progression.
*   **Challenge-Based XP:** Instead of XP for killing, you get large chunks of XP for completing specific *combat challenges*. For example:
    *   "Slay the Cave Troll" = 100 XP
    *   "Defeat 10 enemies using only fire magic" = 50 XP
    *   "Perfect Dodge a boss's special attack 3 times" = 75 XP
    This turns the XP system into a system that encourages engaging with the combat mechanics in a deeper way, rather than just grinding. It's a milestone system *for combat*.

**Games that do this well:** *Final Fantasy XIII* (Crystarium progression is gated by story bosses), many MMOs (daily/weekly quests).

### 3. Addressing Your Specific Concerns

> **"It feels like removing XP makes progression less linear and potentially less satisfying."**

This is a valid fear. The satisfaction of an XP bar is the "compulsion loop": Action -> Small Reward -> Progress to Big Reward. To replicate this:
*   **Give players a "Progress Bar" to fill.** This could be a "Deed Journal" with checkboxes. "Find 5 hidden shrines to earn a point." Now, finding each shrine is the "small reward," and the point is the "big reward."
*   **Use "Insight" or "Training" as a secondary currency.** Maybe combat doesn't give XP, but it gives "Insight" or "Combat Experience" that makes your next *purchased* ability 10% cheaper. This keeps combat feeling directly tied to power progression without it being the sole source.

> **"It also makes me think that combat would be less important..."**

This is a design choice, not necessarily a flaw. If you want combat to remain paramount, you need to incentivize it within the milestone system.
*   **Make Combat a Primary Source of Milestones:** Many of your major milestones *must* be combat-focused. "Defeat the Lich King" is a milestone. "Clear the Bandit Fortress" is a milestone.
*   **Tie Abilities Directly to Combat Feats:** This is a powerful method. You don't just get a point to spend on "Whirlwind." Instead, the ability "Whirlwind" is unlocked by the milestone: "Defeat 5 enemies in a single blow." This makes combat the direct catalyst for new powers.
*   **Reward Combat Exploration:** "Discover the secret technique by defeating the optional boss in the ancient arena." The combat *is* the exploration.

### Actionable Recommendations

1.  **Define Your Game's Pillars:** What is most important? Story, Exploration, or Combat?
    *   **Exploration-Focused:** Use a pure milestone system tied to discovering locations and secrets.
    *   **Combat-Focused:** Use a hybrid system where major stats come from milestones (bosses) but combat skills/abilities are upgraded with combat-earned currency or feats.
    *   **Story-Focused:** Use a strict story-based milestone. "After completing Chapter 3, all characters gain a level."

2.  **Prototype the "Feel":** Build a small test area with two versions:
    *   Version A: Player gains a level after killing 10 wolves (XP).
    *   Version B: Player gains a level after finding the "Wolf Hunter's Totem" at the end of the wolf den (Milestone).
    See which one *feels* better for your game. Does B make the player more engaged with the environment? Does A make them feel more powerful from the act of fighting itself?

3.  **Study These Games:**
    *   **God of War (2018):** A masterful hybrid. You get XP from combat to upgrade abilities, but major stat increases come exclusively from upgrading your equipment, which requires resources found by exploring and defeating specific, high-value targets.
    *   **Final Fantasy X:** The Sphere Grid is a form of milestone leveling. You only progress by using "Spheres" dropped by specific enemies or found in chests. You're not grinding for abstract XP, you're grinding for a specific *key item* that allows progression.

**Conclusion:**

A purely milestone-based system **can absolutely work** and can make your game stand out by encouraging diverse play. The potential pitfalls you identified are real, but they are not deal-breakers—they are design challenges. By thoughtfully replacing the psychological rewards of an XP system with clear goals, meaningful reward ceremonies, and a tight integration between player actions and progression, you can create a deeply satisfying and unique RPG experience.
