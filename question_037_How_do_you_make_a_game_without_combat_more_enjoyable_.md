## Question 037

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1m23354/how_do_you_make_a_game_without_combat_more

Date: 2025-07-17

## Problem Description
How do you make a game without combat more enjoyable? — Hi! I'm starting to design a "survival horror" game focused on exploration and narrative, but I would like to know how I could make it more engaging gameplay wise.

The gameplay is similar to a resident evil game, but without any combat. Once I decided to not include the combat, I noticed how many systems of the resident evil games are tied and dependant of the combat (like a lot of resources or even the merchant).

So far the only "mechanic" I have going on is dealing with a mental health bar, where it starts loosing health on dark places, or when witnessing scary things (even though the game is not meant to have paranormal elements on it).

I plan to add some puzzles and maybe some mini games, but I would like to know other ideas to make the game itself more enjoyable.

Another option I thought is just to promote more the narrative and exploration aspects of the game instead of the "survival horror" aspect.

Edit: There are no monsters nor paranormal things in the game!

## Best Human-rated Answer
One interesting way to look at this is to consider the game's "repeated mechanic." Many refer to the game loop. Same kind of reasoning.

You can do something with Movement, for example. Stealth is a movement repeat mechanic. Traversal is that too, but is present in almost every game.

You can do something with Looking. Frictional Games makes it so you can't look at the monsters without adverse effects. There's Fatal Frame, where you have a camera and you photograph things; also ties interaction to looking.

Basically, look at your feature set, consider if you can expand it with a repeated mechanic that requires constant player consideration, and you may have something going.

Survival Horror often has an element of scarcity as well. How could you add scarcity to the examples above?

## LLM Responses

### ChatGPT-5 Response
That’s a really interesting (and tricky) design space — a *survival horror game without combat or monsters*. But it’s totally possible to make that engaging! Games like *Amnesia: The Dark Descent* (when hiding, not fighting), *Firewatch*, *Signalis* (in its quiet moments), *What Remains of Edith Finch*, and *SOMA* (in non-combat sections) show how tension, atmosphere, and narrative can replace traditional combat loops.

Let’s go through some structured ways to make your game compelling:

---

### 🧭 1. Strengthen the **Core Loop** Around Exploration

Since you’re removing combat, exploration and discovery become the “verbs” the player performs most.
Make *exploration itself* rewarding and dynamic:

* **Environmental storytelling:** Every room or area should tell a mini-story through objects, notes, environmental changes, etc.
* **Progressive environmental change:** The world subtly shifts as the player’s mental state declines (e.g., lights flicker, sounds distort, objects move).
* **Locked pathways or progression systems:** Replace combat-driven progression (like keys from enemies) with *narrative* or *environmental* progression — solving mysteries, restoring power, finding evidence, etc.
* **Dynamic environments:** Have areas that evolve over time (e.g., mold spreading, clutter increasing, lighting worsening), creating tension.

---

### 🧠 2. Build Gameplay Around the **Mental Health Mechanic**

Your mental health system can be more than a depleting bar — it can drive unique gameplay interactions:

* **Perception distortion:** As sanity drops, the player’s perception of reality subtly warps — lights dim, sounds mislead, rooms appear different. This can make navigation or puzzle-solving more challenging.
* **Trust mechanics:** NPCs, clues, or even the environment could become unreliable as sanity wanes.
* **Recovery mechanics:** Encourage players to find safe spaces, light sources, or comforting memories (maybe linked to story items) to restore sanity. These become *resources* replacing ammo or healing items.
* **Moral or psychological choices:** Force players to make choices that affect mental health or the world’s perception of them (e.g., investigating traumatic evidence vs. looking away).

---

### 🔍 3. Replace Combat Tension with **Situational Tension**

Players need stakes and pressure, but not necessarily enemies.

* **Environmental hazards:** Gas leaks, collapsing structures, fires, floods, etc. create urgency without combat.
* **Time pressure:** A slowly deteriorating system (battery power, oxygen, light supply) can create sustained tension.
* **Stealth without enemies:** You could still have *threats*, even if not monsters — for example, unstable environments, human pursuers, security systems, or even just *being watched* through cameras.
* **Psychological tension:** Use sound design, camera movement, and environmental cues to make the player feel watched or unsafe.

---

### 🧩 4. Deepen Engagement with **Puzzles and Interactivity**

Instead of puzzles as “content fillers,” integrate them into the world and narrative:

* **Diegetic puzzles:** Every puzzle should make *narrative sense* (e.g., repairing an elevator, decoding a diary, restoring power to reach new areas).
* **Multi-solution puzzles:** Encourage player agency by allowing different ways to solve problems — logical, physical, or through exploration.
* **Procedural puzzles:** Vary elements so each playthrough feels fresh.
* **Physicality:** Simple tactile interactions (turning knobs, manipulating objects) can make puzzles feel more immersive and grounded.

---

### 📖 5. Emphasize **Narrative and Player Interpretation**

Since the story is your main hook:

* **Unreliable narration:** Let players question what’s real — not supernatural, but psychological.
* **Environmental consequences:** Player actions should visibly alter the world (e.g., choose to leave a room in darkness, and later it’s consumed by decay).
* **Found objects & notes:** Each discovery should feed both story *and* gameplay (sanity recovery, new routes, or insights that change perception).

---

### 🌌 6. Reward Curiosity and Observation

Without combat rewards, players need *exploration payoffs*:

* **Micro-narratives:** Short story threads or small mysteries resolved through exploration.
* **Visual payoffs:** Unique visuals or environments that reward players for thoroughness.
* **Collectible memories:** Photographs, letters, recordings — things that build emotional connection rather than just completion stats.

---

### 🪞 7. Examples & Inspirations

You might study:

* ***Signalis*** – uses resource tension and eerie atmosphere effectively, even without much fighting.
* ***Amnesia: The Dark Descent*** – sanity and environmental fear mechanics.
* ***Firewatch*** – exploration + emotional narrative.
* ***Pathologic 2*** – psychological pressure and resource management as “horror.”
* ***Gone Home*** – exploration and storytelling through environment.

---

### 🧩 TL;DR Design Pillars

If you had to summarize your game’s loop:

> **Explore → Discover → Interpret → Endure → Recover**

Replace *“fight to survive”* with *“understand to survive”*.
Your “resources” become *light, information, and sanity.*

---

Would you like me to help you sketch out a **core gameplay loop** (like a diagram or structured flow) for your non-combat survival horror? That would make it clearer how to balance exploration, tension, and narrative pacing.


### Gemini Response
Hello! That's a fantastic and challenging design direction. You've correctly identified the core issue: in *Resident Evil*, combat serves as a primary source of tension, a resource drain, and a "gate" for exploration. When you remove it, you need to find new ways to fill those roles.

The fact that you have **no monsters and no paranormal elements** is a *brilliant* constraint. It forces you to focus on psychological and human-scale horror, which can be far more effective.

Here are several ways to make your combat-free "survival horror" game engaging, building on your existing "mental health" mechanic.

---

### 1. The "Threat": Replace Combat with Evasion

The simplest way to add "survival" tension is to replace *fighting* an enemy with *avoiding* one.

* **The Human Antagonist (The "Stalker"):**
    Since there are no monsters, the threat must be human. Think of the stalker from *Clock Tower* or Mr. X/Nemesis from *RE* (but you can't fight him). This could be a killer, a security guard, a homeowner, or a cult member.
* **Gameplay Mechanics:**
    * **Stealth:** The core "combat" is now stealth. This involves line-of-sight, sound (footsteps, opening doors, knocking things over), and light (your flashlight beam).
    * **Hiding:** Introduce dedicated hiding spots (lockers, under beds, in closets).
    * **Distraction:** Allow the player to throw objects, set off alarms, or use the environment to lure the antagonist to a different area.
    * **Barricades:** Instead of fighting, maybe the player can temporarily block doors (e.g., shoving a cabinet in front of one) to buy a few precious seconds. This could consume a resource (e.g., stamina, or it makes a lot of noise).
* **How it Replaces the *RE* Loop:**
    * **Tension:** The constant threat of being *found* replaces the tension of a potential zombie encounter.
    * **Resource Drain:** Instead of draining ammo, a "chase" sequence could drain your Mental Health bar *rapidly*, making evasion critical.

---

### 2. The "Survival": Lean Heavily into Resource Management

Your Mental Health bar is the perfect starting point. Let's make it the central "health" resource and build systems around it.

* **Flesh out the Mental Health System:**
    * **Consequences of Low Sanity:** This is where you can have your "horror" without being paranormal.
        * **Perceptual:** Visual/auditory hallucinations (e.g., hearing footsteps that aren't there, seeing shadows move, doors *seeming* to open or close). The game lies to the player.
        * **Physical:** Shaky hands (making puzzles/lockpicking harder), fumbling with items, stumbling or making noise involuntarily, attracting the antagonist.
        * **Narrative:** The character might write incorrect things in their journal, misread clues, or lead to different (worse) endings.
* **Create New Resource Loops:**
    * **Sanity "Healing" Items:** What restores mental health? These replace *RE*'s "Green Herbs."
        * *Examples:* Tranquilizers, a specific song on a walkman (with limited battery), looking at a personal memento (which you can only do in a "safe" room).
    * **Light Management:** This is a classic.
        * *Resources:* Batteries for your flashlight, matches, a lighter, candles.
        * *Trade-off:* Being in the light stops your sanity from draining, but it *also* makes you more visible to the human antagonist. This creates a fantastic tension.
    * **Tool Management:** These are your new "weapons/ammo."
        * *Examples:* Lockpicks (that break), bolt cutters (that can only be used once), a crowbar (heavy, makes noise, but can open stuck doors), film for a camera (to document clues or "see" in the dark with flash).
        * *The "RE" Loop:* "Do I use my last lockpick on this optional safe that *might* have sanity items, or do I save it for the main story door I know is coming up?"

---

### 3. The "Gameplay": Make Exploration and Puzzles the Core

If the game isn't about combat, it must be about *something else*. Lean into investigation, exploration, and puzzles.

* **Puzzles with Stakes:**
    The best puzzles in horror games are the ones you have to solve *under pressure*.
    * *Example:* You need to find a 4-digit code. The code is split into parts around a large area. While you search, the antagonist is actively patrolling that same area. It's not just a brain teaser; it's a test of nerves.
* **Environmental Puzzles:**
    Go beyond "find key, use key."
    * *Examples:* Rerouting power, manipulating machinery, using sound to navigate, or even using your camera's flash to briefly reveal a clue painted on a wall.
* **Investigation as a Mechanic:**
    The main "goal" shouldn't just be "escape." It should be "understand." What happened here? Who is the antagonist? Why are they doing this?
    * **Clue System:** Finding notes, tapes, and environmental details fills out a journal.
    * **Deduction:** Perhaps the player needs to actively *connect* clues (like in a *Sherlock Holmes* game) to unlock the next part of the story or a new area. "The muddy boots + the broken window + the note = The antagonist is coming in from the garden."
* **"Safe Rooms" (The *RE* staple):**
    Keep them. They are *critical* in a high-tension game. This is where the player can breathe, manage resources, save their game (perhaps a limited "save" resource?), and *maybe* use a special item to restore a large chunk of sanity.

---

### Summary: Your New Gameplay Loop

Instead of *RE*'s "Explore -> Fight -> Solve -> Manage (Ammo/Health)":

Your new loop could be:

1.  **Explore:** Carefully move through new areas, managing your light source.
2.  **Investigate:** Find clues, notes, and items that build the narrative and present you with a problem (e.g., a locked door, a powered-down elevator).
3.  **Manage:** Juggle your resources: "Do I use a match to light this room and restore sanity, or save it? Do I have enough sanity to risk the long, dark hallway?"
4.  **Avoid:** Hear/see the antagonist. Hide, create a distraction, and wait for them to pass. This costs you time and sanity.
5.  **Solve:** Use your tools and the clues you've gathered (under pressure) to solve the puzzle and unlock the next area.

By focusing on a non-combat antagonist and making your Mental Health bar the central resource, you can absolutely create a compelling "survival horror" experience that lives up to the *RE* inspiration. Good luck!

### DeepSeek Response
Of course! This is a fantastic and challenging design space. Removing combat from a survival horror framework forces you to lean into the core pillars of fear: helplessness, uncertainty, and consequence.

Your core idea of a mental health bar (let's call it "Composure" or "Sanity") is a great foundation. Here are several ways to build upon it and create engaging, gameplay-driven loops without combat.

### 1. Deepen the "Composure" Mechanic: Make it a Core Gameplay Loop

Instead of it just being a "health bar" that drains, make it a dynamic resource that the player must actively manage.

*   **Tiered States of Mind:** Don't let it be a binary "Calm" vs "Panicked." Implement tiers:
    *   **Focused (High Composure):** The player sees and hears more clearly (e.g., visual clues might glow, they can hear faint whispers or distant sounds that provide hints).
    *   **Anxious (Medium Composure):** Standard gameplay. Slight visual and audio distortion.
    *   **Terrified (Low Composure):** Heavy visual distortion (blurring, tunnel vision), auditory hallucinations (false sounds of footsteps, doors slamming), and shaky controls. The player cannot solve complex puzzles in this state.
    *   **Broken (Zero Composure):** Results in a game over (e.g., the character faints and is captured, has a heart attack, or simply gives up).

*   **Active Calming Mechanics:** Give the player tools to manage their composure.
    *   **"Safe Havens":** Design specific, well-lit rooms (like a security office or a quiet closet) where the player can "catch their breath" and slowly restore composure. This creates a risk/reward dynamic of venturing out from safety.
    *   **Consumable Items:** Not ammo, but things like sedatives, a comforting photo, or a personal trinket that provides a quick boost of composure. This directly replaces the "herb" or "first-aid spray" function from Resident Evil.
    *   **Breathing Mini-game:** When the player's composure gets low, prompt them with a simple button-prompt breathing exercise (e.g., "Hold X to steady your breath") to prevent a panic attack.

### 2. Replace Combat with Evasion and Stealth

Since there are no monsters, the "threat" must be environmental or human. Think of games like *Alien: Isolation* or *Amnesia: The Dark Descent*, but with purely human antagonists.

*   **The Pursuer:** Introduce a persistent, non-paranormal threat. A stalker, a corrupt security force, or a deranged groundskeeper. This entity cannot be killed, only avoided.
    *   **Stealth Gameplay:** Use light and shadow. Staying in the dark drains composure but makes you harder to see. Staying in the light is safe for your mind but exposes you.
    *   **Hiding Spots:** Lockers, under beds, in closets. The classic horror trope becomes a core mechanic. Make hiding tense—maybe the pursuer checks some spots randomly.
    *   **Distractions:** The player can throw objects to create noise in another room, luring the pursuer away. This is a direct, engaging action the player can take.

### 3. Make Exploration Risky and Rewarding

Exploration shouldn't just be about finding keys. It should be a series of difficult choices.

*   **Risk vs. Reward Loops:** Place a crucial item (e.g., a fuse for a generator) in a high-stress area (e.g., a pitch-black basement that rapidly drains composure). The player must decide: "Do I risk my sanity to get the power back on?"
*   **Environmental Storytelling:** This is your narrative's best friend. Use audio logs, notes, and environmental details (e.g., a child's abandoned drawing, a broken-down car with a story) to build the world. The reward for exploring a dangerous area isn't just an item, but a crucial piece of the story.
*   **Resource Management (New Flavors):** Replace bullets and herbs with:
    *   **Light Sources:** Batteries for your flashlight are precious. Do you use it to see and preserve composure, or save it for a darker area later?
    *   **Tools:** A lockpick that can break, a crowbar to open new paths. These are your "weapon upgrades," but for utility.

### 4. Design Puzzles with Tension

Puzzles shouldn't be static. Integrate them with the horror.

*   **Time-Pressure Puzzles:** The player must solve a puzzle (e.g., reroute power in a fuse box) while the pursuer is actively searching the area. The sound of their footsteps gets louder, increasing the pressure.
*   **Multi-Stage Puzzles:** A puzzle requires items from multiple dangerous locations. The player must chart a course through the nightmare, planning their route to minimize risk.
*   **Sanity-Dependent Puzzles:** Certain clues or solutions are only visible/understandable when the player is in a specific state of mind (e.g., a hidden message only appears when you're "Terrified" and seeing things).

### 5. Rethink the "Merchant" or Progression System

You can still have a progression loop without selling guns.

*   **The "Safe Room" as a Hub:** Your safe haven could have a character on a radio or a computer terminal that acts as your "merchant."
    *   **Trade Information:** You find data drives or secrets that you can "trade" for new map data, passwords to locked doors, or hints about puzzle solutions.
    *   **Unlock Tools:** Progressively give the player new tools that open up exploration, like a keycard that opens new wings of the building, or a gas mask that allows entry into contaminated areas.
    *   **Upgrade Your Safe Haven:** Spend resources to make your safe room more effective—e.g., restore power for permanent light (stops composure drain), unlock a new hiding spot, or activate a security camera system to temporarily track the pursuer.

### Summary of a Potential Gameplay Loop:

1.  **Goal:** Get the key from the Administration Wing.
2.  **Risk:** The Administration Wing is pitch black and known to be patrolled by the Pursuer.
3.  **Preparation:** At your Safe Haven, you check your resources. You have one battery and one sedative. Do you use the sedative now to max your composure, or save it for the dark room?
4.  **Execution:** You navigate the dark halls, using your flashlight sparingly. You hear footsteps and hide in a locker, your composure draining. The Pursuer passes. You find the key, but it's in a well-lit room that the Pursuer frequently checks.
5.  **Choice:** Do you make a run for it, or use your last item to create a distraction in the hallway, luring him away?
6.  **Reward:** You get the key, a new audio log explaining the backstory of the Pursuer, and unlock a new area of the map.

By focusing on **dynamic resource management (Composure, Light), engaging non-combat interactions (Stealth, Puzzles), and a strong risk-vs-reward exploration loop**, you can create a deeply engaging and terrifying experience that stands on its own, completely without combat. Good luck with your game
