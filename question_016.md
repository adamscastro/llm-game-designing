## Question 016

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1ksv8cc/how_do_you_make_turn_based_rpgs_hard

Date: 2025-05-22

## Problem Description
How do you make turn based RPGs hard? — (NOTE: Not a game dev, just had a question I've been thinking about for a while)

Aside from enemies hitting harder and having more health, how can you add difficulty to turn based RPGs in a way that encourages players to engage with the system maximally?

My idea was making enemies smarter instead of just stronger. For example, enemies using support/sabotage skills more: healing, buffs, de-buffs, status ailments, etc. Maybe have certain enemies target certain party members specifically (members that can heal, for example). And have them adjust to the player's behavior (to the degree that's possible, anyway).

These seem like good ways to increase the difficulty of turn based RPGs without it feeling cheap, but again, I'm not a dev. What do you guys think? What would you do?

## Best Human-rated Answer
On the player's turn, there's a pool of possible actions they could choose from. These should be all somewhat useful, instead of having one or a few actions clearly better than the rest.

For instance, I get that using a water attack on a fire-type enemy should be the all-around better choice, but what if an electric attack, on a particular scenario, could be used to trigger a rainstorm that damages and weakens all fire-type enemies on the field? Maybe there are other not-so-on-the-nose solutions to the same problem.

That's not even the best example as it implies situational advantage (hey, also a cool feature!), but ideally every action should be viable on it's own way. Within this kind of framework, using a good action carries the cost of not using other differently good actions.

## LLM Responses

### ChatGPT-5 Response
That’s a great design question — and one a lot of developers wrestle with! Making a turn-based RPG “hard” without just inflating numbers is really about *depth* rather than *brute force*. You want players to feel challenged because they’re making interesting decisions, not because the enemies are statistical walls.

Here are several ways a developer can achieve that:

---

### ⚙️ 1. **Smarter Enemy AI (as you suggested)**

You’re absolutely right — smarter enemies are more engaging than tougher ones. Some concrete AI strategies:

* **Target Priority Logic:** Enemies prioritize healers, buffers, or low-HP characters.
* **Synergy Awareness:** Enemies use combos — e.g., one casts *Oil*, another uses *Fire*.
* **Adaptation:** After a few turns, enemies recognize player patterns (e.g., “player always buffs on turn 1”) and counter them.
* **Conditional Reactions:** Certain enemies might enrage when their ally dies, switch tactics when under 30% HP, or retreat to heal.

This creates the sense of fighting *thinking* opponents rather than static damage dealers.

---

### 🧩 2. **Resource Management Pressure**

Instead of battles being individually hard, make **the sequence** of battles matter:

* **Limited Healing Between Battles:** Encourage players to ration items and MP.
* **Endurance Dungeons:** Make it so players must manage resources across multiple encounters without easy resets.
* **Alternative Costs:** Maybe using powerful skills consumes a resource that’s rare or affects future encounters.

This rewards planning and long-term thinking.

---

### 🧠 3. **Layered Systems That Reward Mastery**

Add mechanics that reward deeper understanding:

* **Status Synergy:** Certain buffs/debuffs interact in interesting ways (e.g., “Freeze + Smash” = shatter damage).
* **Positioning/Turn Order:** Let players and enemies manipulate initiative or formation.
* **Conditional Skills:** Moves that gain extra effects when used under certain circumstances (e.g., “Attack deals double damage if enemy is debuffed”).

When systems interlock, skilled players can extract more power — making mastery itself the “difficulty.”

---

### 🎯 4. **Asymmetric Information**

Players might not always know everything:

* Hidden enemy skills or phases (learnable through experience or observation).
* Enemies disguising their roles until they act.
* “Mystery” boss mechanics that require deduction, not just damage.

This keeps players guessing and engaged with experimentation.

---

### 🧨 5. **Scenario & Encounter Design**

Make each battle a small puzzle rather than a stat check:

* **Unique Win Conditions:** Defend an NPC, survive 5 turns, destroy a specific object, etc.
* **Enemy Composition Challenges:** Pair enemies that synergize dangerously (healer + buffer + heavy hitter).
* **Environmental Effects:** Weather, terrain, or hazards change tactics each time.

These keep combat fresh and strategic.

---

### 🎮 6. **Player Risk–Reward Choices**

Make the player *choose* difficulty dynamically:

* **Optional Challenges:** Risk taking on tougher enemies or objectives for better rewards.
* **Combo Systems:** Powerful but risky moves — e.g., sacrifice HP for big damage.
* **Morale/Focus Systems:** If you overextend or make mistakes, your characters might suffer penalties.

This kind of “voluntary” difficulty feels fair and personal.

---

### 🧱 7. **Deceptive Simplicity**

The hardest RPGs often feel easy at first but hide punishing systems:

* *Example:* In *Shin Megami Tensei* or *Darkest Dungeon*, one mistake in preparation snowballs into disaster.
* If players don’t learn the rules or synergy, they’re punished later — but *it’s their fault*, not bad balance.

---

### 💡 Summary

| Goal                     | Design Approach                                |
| ------------------------ | ---------------------------------------------- |
| Reward strategy          | Smart AI, synergy mechanics                    |
| Encourage planning       | Resource pressure, long-term consequences      |
| Make choices matter      | Trade-offs, risk–reward systems                |
| Avoid “cheap” difficulty | Fair telegraphing, counterplay opportunities   |
| Keep it fun              | Variety, expression, multiple valid playstyles |

---

Would you like me to give examples of **specific games that do each of these well** (e.g., *Persona 5 Royal*, *Into the Breach*, *Divinity: Original Sin 2*)? It can help illustrate how these design ideas feel in action.

### Gemini Response
Hello! That's a fantastic question, and honestly, it gets to the very heart of what makes a turn-based RPG compelling.

You are 100% correct. Your ideas are not only good, they are the *exact* methods used by developers to create deep, challenging, and fair-feeling RPGs. What you're describing is the shift from a **stat-check** (do my numbers beat your numbers?) to a **system-check** (is my *strategy* better than your *strategy*?).

When players complain about "cheap" difficulty, they're usually talking about stat-checks. A boss that just has 500 million HP and one-shots your party isn't a fun challenge; it's a "go grind for 5 hours and come back" sign.

Here’s a breakdown of your ideas and other common developer strategies, all aimed at forcing the player to engage with the systems.

### 1. Smarter AI & Enemy Synergy (Your Idea)

This is the big one. Instead of 4-6 enemies all just picking "Attack" on a random player, you make them work as a team. This turns the fight from a simple damage race into a puzzle.

* **Role-Based Enemies:** You hit this perfectly.
    * **The Tank:** Has high defense and a "Taunt" ability. All player single-target attacks *must* target the Tank. This protects the other, more dangerous enemies.
    * **The Healer/Support:** Stays in the back, healing allies, or (even worse) applying buffs like "Attack Up" or "Evasion Up" to the main damage dealer.
    * **The Saboteur:** Focuses on debuffing the player's party. Think "Defense Down," "Silence" (disabling your mage), or "Blind" (disabling your physical attackers).
    * **The "Nuker" / Damage Dealer:** This enemy is fragile but hits *very* hard.
* **Target Prioritization:** Your idea of targeting the healer is a classic. Good AI will identify the player's biggest threat or most valuable asset.
    * **Focus Fire:** All enemies attack the *same* party member to overwhelm the player's healing.
    * **Exploit Weakness:** If a player character is vulnerable to Fire, the AI *knows* this and will prioritize using Fire attacks on them.
    * **Punish Buffs:** Does the player's Knight just use "Attack Up"? The enemy Saboteur immediately hits them with "Dispel" to remove it, wasting the player's turn.

### 2. Status Effects & Debuffs That *Matter*

In many RPGs, "Poison" is just a tiny chip damage, and "Sleep" wears off in one turn. To make systems engaging, status effects need to be *genuinely threatening*.

* **"Hard" Control:** Effects that make the player lose a turn are the most powerful. **Paralysis**, **Stun**, **Freeze**, **Petrify**. If the enemy can stun-lock your healer, you're in a death spiral. This forces the player to equip "Stun Resist" items or have abilities that *cleanse* debuffs.
* **"Soft" Control:** These don't stop the player, but they severely hamper them. **Silence** on a mage, **Blind** on a rogue, **Defense Down** on a tank.
* **Resource Drain:** Enemies that burn the player's MP/SP. This creates a war of attrition. You *can* win, but can you win with enough MP left to face the *next* fight?
* **Unique Debuffs:** Think of *Darkest Dungeon*. The "Mark" system has enemies "mark" a hero, and other enemies have attacks that do 3x damage to marked targets. This is *synergy* (Point #1) combined with a scary debuff.

### 3. "Soft" and "Hard" Timers (Creating Urgency)

This prevents the player from just playing super-defensively forever, "turtling" until they win.

* **The "Charging" Attack (Soft Timer):** An enemy "Gathers Energy" or "Begins Casting." The player has 1-2 turns to either **Stun** the enemy, **Silence** them, or deal enough damage to "Break" their stance. If they fail, the enemy unleashes a devastating party-wide attack. This forces offensive action.
* **The Reinforcements (Soft Timer):** The boss summons minions. If the player ignores them, the minions will either heal the boss or swarm the party. This creates a "target priority" puzzle: kill the adds or burn the boss?
* **The "Enrage" (Hard Timer):** A classic in *World of Warcraft* and many RPGs. After a certain number of turns (e.g., 20 turns), the boss "Enrages," dealing 500% more damage and wiping the party. This makes the fight a "damage-per-second" check and prevents 30-minute stalemates.

### 4. Break & Stagger Systems

This is a very popular modern solution. Think *Octopath Traveler*, *Final Fantasy VII: Remake*, or *Persona 5*'s "Hold Up" system.

* **The Mechanic:** Enemies have a "Shield" or "Stagger" gauge, often with 2-8 points. To break the shield, the player *must* hit the enemy with its weaknesses (e.g., "Sword," "Fire," "Ice").
* **Why it Works:** It forces the player to engage with the "weakness" system maximally. You can't just spam your strongest attack. You *must* bring a diverse party that can cover multiple weaknesses. Once "Broken," the enemy is stunned and takes massive extra damage. This creates a fantastic rhythm of:
    1.  **Solve Puzzle:** Figure out weaknesses and break the shield.
    2.  **Reward:** Unleash all your biggest attacks during the "Break" window.

### 5. Resource Management & Attrition

Difficulty isn't just about a single fight; it's about the *entire dungeon*.

* **Scarce Resources:** Make MP and healing items rare or expensive. If the player uses all their MP on a "normal" enemy fight, they'll have nothing left for the boss. This makes *every* encounter a meaningful choice. Do I use my big "Fireball" spell now, or do I save the MP and just use my (weaker) auto-attack?
* **The "Per-Battle" vs. "Per-Dungeon" Problem:** In many modern games (like *Persona 5*), your SP/MP auto-refills after every fight. This means you can go all-out every time. In "hardcore" games (like *Shin Megami Tensei III: Nocturne* or *Etrian Odyssey*), your MP pool is for the *whole dungeon*. This makes resource management critical and every single turn count.

### 6. Information & Uncertainty

How much do you tell the player?

* **The "Scan" Mechanic:** In an easier game, you see enemy HP and weaknesses by default. In a harder game, the player must *waste a turn* using a "Scan" or "Libra" ability to learn that information.
* **Trial & Error:** The hardest games (like *Shin Megami Tensei*) tell you *nothing*. You have to *guess* what an enemy is weak to. If you guess wrong and use "Fire" on an enemy that *absorbs* Fire, you just healed the boss and wasted your turn. This forces players to learn, adapt, and remember.

**Conclusion:**

You are absolutely on the right track. The best-designed "hard" RPGs don't just buff enemy stats; they create **puzzles**. They force the player to stop mashing "Attack" and ask questions:

* "Who do I attack first? The healer or the guy buffing him?"
* "Can I break that enemy's 'Charge' attack in time?"
* "Should I use my big spell now, or save the MP for the boss?"
* "What's this enemy's weakness? I need to use 'Scan' or I'm fighting blind."

When you make the player answer those kinds of questions, you've created difficult, engaging, and (most importantly) *fair* encounters.

### DeepSeek Response
Excellent question! You've hit the nail on the head. The core of engaging turn-based RPG difficulty isn't about bigger numbers; it's about forcing the player to make more interesting and consequential decisions. Your ideas are not just good, they are the foundation of modern, well-designed tactical RPGs.

Your approach of making enemies "smarter instead of stronger" is precisely the right direction. Let's expand on your ideas and add a few more layers that developers use.

### 1. Enemy AI & Tactics (Expanding on Your Ideas)

This is your core concept, and it's incredibly powerful.

*   **Roles and Synergy:** Design enemy groups like a balanced player party.
    *   **Tanks:** Enemies with high threat/taunt abilities that force you to target them, while their backline allies attack freely.
    *   **Healers/Buffers:** As you said, these become primary targets. The difficulty comes from the **race** to take them out before they undo your progress.
    *   **Controllers:** Enemies that specialize in disabling your key party members with sleep, paralysis, or silence. This breaks your expected "rotation" and forces improvisation.
    *   **Glass Cannons:** Enemies that do massive damage but are fragile. The challenge is getting to them through their frontline.

*   **Adaptive Behavior:** This is the pinnacle of "smart" AI.
    *   If the player spams a powerful AoE spell, enemies might spread out.
    *   If the player relies on a single buffed character, enemies might use "Dispel" or focus that character with armor-breaking debuffs.
    *   After a certain HP threshold, an enemy might change its pattern, becoming more aggressive or defensive.

*   **Priority Targeting:** As you mentioned, having enemies target healers or mages is great. You can make this more nuanced:
    *   Target the character with the lowest HP.
    *   Target the character with the most beneficial buffs.
    *   Target the character who acted last (exploiting a slow character).

### 2. Mechanics That Force Engagement

These are systems that make "just attacking" a losing strategy.

*   **The "Puzzle Boss":** Create enemies with specific mechanics that must be solved.
    *   **Damage Sponges with a Twist:** A boss that is immune to all damage unless a certain condition is met (e.g., a specific element, a status effect, or after destroying a "power crystal").
    *   **Counters:** Enemies that counter-attack specific action types (e.g., countering all physical attacks, or countering all magic with a silence spell). This forces the player to use a diverse set of skills.
    *   **Interrupting Attacks:** Enemies that have a "charging" or "preparing" phase for a devastating attack. The player must use a specific skill (e.g., a "Stop" spell, a stun attack, or break a part of the enemy) to interrupt it. Failure is punished severely.

*   **Resource Management & Pressure:**
    *   **Attrition:** Design dungeons or sequences with multiple tough battles before a boss, forcing the player to conserve MP/TP and items. This makes every spell cast a meaningful choice.
    *   **Timers/Enrages:** A boss that enrages after a certain number of turns, becoming exponentially more powerful. This prevents overly defensive, "turtle" strategies and encourages efficient, aggressive play.

*   **Environmental Interaction:**
    *   The battlefield itself can be a factor. There could be hazards to avoid, cover to use for defense, or interactive objects that can be used to gain an advantage.
    *   **Positioning:** Introduce a grid or positional system (like in *Final Fantasy Tactics* or *Divinity: Original Sin*). This makes AoE spells, line-of-sight, and protecting backline members a core part of the strategy.

### 3. Player-Centric Limitations

Increase difficulty by strategically limiting the player's options, forcing creativity.

*   **Conditional Battles:** Impose special rules on a fight.
    *   "Win without using magic."
    *   "Win without any party member falling below 50% HP."
    *   "Defeat the enemy using only fire attacks."
    *   These are excellent for optional, high-difficulty content.

*   **Forced Party Composition:** Don't let the player always use their four strongest characters. Force them to use specific, perhaps under-leveled, story characters for certain segments, challenging their ability to build a synergistic team on the fly.

### 4. Synergistic Systems (The True Key to Mastery)

This is the ultimate goal: creating a system where the *interaction* between mechanics is where the depth lies.

*   **Elemental Affinities & Break Systems:** Like in *Persona 5* or *Octopath Traveler*, hitting an enemy's weakness doesn't just do extra damage; it grants an extra turn, interrupts their action, or breaks their guard. This turns combat into a chain-reaction puzzle.
*   **Buff/Debuff Stacking and Dependency:** Make buffs and debuffs essential, not optional. For example, a boss might have such high defense that you *must* apply an "Armor Break" debuff to do meaningful damage. Or, you might *need* a "Haste" buff to get enough actions in to survive.
*   **Combo Systems:** Encourage using skills in a specific order for a bonus. For example, "Using 'Soak' on an enemy followed by a lightning spell does 300% damage." This rewards planning and setup over simple, powerful attacks.

---

### Summary: What Makes it Feel "Fair" vs. "Cheap"?

You rightly want to avoid a "cheap" feeling. The difference almost always comes down to:

*   **Fair:** The player loses because they failed to understand or engage with the mechanics. The solution is to learn, adapt, and try a new strategy.
*   **Cheap:** The player loses to an unavoidable, unpredictable one-hit KO or a string of perfect RNG from the enemy.

Your proposed solutions are firmly in the "fair" category. They present a clear problem (a smart enemy tactic) that has a clear, learnable solution within the game's systems. The player feels smart when they figure it out, not cheated.

You're thinking like a pro game designer already. Keep it up
