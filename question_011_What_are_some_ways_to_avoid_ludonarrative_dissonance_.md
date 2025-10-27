## Question 011

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1j7e5el/what_are_some_ways_to_avoid_ludonarrative

Date: 2025-03-09

## Problem Description
What are some ways to avoid ludonarrative dissonance? — If you dont know ludonarrative dissonance is when a games non-interactive story conflicts with the interactive gameplay elements.

For example, in the forest you're trying to find your kid thats been kidnapped but you instead start building a treehouse. In uncharted, you play as a character thats supposed to be good yet you run around killing tons of people.

The first way I thought of games to overcome this is through morality systems that change the way the story goes. However, that massively increases dev time.

What are some examples of narrative-focused games that were able to get around this problem in creative ways?

And what are your guys' thoughts on the issue?

## Best Human-rated Answer
The biggest ludo-narrative breaks for me when I play games are always matters of urgency. A game may have an open world, lots of things to explore, lots of secrets and minigames etc. but I can't really enjoy the sense of wandering and exploring if the story of the game is telling me that there is one super important time-sensitive task that I need to be doing above all else. In my opinion, any game with side quests or open exploration needs a narrative hook that says "Getting sidetracked into these other activities is a good thing". Things like:

"You're not very powerful yet. If you go directly to the main goal you'll probably fail, so go and find things to help you become stronger."

"We don't actually have a plan, we need more information first, so go out and investigate."

"You need to take odd jobs on the side too, otherwise you won't be able to pay the bills."

"The main quest needs your help, but lots of people you encounter in the world need help too, and that's what heroes do."

Being able to take a quest that's not related to your main goal and feel satisfied that it's what your character would do is a sign of a good game narrative. I think it draws on the same kind of vibes as TV series back when they were more than 8 episodes long, and there were tons of episodes that are just "here's something interesting that the protagonists would reasonably choose to do as they're traveling from point A to point Z".

## LLM Responses

### ChatGPT-5 Response
Excellent question — this is one of the trickiest and most-discussed design problems in narrative game design. You’ve already nailed the definition and pointed out how morality systems *try* to reconcile it, but as you said, they can balloon development scope quickly.

Let’s break this down into **three areas**: (1) design philosophy, (2) narrative techniques, and (3) examples of games that handled it well.

---

### 🧠 1. Design Philosophy: Preventing Dissonance Early

The best way to avoid ludonarrative dissonance is to **align the core loop with the narrative theme** from day one.
Some approaches:

* **Design gameplay around the protagonist’s values.**
  If your hero is compassionate or reluctant, the mechanics should reflect that. For instance, maybe combat isn’t about domination but about *survival* or *avoidance* (e.g., *The Last of Us Part II* framing violence as costly and painful).

* **Make the player’s goal and the character’s goal the same.**
  In *The Forest*, the story goal (find your son) and the gameplay goal (build and survive) can feel separate. You could integrate them: maybe building shelters or traps *directly aids* in searching (e.g., building radios, light towers, etc.).

* **Minimize dissonance through tone.**
  If gameplay *has* to be over-the-top (like *Uncharted*), lean into pulp adventure tone instead of realism. The story acknowledges the exaggeration — Nathan Drake’s “luck” and witty disbelief act as a narrative cushion.

* **Choose the right genre for your narrative.**
  A deeply serious emotional story doesn’t mix well with inherently chaotic mechanics unless the chaos *means* something. (For example, *Spec Ops: The Line* uses shooter mechanics to *criticize* the player’s complicity.)

---

### 🎭 2. Narrative & Presentation Techniques

* **Reframing actions through character perspective.**
  Let the character (and world) react to gameplay in a self-aware way. If the player kills, have the story acknowledge that emotionally or socially.

* **Environmental storytelling** to reinforce narrative tone.
  The world can remind players of the emotional or moral weight of their actions (bloodied hallways, memorials, survivor graffiti, etc.).

* **Procedural narrative linking.**
  Use systems that *adapt flavor text, dialogue, or quests* to reflect player choices without a full branching narrative system.
  For example:

  * NPCs comment differently depending on your playstyle.
  * Music or UI tone changes subtly if the player acts aggressively or mercifully.

* **Embrace ambiguity or unreliable narration.**
  Let players question whether what they’re doing *fits* because the story itself is ambiguous (*Disco Elysium* and *Inside* do this).

---

### 🎮 3. Games That Handled It Well

| Game                       | How It Avoided Dissonance                                                                                                   |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Papers, Please**         | The gameplay *is* the narrative conflict — mundane bureaucracy vs. morality.                                                |
| **Undertale**              | Story explicitly reacts to player behavior; violence vs. mercy are both valid gameplay loops.                               |
| **Disco Elysium**          | The player’s inner dialogue system merges story and mechanics; there’s no “off” time.                                       |
| **The Last of Us Part II** | Violence and story are consistent — every encounter reinforces emotional themes of revenge and loss.                        |
| **Spec Ops: The Line**     | Uses dissonance intentionally to critique shooter conventions — “why are you still playing?”                                |
| **Celeste**                | Platforming directly mirrors the protagonist’s emotional struggle; every failure reinforces the story.                      |
| **Red Dead Redemption 2**  | Story acknowledges gameplay inconsistencies through journal entries, dialogue, and morality; world reactions feel cohesive. |

---

### 💬 Thoughts on the Issue

Ludonarrative dissonance isn’t *always* bad — sometimes it’s **thematic**. It can highlight the absurdity or hypocrisy of the character or the player (as in *Spec Ops*). But when it’s unintentional, it breaks immersion.

Ultimately, the solution is **intentional design cohesion**:

* If story says “you’re desperate,” gameplay shouldn’t make you feel empowered.
* If story says “you’re kind,” gameplay shouldn’t make you a mass murderer — unless the narrative *acknowledges* it.

---

Would you like me to focus on **specific design techniques** (e.g., lightweight systems to handle morality without branching storylines), or more **case studies of games** that solved it elegantly within limited budgets?


### Gemini Response
This is a fantastic question and one of the most classic and difficult challenges in modern game design. You've perfectly identified the core issue and even the most common (and expensive) solution.

Here are some other, often more budget-friendly, ways to solve or mitigate ludonarrative dissonance, followed by the examples you requested and my "thoughts" on the issue.

### 1. Ways to Solve Ludonarrative Dissonance (Without Full Branching)

Instead of changing the *plot*, you can change the *context*, the *flavor*, or the *justification*.

* **Align the Narrative with the Gameplay Loop:** This is the most direct solution. If your core gameplay is exploration and crafting (like *The Forest*), don't make the primary story motivator a ticking time bomb.
    * **The Fix:** Change the story from "Find your kidnapped son *right now*!" to "You've crash-landed. You are the lone survivor. **Your goal is to survive.**" This *gives the player permission* to build a treehouse. The mystery of the cannibals and the "find son" plot can be a secondary, player-driven goal discovered through exploration, not an urgent opening mandate.
* **Narratively Justify the Gameplay:** This is the *Uncharted* fix. The problem isn't that Nathan Drake kills people; it's that the story *frames him as a charming, good-natured everyman* who just stumbles into trouble.
    * **The Fix:** Make the character's persona match their actions. If the character kills 500 people, write them as a hardened killer, a desperate survivor, or a psychopath. *Max Payne* does this well. His inner monologue is dark, violent, and poetic. He's a tragic, broken man, and his gameplay (violently shooting his way through his problems) is a perfect extension of that.
* **Use an Unreliable or Malleable Protagonist:** Instead of the story *telling* the player who the character is, let the player's *actions* tell the story who the character is.
    * **The Fix:** The protagonist is a blank slate (like in *Skyrim*) or their personality is intentionally vague. The game doesn't say "You are a good person." It just presents a world. Your actions (stealing, killing, helping) define who you are *in that world*. The dissonance is lower because the narrative isn't making a strong claim to begin with.
* **Use "Flavor" Reactivity (Instead of Plot Reactivity):** This is much cheaper than branching plots. The main story can stay the same, but the world and its characters *comment* on your actions.
    * **The Fix:** *Red Dead Redemption 2* does this beautifully. Whether you play Arthur as an honorable saint or a ruthless outlaw, the main plot points are largely the same. However, his *Honor rating* changes:
        * How random NPCs greet him (e.g., "Howdy, mister!" vs. "Get away from me!").
        * The content of his personal journal entries.
        * Specific lines of dialogue with main characters, who will call him out for being reckless or praise him for being kind.
    * This makes the player feel *seen* by the narrative, even when their actions aren't changing the ending.
* **Deconstruct the Dissonance (The "Meta" Approach):** Intentionally create ludonarrative dissonance and then make it the *entire point* of your story. This is high-risk, high-reward.
    * **The Fix:** The game starts like a normal shooter, but the story begins to question *why* the player is doing these things. Loading screens might taunt the player. The narrative reveals that their "heroic" actions are, in fact, monstrous.

### 2. Creative Examples of Narrative-Focused Games

Here are games that tackled this head-on with great success.

1.  ***Spec Ops: The Line*** **(The Deconstruction Example)**
    * **How it works:** This is the most famous example of tackling the *Uncharted* problem. It presents itself as a generic military shooter. You are a "good guy" hero. As you progress, your actions (which are standard shooter gameplay) are shown to have horrific, civilian-costing consequences. The story *is about* the dissonance between the player's "hero" fantasy and the "monstrous" reality of their actions. The game's famous loading screens eventually start asking things like, "Do you feel like a hero yet?"

2.  ***Disco Elysium*** **(The "Align Gameplay & Theme" Example)**
    * **How it works:** This is a murder mystery RPG with *zero* traditional combat. Your character is a broken-down, amnesiac detective. The "gameplay" isn't shooting; it's his own internal monologue. You "fight" your own addictions, insecurities, and bad ideas via skill checks. You "win" a conversation by using Logic or Empathy. The core mechanic (internal skill checks) is *perfectly* aligned with the narrative theme (a man rebuilding his shattered mind).

3.  ***Undertale*** **(The "Total Accountability" Example)**
    * **How it works:** This game *directly* ties its narrative to its gameplay mechanics. You can fight or "ACT" (spare) enemies. The story *completely* changes based on this, but more importantly, the game *remembers*. It's not just a "good" or "bad" ending; the game's entire tone, dialogue, and character relationships are built around your moment-to-moment choices. It solves dissonance by making *every* gameplay action a narrative choice.

4.  ***Papers, Please*** **(The "Mundane Gameplay as Narrative" Example)**
    * **How it works:** The gameplay is the seemingly boring act of being a border agent: checking passports. The narrative is the crushing moral weight of your actions. Do you follow the rules and deny a desperate grandfather, or do you break the rules to let him see his family (and risk getting a citation that docks your pay, meaning you can't afford medicine for your *own* sick child)? The gameplay *is* the moral choice. There is zero dissonance.

### 3. My "Thoughts" on the Issue

As an AI, I see this as a fascinating problem of system design. Here's my analysis:

* **It's a Problem of Urgency vs. Fun:** The root of the *Fallout 4* / *The Forest* problem is that the narrative introduces **extreme urgency** ("Find your son!"). But the core gameplay loop (exploring, crafting, side-questing) is **inherently non-urgent**. These two design goals are in direct opposition. The easiest fix is to *remove the urgency* from the main plot.
* **Suspension of Disbelief is a Resource:** Most players are perfectly happy to ignore *some* dissonance. We can enjoy *Uncharted* as a fun action-adventure romp and not think too hard about the body count. The "problem" arises when the dissonance becomes so great that it *breaks* the player's immersion and shatters their suspension of disbelief (like in *Tomb Raider (2013)*, where a cutscene shows Lara horrified by her first kill, and then 10 minutes later she's expertly mowing down 30 mercenaries).
* **"Gameplay is King" vs. "Story is King":** This issue often comes from a conflict between two design philosophies. If gameplay is king, you design a fun mechanic (like shooting or base-building) and then write a story to loosely justify it. If story is king, you write a powerful story and then design mechanics to *serve* it (like in *Papers, Please*). The best games find a harmony where both serve each other.
* **The "Player" vs. "Protagonist" Problem:** Are you, the *player*, making choices? Or are you *inhabiting* a pre-defined *protagonist* (like Nathan Drake)? Dissonance gets high when you are *playing* one way (chaotic, violent) but the *protagonist* in cutscenes is acting another way (calm, heroic). This is why the "flavor" system of *Red Dead 2* is so effective; it makes the protagonist (Arthur) slowly bend to match the player's actions.

**In summary:** You don't always need a massive, branching-plot morality system. Often, the more elegant solution is to align your game's mechanics and your story's *premise* from the very beginning. If your game is fun to explore, write a story about exploration, not a story about a ticking bomb.

### DeepSeek Response
Of course! This is a fantastic and central question in modern game design. Ludonarrative dissonance is a hurdle that every narrative-driven game must overcome, and it's great that you're thinking about it proactively.

Here’s a breakdown of creative ways games have tackled this issue, moving beyond just morality systems.

### Creative Ways Games Avoid Ludonarrative Dissonance

The key is to **align the player's goals with the character's goals, and the mechanics with the theme.**

#### 1. Make Gameplay the Metaphor
Instead of the story being a separate cutscene, the core gameplay loop itself *is* the narrative.

*   **Example: *Papers, Please***
    *   **The Dissonance Potential:** A game about the moral weight of being a border inspector could easily have a separate "story" about your family. If you could just abandon your post to go on an adventure, it would break the theme.
    *   **The Creative Solution:** The *entire game* is you inspecting passports. The "gameplay" of checking documents, spotting forgeries, and following ever-changing rules *is* the story. Every decision you make (denying entry, accepting a bribe) directly impacts the narrative of your family's survival. The mechanics and the narrative are one and the same.

#### 2. Integrate the "Side Activities" into the Narrative
Your "treehouse building" example is a classic case of a side activity that breaks the narrative. Some games find ways to make these activities feel diegetic and necessary.

*   **Example: *The Last of Us Part II***
    *   **The Dissonance Potential:** In a brutal, survival-horror world, stopping to craft a health kit or upgrade a weapon could feel gamey.
    *   **The Creative Solution:** The crafting and upgrading are slow, deliberate, and often tense. You are always exposed while doing it. The game makes you feel the *need* to do it to survive the next encounter. It's not a fun distraction; it's a desperate, narrative-driven act of survival that reinforces the world's danger.

#### 3. Thematic and Psychological Alignment
The gameplay doesn't have to be a literal representation of the story; it can be a symbolic representation of the character's internal state.

*   **Example: *Spec Ops: The Line***
    *   **The Dissonance Potential:** This is the ultimate subversion of your *Uncharted* example. It's a standard third-person military shooter... at first.
    *   **The Creative Solution:** The game *uses* the dissonance as its core theme. The repetitive, violent gameplay isn't a fun power fantasy; it's a descent into hell. The game makes you complicit in horrific war crimes and then asks, "Why do you keep playing? Do you feel like a hero?" The dissonance between the "hero narrative" and your brutal actions *is the entire point*.

*   **Example: *Hellblade: Senua's Sacrifice***
    *   **The Dissonance Potential:** A game about a Celtic warrior with psychosis navigating hell to save her lover's soul.
    *   **The Creative Solution:** The gameplay mechanics are directly tied to her psychosis. The "voices" in her head (which are brilliantly implemented with binaural audio) are not just story flavor; they give you hints, warn you of danger, and sow doubt. The visual puzzles are manifestations of her broken perception of reality. Fighting shadowy creatures is a fight against her inner demons. The gameplay *is* her illness.

#### 4. Structural and Pacing Solutions
Sometimes, the solution isn't in the mechanics themselves, but in how the game is structured.

*   **Example: *God of War (2018)***
    *   **The Dissonance Potential:** Kratos is a father trying to teach his son to be better than he was, yet he goes on violent side-quests.
    *   **The Creative Solution:** The game frames the central journey as the critical path. The Lake of Nine acts as a hub, and the side-quests are often framed as "favors for the dead" or necessary tasks to gain the strength/resources to continue the main journey. The writing constantly reinforces that these detours are part of preparing Atreus for the path ahead. The core father-son relationship is always the focus, even during combat.

*   **Example: *What Remains of Edith Finch***
    *   **The Dissonance Potential:** As a walking simulator, the risk is low, but the potential is in the player acting in a way that breaks the somber tone.
    *   **The Creative Solution:** The game is tightly controlled and linear. You are led through a series of vignettes, and in each one, the core mechanic is unique and perfectly married to the story being told (e.g., swinging on a swing to represent a child's imagination, chopping fish to represent a monotonous job turning into a fantasy). The player's interaction is so specific and curated that dissonance is nearly impossible.

### My Thoughts on the Issue

Ludonarrative dissonance isn't always a "bug"; sometimes it's a necessary concession to the medium. A perfectly harmonious game might be less "fun" or commercially viable. However, the games that successfully achieve harmony are often the ones we remember as masterpieces.

Here’s my perspective:

1.  **It's a Spectrum, Not a Binary:** Very few games have zero dissonance. The goal is to *minimize* it to a point where it doesn't break the player's immersion. A player happily building their settlement in *Fallout 4* might not care that the main quest is urgent, because the *fantasy* of rebuilding is compelling enough.
2.  **Player Choice vs. Authorial Intent:** This is the core tension. A heavy-handed, linear story (like *The Last of Us*) can achieve harmony by limiting player freedom. A vast, open-world game (like *Skyrim*) achieves harmony by giving the player the freedom to *create their own narrative*, even if it sometimes conflicts with the main one. Both are valid approaches.
3.  **The "Why" is More Important Than the "What":** A player will forgive almost any activity if the *motivation* is strong enough. If building that treehouse in the forest is the *only way* to get a vantage point to spot your son's captors, then it's no longer a dissonant distraction—it's a brilliant, narrative-driven strategy.

In summary, while morality systems are one tool, the most creative and effective solutions involve weaving the narrative directly into the fabric of the gameplay, using mechanics as metaphor, and carefully structuring the game's world and pacing to make every player action feel like a natural extension of the story being told.
