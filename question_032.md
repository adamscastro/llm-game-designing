## Question 032

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1inn37l/mmo_game_design_how_to_encourage_exploration

Date: 2025-02-12

## Problem Description
MMO Game Design: How to encourage exploration — This is more of a theoretical exploration and I'm looking for some input from experts. How do you encourage players to actually explore your worlds and not simply farm monsters for EXP?

Do you go the Fallout method of having exploration and quests actually give EXP or do you go the Bethesda method of having skill increases be tied to actually using skills instead of killing monsters?

Bonus question: is there ever a good reason to include a 'diminishing returns' system for EXP gains (i.e. slain enemies start to give less EXP around a certain level)?

## Best Human-rated Answer
Having worked on an MMO and an open world game, I have used the following things to help encourage exploration:

Use the main quest/golden path
A lot of players are going to be following your main quest line, so make sure it takes you on a grand tour of the world. Avoid making the golden path back track following the same routes, and as you are placing the rest of the content in your world, try to put as much of it as you can so it can be discovered just off the golden path. Side quest content can also be done to do this as well. For instance, the main quest may take you to this tavern where you need to pick up your McGuffin, and while there, a side quest character catches your eye, and sends you off to make a deal with the Thingamajig vendor located somewhere off the golden path. On the way to the vendor you may see an shiny objective off in the distance...

Basically, every path that you send the player on can open up new opportunities to explore, should the player choose to do so. Draw maps of the expected player paths for both your golden path and silver paths (aka side quest paths), and aim to have as much area covered as possible and look to make crossing lines cross more perpendicularly than have them traversing in parallel.

Epic Landmarks
Every level and world designer should know about the concept of Weenies. Epic landmarks will work as weenies to not just orient yourself in the world, but also draw players towards it to see what that landmark is about. You can reward this behavior by making sure you have something at these locations that's interesting to engage in, maybe a side quest, maybe an open world activity, maybe some rare loot. You may also find that there are some paths towards this epic landmark that are more traveled than others. This is an opportunity to put more distractions along this path.

Environmental Story Telling that Catches the Eye
Not all narratives need to be spoon fed to the player. Having clues as in the form of out of place things in the world will capture the player's curiosity, and invite them to explore further. Maybe there's a suit of armor that's been skewered to the top of an entrance to a cave. Or the player sees a crows nest from a ship sticking atop the canopy of a forest. A player might hear a sick beat being played on some drums out in the middle of nowhere.

Provide Rewards for the Curious
One thing I loved about Zelda Breath of the Wild were the Korok seeds. BotW scattered the world with simple little activities that were just inherently satisfying to both find and complete. My understanding is that they had their QC team explore the world and if they ever found a place they found interesting either because of the view, or it was challenging to reach, and they dropped a flag there that the designers could see. Those locations became candidates for Korok seed placements.

Another way to look at this is to make sure you do your best to never have dead ends that don't have some sort of reward for the player. The rewards don't need to be huge. Just something to make the player feel seen by the designer indicating to the player that the designer thought you might go here. Just by having features like this in the world will encourage more exploration as players are incentivized to see what else is out in the world.

I'd love to hear other people's tips too!

## LLM Responses

### ChatGPT-5 Response
That’s a great and very common design question in MMO development — how to get players to explore instead of grinding the same mobs or dungeons for efficiency. Here are several **design approaches and incentives** that can encourage exploration, along with some discussion of **experience systems** and **diminishing returns**.

---

### 🌍 1. Reward Exploration Directly

If you want exploration to feel rewarding, **make exploration itself yield tangible benefits**.

**Ideas:**

* **Exploration XP:** Give experience (or other progression rewards) for discovering new areas, landmarks, or hidden locations — similar to *Guild Wars 2* or *Fallout*.
* **Lore and Achievements:** Unlock lore entries, titles, or achievements for visiting rare or scenic places. These create a sense of prestige and completion.
* **Resource and Loot Incentives:** Scatter unique resources, collectibles, or treasure chests across the world. This makes exploration a practical activity, not just aesthetic.
* **Dynamic Events:** Place dynamic world events or mini-bosses that only appear in certain regions and times, encouraging players to roam.

---

### 🧭 2. Design the World for Curiosity

The **level design** itself can promote exploration if it invites curiosity and discovery.

**Ideas:**

* **Visual Landmarks:** Use distinctive structures, colors, or shapes to attract players’ attention.
* **Subtle Guidance:** Environmental storytelling — trails, lights, or sounds — can subconsciously lead players toward hidden points of interest.
* **Nonlinear Paths:** Avoid strict quest hubs and corridors. Let players wander and find quests or secrets organically.
* **Meaningful Discovery:** Ensure discovered areas have lore or context that connects to the main story — it makes exploration emotionally rewarding.

---

### 🧩 3. Integrate Exploration into Core Progression

Instead of treating exploration as a side activity, make it part of the player’s advancement.

**Examples:**

* **Exploration Skill Trees:** Introduce a “Pathfinder” or “Explorer” progression line where finding new places boosts travel speed, gathering yield, or navigation tools.
* **Quests That Require Discovery:** Create questlines that depend on finding clues or hidden objects rather than killing targets.
* **World Knowledge Bonuses:** Visiting areas could increase reputation with local factions or unlock fast travel nodes, crafting bonuses, or merchants.

---

### ⚔️ 4. Alternative XP Systems

Both Fallout-style and Bethesda-style systems have merit — and can even be blended.

* **Fallout-style (EXP for everything):** Encourages diverse play — combat, dialogue, exploration all feed into leveling. Great for rewarding exploration directly.
* **Bethesda-style (skills through use):** Encourages emergent gameplay — players grow through action, not grinding. But without balance, exploration may feel secondary.

**Hybrid suggestion:**
Reward exploration with both *discovery XP* **and** *skill opportunities* — for instance, finding a hidden ruin gives discovery XP and lets you use your lockpicking or survival skills.

---

### 📉 5. Diminishing Returns (Bonus Question)

**Diminishing returns** can be a valuable *anti-grind* mechanism, but use it carefully.

**Pros:**

* Prevents “optimal farming” behavior.
* Encourages players to move to new zones or activities.
* Keeps the world feeling large and alive.

**Cons:**

* If too aggressive, it frustrates players who just want to play casually or master one area.
* It can feel like the game is punishing efficient play.

**Good implementations:**

* Soft caps: gradual XP reduction, not hard cutoffs.
* Contextual scaling: certain mobs stop yielding XP only when you outlevel their zone.
* Rotating bonuses: instead of penalizing grinding, *reward* exploring new content (e.g., “rested XP” or “discovery XP multiplier”).

---

### 💡 6. Encourage Social Exploration

MMOs thrive on social engagement — use that to motivate exploration.

**Examples:**

* **Exploration parties:** Group bonuses for discovering areas together.
* **Player-driven exploration:** Allow players to leave notes or markers for others (like *Elden Ring* messages or *No Man’s Sky* discoveries).
* **Server events:** Global progress toward unlocking new regions.

---

### ✅ Summary of Solutions

| Problem                      | Design Solution                                         |
| ---------------------------- | ------------------------------------------------------- |
| Players grind mobs for EXP   | Add discovery XP, achievements, and loot for exploring  |
| Exploration feels unrewarded | Link exploration to story, progression, or skill growth |
| World feels static           | Add dynamic events and environmental storytelling       |
| Players ignore new zones     | Use soft diminishing returns and exploration bonuses    |
| Exploration is lonely        | Add social mechanics or global events tied to discovery |

---

Would you like me to outline a **sample reward structure or progression system** (e.g., how much EXP or rewards to give per discovery tier) for an MMO that encourages exploration?


### Gemini Response
This is a classic and fundamental challenge in MMO design: balancing the "optimal path" (efficiency) with the "intended path" (exploration and world engagement).

You've already identified the core conflict: If killing monsters is the most efficient way to gain power (EXP), players—especially "min-max" players—will optimize the fun out of the game and stick to farming loops.

To solve this, you must make exploration **a competitive and rewarding progression path in its own right.**

Here are several methods, from direct to systemic, to encourage players to explore your world.

---

### 1. The Direct Incentive Model (The "Fallout/Guild Wars 2" Method)

This is the most direct way to "pay" the player for exploring. You tie the primary progression system (EXP) directly to the act of discovery.

* **Discovery EXP:** This is the *Guild Wars 2* model, and it's brilliant. Players receive a significant chunk of EXP for:
    * **Discovering a Point of Interest:** (e.g., a named location, a statue, a cave entrance).
    * **Unlocking a Waypoint/Fast Travel:** This is a double reward (convenience + EXP).
    * **Viewing a "Vista":** A simple cinematic that shows off a beautiful view, rewarding the player for reaching it.
    * **Map Completion:** Completing all objectives in a zone grants a large one-time bonus (EXP, currency, and rare items).

* **Exploration-Based Quests:** Move quests away from "Kill 10 Boars" and toward "Find the Source of the River" or "Solve the Riddle of the Stone Circle." The quest *is* the exploration. *Elden Ring* does this exceptionally well; most quests are just vague rumors that propel you to explore a new region.

* **The "Fog of War" Map:** The simple, psychological drive to "fill in the map" is incredibly powerful. Rewarding small amounts of EXP for revealing new map segments reinforces this.

**Why it works:** It directly competes with monster farming. A player can now calculate their "EXP per hour" and find that a 20-minute loop to discover 5 new locations is just as, or more, efficient than grinding mobs for 20 minutes.

### 2. The Systemic Model (The "Bethesda/Elder Scrolls" Method)

This is a deeper, more complex approach that changes the fundamentals of progression.

* **Skill-Based Progression:** As you noted, skills increase by *use*. This is difficult to balance in an MMO but has a powerful effect. If you have an "Athletics" or "Exploration" skill, it could level up by:
    * Running and jumping.
    * Discovering hidden locations.
    * Climbing to high places.
    * Leveling this skill could grant passive benefits (movement speed, jump height, reduced fall damage) or even active abilities (a short climb, a "detect hidden" pulse). This makes exploration *itself* a formof character progression.

* **Crafting & Gathering:** Place rare, valuable crafting resources *only* in hard-to-reach, out-of-the-way locations. This creates an economic incentive. Players aren't exploring for EXP; they're exploring for *wealth*. This also creates a new player role: the dedicated "Explorer/Gatherer" who sells their finds.

**Why it works:** It appeals to a different kind of player. The reward isn't just an EXP bar; it's tangible, permanent improvement or wealth. It makes exploration a core *gameplay system*, not just a side activity.

### 3. The Content & Curiosity Model (Intrinsic Rewards)

This is the most "pure" form of exploration. You reward the player not with EXP, but with *more game*.

* **Hidden "Breadcrumbs":** This is the soul of exploration.
    * **Lore:** Finding notes, journals, or audio logs that piece together a compelling mystery.
    * **Treasure Maps:** A monster drops a hand-drawn map with an "X" on it. There's no quest marker. The player must use the map's landmarks to find the treasure.
    * **Collection Systems:** Add a "Sightseeing Log" or "Explorer's Journal." Players get achievements, titles ("World Walker"), or unique cosmetics for finding 10 hidden waterfalls, 5 ancient ruins, etc.

* **Jumping Puzzles & Hidden Challenges:** *Guild Wars 2* and *Destiny 2* are masters of this. Create complex platforming sections hidden in the world that lead to a magnificent view and a "Hero's Chest." This chest shouldn't just contain a bit of currency; it should have a high chance for a unique cosmetic item or a powerful piece of gear.

* **Unique Encounters:** Hide unique things in the world.
    * **Hidden Bosses:** A powerful enemy that only spawns in a remote location under specific conditions.
    * **Secret Vendors:** An NPC hidden behind a waterfall who sells unique, rare items.
    * **Environmental Storytelling:** Finding a skeleton in a cage next to a poison vial and a love letter. It tells a story with no text, rewarding the player's observation.

* **Unlocking Access:** The reward for exploring a complex cave system isn't a chest; it's finding a new, permanent *shortcut* back to the main city or unlocking a new, hidden dungeon entrance.

---

### Answer to the Bonus Question: Is Diminishing Returns (DR) on EXP Good?

**Yes, absolutely.** A diminishing returns system for EXP is an essential pacing and design tool in an MMO for several key reasons:

1.  **It's a "Soft" Nudge:** It's the game's way of gently telling the player, "You've mastered this area. It's time to move on." It encourages them to progress to the next zone, experience new content, and follow the intended story/leveling path without putting up a "hard wall."

2.  **It Prevents "Over-Grinding" and Boredom:** Without DR, players might inefficiently grind in a starting zone for days, getting bored and quitting. Or, they might over-level and find the next 3 zones trivially easy, which ruins the challenge and experience.

3.  **It Combats the "Efficient Farm" Problem:** It directly disincentivizes the *exact* problem you're trying to solve. If a high-level player discovers a super-efficient farm in a low-level area (a "hyper-spawn"), DR ensures it's not the best way to level, pushing them to seek out level-appropriate challenges.

4.  **Economic & Anti-Botting:** It helps prevent high-level players or bots from endlessly farming low-level areas for resources or gold, which can destroy a new player's economy and experience.

**In short:** Diminishing returns are a way to protect the player's experience from their own "optimization" impulse. It's a key tool for guiding players through the vast amount of content you've created.

### Summary: The Holistic Solution

The best approach is a **layered system**. Don't rely on one method.

* **Base Layer:** Use the **Fallout/GW2 Method** (Discovery EXP) to make exploration a *viable* alternative to grinding.
* **Mid Layer:** Use the **Bethesda Method** (Skill/Gathering) to give exploration its own systemic depth and economic value.
* **Top Layer:** Use the **Content Model** (Lore, Puzzles, Secrets) to provide the *intrinsic* motivation—the "wow" moments that players remember and talk about.
* **Back-end:** Use **Diminishing Returns** on mob EXP to gently discourage "zombie-grinding" and nudge players toward your other, more engaging content.

### DeepSeek Response
Of course! This is a classic and excellent MMO design question. The core challenge is to make exploration feel more rewarding, or at least equally rewarding, than the predictable loop of monster farming.

Here’s a breakdown of potential solutions, addressing both your main and bonus questions.

### The Core Philosophy: Make Exploration Inherently Rewarding

The goal isn't to *force* players to explore, but to make them *want* to because the rewards are unique, compelling, and align with player goals. Monster farming is about predictable, incremental gains. Exploration should be about **discovery, surprise, and powerful horizontal progression**.

---

### How to Encourage Exploration: A Multi-Layered Approach

The most successful MMOs use a combination of these methods. Relying on just one is rarely enough.

#### 1. Tangible, Exclusive Rewards (The "What's In It For Me?")

This is the most direct motivator. If players know a hidden area contains something they can *only* get there, they will seek it out.

*   **Cosmetic & Prestige Items:** Unique transmog/wardrobe skins, mounts, pets, titles, and emotes that scream "I was here!" These have zero impact on game balance but immense social value.
    *   *Example: A rare phoenix mount that only spawns on a hidden peak in a volcanic zone.*
*   **Powerful, Unlockable Skills:** Instead of just finding a +5 Sword, players find a "Tome of the Frozen Wastes" that teaches a new, powerful ice spell. This is a permanent upgrade to their character's toolkit that can't be bought or farmed from mobs.
*   **Convenience & Base Building:** Unlock new teleportation points, secret vendors with rare reagents, or personal housing locations. In modern MMOs, things like "Sight of Grace" in *Elden Ring* or "Waypoints" in *Guild Wars 2* are brilliant examples.
*   **Lore-Driven Gear:** Weapons and armor tied to the history of the location. A sword found in a forgotten tomb isn't just statistically good; it has a name and a story, making it more memorable.

#### 2. Intrinsic Motivation & World Design (The "Feel" of Exploration)

This layer makes the act of exploring enjoyable in itself, not just a means to an end.

*   **Environmental Storytelling:** Don't just tell a story with quest text; show it. A skeleton of two lovers holding hands in a cave, a ruined village with signs of a desperate last stand, a hidden journal. This rewards curious players with narrative payoff.
*   **"Cool Shit" Design:** Design vistas, hidden caves, and ancient structures that are simply awe-inspiring to find. The reward is the "wow" moment and a great screenshot.
*   **Non-Combat Challenges:** Incorporate light puzzle-solving, jumping puzzles (*Guild Wars 2* is the master of this), or navigation challenges that break the combat grind.

#### 3. Systemic & Progression Incentives (The "How It Fits Into the Game")

This is where your question about EXP and skills comes in.

*   **The "Fallout" Method (Exploration Grants EXP):** This is highly effective. Simply give a hefty chunk of EXP for discovering new locations, uncovering hidden lore pages, or solving environmental puzzles. This directly validates exploration as a viable leveling path alongside questing and combat.
*   **The "Bethesda" Method (Skill-Based Progression):** This can be brilliant but is harder to implement in a traditional MMO. You can hybridize it:
    *   **Discovery Skills:** Have a "Scavenging" or "Lore Mastery" skill that only levels up by finding hidden objects and locations.
    *   **Contextual Skill Gains:** Jumping a lot could slightly increase a "Agility" stat. Discovering new flora could grant a point in "Alchemy." This makes every action in the world feel productive.
*   **The "Map Completion" Meta-Reward:** *Guild Wars 2* popularized this. Players are rewarded with significant EXP, loot, and currency for fully uncovering every part of a zone's map. This creates a clear, satisfying checklist for completionists.

#### 4. Content & Social Design

*   **Secret Bosses & Dynamic Events:** Hide world bosses or elite monsters that only spawn under specific conditions (e.g., during a full moon, after lighting three braziers). This creates community-driven hunting parties and shared discovery.
*   **Scouting & Information as a Role:** Create game mechanics where one player can discover a temporary resource-rich node or a hidden enemy camp and share its location with their guild for a collective benefit.

---

### Addressing Your Bonus Question: Diminishing Returns on EXP

**Yes, there can be a good reason for a diminishing returns system, but it must be implemented with extreme care and transparency to avoid feeling punitive.**

The primary goal of such a system is **to guide player behavior and maintain game health.**

**Good Reasons to Use It:**

1.  **To Combat Botting and Mindless Farming:** If a single type of enemy in a single spot is the most efficient EXP in the game, bots and players will camp there forever, ruining the spawn for others and inflating the economy. Diminishing returns after a certain kill count can push players to move elsewhere.
2.  **To Encourage Diverse Gameplay:** The system can be a "soft hand" guiding players to try other content. If EXP from grinding wolves drops off, maybe it's time to try that dungeon, PvP battleground, or exploration objective the game is offering.
3.  **For Zone-Level Appropriateness:** To prevent high-level players from farming low-level zones (which can ruin the experience for new players) by making the EXP/Loot gains negligible. This is a very common and generally accepted form of "diminishing returns."

**How to Implement It Without Angering Players:**

*   **Don't Call it "Diminishing Returns."** Frame it positively. Call it "Diverse Play Bonus" or "Adventurer's Spirit." The first 100 monsters you kill of a type each day give 100% EXP, but then you get a buff that increases EXP from *other* activities by 10%.
*   **Be Transparent:** The game should clearly communicate how the system works. A tooltip like "You are becoming too efficient at slaying Boars. EXP from Boars is reduced, but EXP from exploring the Whispering Woods is increased!" feels much better than a hidden, unexplained penalty.
*   **Target the Behavior, Not the Player:** The system should nudge players towards other valid forms of progression (exploration, dungeons, crafting), not simply punish them for playing.

### Conclusion and Recommended Approach

For your MMO design, I would suggest a **hybrid model**:

1.  **Adopt the "Fallout" method liberally.** Grant significant EXP for discovering points of interest, vistas, and hidden areas. This makes exploration a core, rewarded pillar of progression.
2.  **Supplement with "Bethesda-style" unlocks.** Tie unique skills, recipes, and cosmetic items to specific exploration achievements. This provides the horizontal progression that makes characters feel unique.
3.  **Use a transparent "Diversity Bonus" system instead of a punitive "Diminishing Returns" system.** Encourage players to mix exploration, questing, and dungeons by offering bonuses for engaging in different activities throughout their play session.

By making exploration a primary source of unique power, compelling stories, and prestigious rewards, you can successfully shift the player's mindset from "Where is the most efficient spawn to farm?" to "I wonder what's over that mountain range?"
