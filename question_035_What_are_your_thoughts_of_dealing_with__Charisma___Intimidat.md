## Question 035

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1ir88yh/what_are_your_thoughts_of_dealing_with_charisma

Date: 2025-02-16

## Problem Description
What are your thoughts of dealing with "Charisma" "Intimidation" in games? — I always sort of wondered about this, I like to put lots of points in Charisma because I love role playing as this awesome hero!

But then sometimes I feel the whole points part of it kind of kills the idea of Charisma. Like you become so good at talking you basically miss a whole bunch of content. Or someone dislikes you and instead of fighting them you just use "intimidation" which gets extra XP and you don't get to do the whole confrontation at all.

I guess it sort of feels like I just add points to some thing that allows me to take the easy way out which lacks substance. Is there any better way to deal with this system? Is this talking your way out actually more enjoyable to most as you get what you want?

## Best Human-rated Answer
It would be good to design it so that high Charisma doesn't automatically resolve situations, but instead, it opens up new choices. Within those choices, the player is free to decide which one to take. This way, Charisma becomes a tool for expanding the player’s options, and they can choose how to use it, which adds more depth to the gameplay.

## LLM Responses

### ChatGPT-5 Response
That’s a *great* and very common design dilemma — you’re touching on something that’s been debated in RPG design for decades. Charisma, persuasion, and intimidation systems often feel like they either:

* trivialize content (you skip conflict or challenge), or
* feel like “cheat buttons” that undermine story depth.

Here are several design approaches (used in various successful games) that can help make **Charisma-type skills** meaningful *without* hollowing out the experience:

---

### 🎭 1. Make “talking your way out” a **different kind of challenge**

Instead of a single “pass/fail” die roll, make persuasion/intimidation **interactive**:

* **Dialogue puzzles**: Instead of just clicking “Persuade,” make the player infer what motivates the NPC (as in *L.A. Noire* or *Disco Elysium*).
* **Multiple stakes**: Even if you succeed, you might lose reputation elsewhere or uncover only partial information.
* **Context-based modifiers**: Skills open *options*, not guaranteed successes — the player still needs to say the right thing.

✅ *Result:* Charisma doesn’t bypass gameplay; it *is* gameplay.

---

### ⚖️ 2. Balance “combat” and “conversation” rewards

The issue of “talking skips XP” vs. “fighting gives XP” often pushes players toward one mode.
Try these solutions:

* **Give equivalent XP or rewards** for resolving situations peacefully.
* Or, even better, give **different** rewards: talking might grant influence, allies, or lore instead of loot.
* *Planescape: Torment* and *Disco Elysium* are great examples — your words open entire new storylines.

✅ *Result:* Non-combat resolution feels just as valuable, not “easy mode.”

---

### 🧩 3. Treat Charisma as a *world-shaping* stat, not a “skip button”

Make Charisma influence *how* the world reacts to you, not just whether you win or lose a conversation.

* NPCs might trust you sooner, reveal hidden plots, or call in favors later.
* High Charisma could **unlock alternative story arcs** rather than just shortcuts.
* Sometimes, your “success” might even *backfire* — an NPC you persuade too easily might become dangerously loyal or overstep boundaries.

✅ *Result:* It deepens narrative consequences instead of removing content.

---

### 💬 4. Build mixed outcomes instead of binary ones

Instead of “Intimidate → instant success,” make outcomes more nuanced:

* Success might bring long-term resentment or loss of respect.
* Failure might still yield useful insight or make enemies you can later redeem.
* Each approach (fight, talk, bribe, charm) has its own *flavor* and cost.

✅ *Result:* Choices stay interesting even when “successful.”

---

### 🕹️ 5. Use Charisma to **expand** content, not reduce it

Players often feel “cheated” when a high Charisma roll *removes* a quest or conflict.
Instead, use Charisma to *add* scenes:

* Unlock a secret route, backstory, or new companion dialogue.
* Discover peaceful solutions that still have gameplay tension (e.g., negotiation minigames, timed choices).
* Let persuasion open new *types* of challenges (political intrigue, alliances, betrayal).

✅ *Result:* Talking becomes exploration, not an escape hatch.

---

### 🧠 6. Reflect player intent in character building

Your comment — wanting to roleplay a hero but feeling “cheap” for skipping fights — hints that the **game isn’t aligning narrative fantasy with mechanics**.
To fix that:

* Design the game so Charisma aligns with *being heroic*, not just avoiding danger.
* Maybe “Charisma” lets you **inspire allies**, **rally crowds**, or **defuse violence** — heroic, but still active.
* Don’t make the “talker” feel like they’re choosing the *short* route — make them feel like they’re *choosing the smart or noble* route.

---

### 🧭 Summary of Approaches

| Problem                            | Better Design Strategy                            |
| ---------------------------------- | ------------------------------------------------- |
| Talking skips content              | Make talking its *own* gameplay loop              |
| Rewards feel uneven                | Balance XP and rewards across playstyles          |
| Charisma feels like a “win button” | Add consequences and world reactivity             |
| Missed drama                       | Expand content via dialogue rather than remove it |
| Player fantasy misalignment        | Tie Charisma to active, heroic roles              |

---

Would you like me to sketch a **mechanic example** — like how a conversation encounter system could handle persuasion, intimidation, and failure dynamically (say, for an RPG or visual novel)? It could make this more concrete.

### Gemini Response
This is a classic and very difficult problem in RPG design, and your feelings about it are spot on. You've hit the nail on the head: when "Charisma" just becomes a "skip content" button, it feels unrewarding and hollow. It stops being role-playing and becomes a "win" button that makes you miss the game.

The core challenge is **making social interaction as engaging, complex, and rewarding as combat**, rather than just a way to avoid it.

Here are several ways developers can (and have) tried to solve this, moving from simple fixes to more complex systemic changes.

---

### 1. Shift from "Skipping Content" to "Altering Content"

This is the most crucial fix. A successful social check shouldn't *end* the encounter; it should *change* it. The goal is to provide **alternate content, not less content.**

* **The "Alternate Path" Solution:**
    * **Problem:** Intimidating the fortress guard makes him run away, and you just walk in, skipping the entire fortress layout.
    * **Solution:** Intimidating the guard makes him say, "Look, I can't let you through the front gate, my boss will kill me! But... there's a loose grate in the sewer that leads to the dungeons. Here's the key. Just... don't tell anyone you saw me."
    * **Result:** The combat player fights through the fortress (Content A). The social player navigates the trap-filled sewer and dungeon (Content B). Both are full, distinct gameplay experiences. The social build unlocked a *new* path, it didn't just skip the *only* path.

* **The "Information & Leverage" Solution:**
    * **Problem:** You "persuade" the quest giver to give you the reward without doing the quest.
    * **Solution:** Your high Charisma doesn't auto-win. Instead, it unlocks new dialogue options that reveal the *real* reason the quest giver wants the item (e.g., "You seem nervous... this isn't just about money, is it?"). You learn he's being blackmailed. Now you have a new objective: find the blackmailer.
    * **Result:** The social skill didn't *solve* the problem; it *reframed* it and gave you a more complex, interesting problem to solve, likely one that requires more investigation and talking.

### 2. Make "Talking" an Active System, Not a Passive Check

The user feels like they just "add points." This is because the *player* isn't doing anything; their *stat sheet* is. The solution is to make the dialogue itself a mini-game.

* **The *Deus Ex: Human Revolution* Model (Psychological Analysis):**
    In key "boss" conversations, you don't just pick "Persuade." You have to listen to the NPC, analyze their personality (e.g., "Alpha," "Beta," "Omega"), and choose the *correct approach*. Pressuring an "Alpha" might work, but pressuring an "Omega" will make them shut down. Your Charisma skill might unlock the "Analyze Personality" option, but *you* still have to make the right call.

* **The *Disco Elysium* Model (Internal Monologue):**
    This is the gold standard. Your skills (like "Rhetoric," "Empathy," "Intimidation") are characters in your head. A high "Rhetoric" skill doesn't just "win" an argument. It pipes up in your internal thoughts: "He's using a logical fallacy. Call him on it!" or "His hands are shaking. He's not as confident as he sounds. Press him." You still have to *choose* to follow that advice, and it can sometimes be *wrong*. This makes "talking" a rich, interactive, and uncertain process.

* **The "Knowledge-Based" Model:**
    A Charisma check should be *easier* or *only possible* if you've gathered leverage. You can't just "Intimidate" the guard. You have to *explore* first, find a "Smuggler's Ledger" in his barracks, and *then* use your Intimidation skill to say, "I know about your side business. Let me pass." This rewards exploration *and* social stats.

### 3. Rethink the "Success/Fail" Model (Graduated Outcomes)

The "easy way out" feeling comes from a binary pass/fail system. Adding nuance makes it feel more realistic and less like a cheat.

* **Full Success:** You get exactly what you want. (e.g., "You're right, hero. Here's the item, and my men will stand down.")
* **Partial Success:** You get *some* of what you want, but with a complication or a cost. (e.g., "Okay, I'll stop the attack... but you owe me. I'll call in a favor later.") This is great for storytelling.
* **Partial Failure:** You don't get what you want, and the situation gets *worse*. (e.g., "Nice try. I'm not scared of you. Now I'm going to tell my boss you're here, and he's doubling the guard.")
* **Critical Failure:** A fight starts immediately, and you're at a disadvantage (e.g., you're "Surprised" for the first round).

This system means a high Charisma stat is still valuable (it pushes you *towards* Full Success), but it's never a guaranteed, clean "win."

### 4. Rebalance the Rewards

* **XP for the Encounter, Not the Method:** This is the simplest fix. Whether you fight 5 guards, sneak past them, or persuade their leader to stand down, you are *resolving the encounter*. All methods should grant the *same* (or very similar) XP. This removes the "I got extra XP for doing less work" feeling. The challenge was "Get past the guards," and you succeeded.
* **Different Types of Rewards:** Maybe combat gives the most XP and Loot. But the social solution gives you a new, powerful **Ally**, or a unique piece of **Information** that opens a new questline, or a permanent **Reputation** boost in that town. This makes the choice about *what kind* of reward you want, not just "the easy one."
* **Add Long-Term Consequences:** Make the "easy way out" have a cost. If you "Intimidate" everyone you meet, your "Reputation" becomes "Tyrant." Now, honorable characters will refuse to work with you, and citizens will be too scared to give you information. Your "easy" solution has now made future quests *harder*. This adds *weight* to the choice.

---

### Is talking your way out more enjoyable?

To your last question: for many players, **yes, but only when it's done right.**

It's *not* enjoyable when it's a "skip" button.

It *is* extremely enjoyable when it makes the player feel **smart**. It's the fantasy of being the clever hero who outwits the villain, the smooth-talker who diffuses a bomb with words, or the terrifying badass who makes a room go silent.

When a player successfully navigates a *Deus Ex*-style debate or uses a clue they found in *Disco Elysium* to break a suspect, the feeling of accomplishment is *immense*—often more so than just winning another combat encounter.

The goal for a developer is to make the "Charisma" player feel like they **actively outsmarted** the problem, not that they just **skipped it**.

### DeepSeek Response
This is a fantastic and very common design dilemma that many players and developers grapple with. You've perfectly identified the core tension: **the "optimal" playstyle (maxing a skill) can feel at odds with the "fulfilling" playstyle (experiencing content).**

Your feeling that high Charisma/Intimidation can "skip" content is valid, but it's also worth reframing: it's not *skipping* content; it's *unlocking a different branch* of content. The key to a better system is making that branch feel just as substantive and rewarding as the combat path.

Here are several ways game developers (and you, as a player seeking a better experience) can think about solving this issue.

### 1. Redefine "Success" and "Failure" in Dialog

The problem often lies in the binary pass/fail nature of the skill check.

*   **The Problem:** Pass (Intimidation) = "They back down, you win." Fail = "They attack, you fight."
*   **The Solution:** Make success and failure create different, complex outcomes.

**Design Solutions:**
*   **Success with a Cost:** Intimidating the bandit leader works, but he swears revenge. Later, he ambushes you with stronger friends. You avoided one fight but created a harder one down the line. Charisma convinces the guard to look the other way, but now he loses his job and his family starves, creating a moral dilemma.
*   **Failure with a Benefit:** You fail the Intimidation check and a fight starts, but because you tried, the enemy is overconfident and makes more mistakes (giving you a combat advantage). Or, they respect your guts and are more willing to talk *after* the fight.
*   **Tiered Success:** Instead of one DC (Difficulty Class), have multiple. A bare pass might get you what you want, but a spectacular success unlocks extra information, a unique item, or a new ally.

### 2. Make Social Skills a Key to *More* Content, Not Less

The feeling of "missing out" is powerful. The solution is to design social skills as a unique key.

**Design Solutions:**
*   **The Social "Boss Fight":** Create encounters that are *only* solvable with high Charisma. A tense political negotiation, a trial where you must defend yourself with words, or a debate with a ghost that can't be harmed by weapons. This makes your investment feel essential, not just a shortcut.
*   **Unlock Unique Quests and Factions:** High Charisma shouldn't just close quests; it should open new ones. Persuading a character might make them invite you to their secret guild. Intimidating the right person might get you a job from a crime syndicate that would never trust a mere brute.
*   **Access to Unique Information:** The talkative bartender won't tell the hulking barbarian the secret, but he'll spill everything to the charming hero. This information can lead to hidden treasure, a enemy's weakness, or a way to resolve a situation without any bloodshed at all.

### 3. Integrate Social Skills with Other Systems

Charisma shouldn't exist in a vacuum. It should interact with the world and your other skills.

**Design Solutions:**
*   **Knowledge is Power:** A successful "Persuasion" check might require you to first pass a "History" or "Streetwise" check to know what lever to pull. "I'm not threatening you, but I *do* know about the embezzlement you've been doing. Now, about those castle gates..."
*   **Reputation Systems:** Your Intimidation success should depend on your reputation. If you're known as a pacifist, it will fail. If you're known as the "Butcher of Bravil," your mere presence is an intimidation check. This makes your actions throughout the game matter.
*   **Resource Cost:** Intimidation could cost "Morale" or "Resolve" (a finite resource). Persuading a king might require an extremely valuable item as a bargaining chip. It's not a free "I win" button; it's a strategic choice.

### 4. Shift the Player's Mindset (A Message to You, the Player)

While the above are for developers, you can adjust your own approach to find more enjoyment.

*   **Roleplay, Don't Min-Max:** You love role-playing as an awesome hero. Stick to that! Make dialogue choices that your *character* would make, not just the ones with the highest success chance. Sometimes a true hero gets angry and fails an intimidation check, leading to a righteous fight.
*   **Embrace the "Social Victory":** Reframe your thinking. Talking your way out of a fight isn't "the easy way out." For a charismatic hero, **it is the climax.** It's their version of a boss fight. You used your wits and presence to overcome a threat that others would have had to solve with violence. That *is* substance.
*   **Seek Different Rewards:** The XP for avoiding a fight should be equal to the XP for winning it, and many modern games do this. The real reward for the Charismatic path is often a cleaner conscience, better political standing, and unique narrative outcomes. You're not playing for XP; you're playing for the story.

### Conclusion: Is it more enjoyable?

For many players, **yes, it is profoundly more enjoyable.** It makes them feel smart, clever, and truly role-playing their character. The sense of "missing" the combat is real, but a well-designed game will offer plenty of other opportunities for combat. A poorly designed game makes social skills a simple "skip" button. A well-designed one makes them a "divert" button, sending you down a path just as rich and challenging, but in a different way.

The ideal system makes you pause and think: *"Do I want to be the hero who wins with a blade, or the hero who wins with a word?"* Both choices should be valid, compelling, and full of substance.
