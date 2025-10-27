## Question 018

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1kgzfvy/what_do_you_consider_moon_logic

Date: 2025-05-07

## Problem Description
What do you consider moon logic? — I want to make a pnc adventure with puzzles, problem is I hear a lot of people got a hard hate for "moon logic puzzles" which I can understand after dealing with the Gabriel Knight "Mustache" but it feels like any kind of attempt at something beyond "use key on lock, both are in the same room" winds up getting this title.

So I ask, what would the threshold for a real moon logic puzzle be?

I got a puzzle idea for a locked door. It's a school, it's chained shut and there a large pad lock on it.

The solution is to take some kind acid, put down a cloth on the floor so the drippings don't damage anything further and carefully use a pair of gloves to get the lock damaged enough to break off.

Finding the acid can be a fast look in the chemical lab, have a book say which acid works best the cloth could come from the janitor closet and the gloves too before getting through.

It feels simple and would fit a horror game set in a school.

## Best Human-rated Answer
I wouldn’t think to put a piece of cloth on the floor since it doesn’t seem like something more sturdy than the floor. I’m also not sure why I would be caring about the floor at all while trying to survive.

Maybe lean into it and have the acid dig a hole in the floor that affects the puzzle in the room under. That could go a long way into making the world feel cohesive and interconnected.

## LLM Responses

### ChatGPT-5 Response
That’s a really thoughtful question — and a common design pain point for point-and-click (PnC) devs.
Let’s break this down into **what “moon logic” means**, how to **avoid it**, and whether your **acid-lock puzzle** crosses that line.

---

### 🌓 What “Moon Logic” Actually Means

The term comes from puzzles that *technically* make sense in hindsight, but are so far removed from player expectations that they feel arbitrary or unfair.
Think:

* “Combine cat hair + masking tape + maple syrup to make a mustache.”
* “Use a rubber chicken with a pulley in the middle to cross a cable.”

Moon logic usually happens when:

1. The **real-world logic doesn’t match the game’s internal logic** (the player can’t guess what the designer was thinking).
2. The **clues are too obscure or disconnected**.
3. The **player’s action lacks a clear cause-and-effect** or feels like a random guess that just happens to work.

So the threshold isn’t about puzzle complexity — it’s about *clarity and coherence*.

---

### ✅ Your Acid-Lock Puzzle: Analysis

Your setup actually avoids most moon-logic traps:

| Element                                 | Realistic Logic                           | In-World Clues             | Player Intuition        |
| --------------------------------------- | ----------------------------------------- | -------------------------- | ----------------------- |
| Door chained with padlock               | Plausible obstacle                        | Visibly there              | Obvious “needs to open” |
| Acid from chem lab                      | Believable in a school                    | Common sense to look there | ✅                       |
| Book explaining which acid works        | Provides clarity and avoids brute-forcing | ✅                          |                         |
| Gloves and cloth to protect floor/hands | Logical safety steps                      | Reinforces realism         | ✅                       |

This is **good puzzle design** because:

* The **items have logical locations**.
* The **steps are thematically consistent** (school, chemistry, safety).
* The **solution makes intuitive sense** once the player gathers the clues.

It’s not moon logic — it’s just *multi-step logic*.

---

### 🧩 Tips to Avoid “Moon Logic” in Future Puzzles

1. **Ground every puzzle in either common sense or in-world logic.**

   * If it’s something the average person might try (even roughly), it’ll feel fair.
2. **Provide environmental hints.**

   * Posters about lab safety, a note about corrosive chemicals, etc.
   * Players should *feel clever*, not *lucky*.
3. **Ensure each required item has a clear reason to exist.**

   * Don’t add red herrings unless they serve tension or narrative.
4. **Test with fresh players.**

   * If more than one tester says “I’d never have thought of that,” clarify the clues.
5. **Reward partial reasoning.**

   * If the player tries to pour acid bare-handed, maybe the game warns: “This stuff will burn right through skin.” That gently guides them to look for gloves.

---

### 💡 Optional Polish for Your Puzzle

To make the acid puzzle feel extra satisfying:

* Include a **lab safety poster** or **teacher’s note** about acid dissolving metal.
* Make the **cloth drip protection** optional but rewarded (e.g., player comments “Good thing I protected the floor”).
* Add a **sound cue or visual** when the lock corrodes — sensory feedback matters.

---

### TL;DR

Your puzzle isn’t “moon logic” — it’s a solid, grounded multi-item puzzle.
“Moon logic” happens when puzzles rely on leaps of reasoning that the player has no fair way to infer.
Stick to **coherent in-world logic, environmental hints, and player feedback**, and you’ll be fine.

---

Would you like me to suggest a few variations of that acid-lock puzzle — one “simple,” one “medium,” and one “complex” — to see how difficulty can scale without slipping into moon logic?

### Gemini Response
This is an excellent question and one that sits at the very heart of adventure game design. The *Gabriel Knight 3* "cat-hair mustache" puzzle is infamous for a reason, and your fear is completely valid.

Let's break down your questions.

### What is the Threshold for "Moon Logic"?

You are correct that "moon logic" is often used as a catch-all for "a puzzle I found difficult or obtuse." However, there is a real design threshold for it.

**Moon logic is not about *difficulty*; it's about *deducibility*.**

A puzzle is "moon logic" when the solution requires the player to make an absurd, arbitrary, or impossible leap of logic. The solution cannot be reasonably deduced from the information, context, and environmental clues provided by the game.

The threshold is crossed when the player's reaction to the solution is: **"How in the world was I supposed to know that?"**

This is the opposite of a good puzzle's reaction, which is: **"Duh, of course! Why didn't I think of that?"**

Here are the key warning signs that you're drifting into moon logic:

1.  **Broken Causality:** The action and the outcome have no logical connection.
    * **Moon Logic:** Using a rubber chicken on a pulley to cross a canyon (*The Longest Journey*).
    * **Good Logic:** Using a plank of wood to bridge a small gap.

2.  **Lack of Signposting (Cluing):** The game fails to provide the necessary clues. If the player *must* find one specific pixel, read one missable line of dialogue, or combine two items that have no business being combined, it's moon logic.
    * **Moon Logic:** The *GK3* mustache. There is no clue suggesting you need a disguise, that tape will get cat hair, that syrup is an adhesive, or that you must combine them all to draw on an ID.
    * **Good Logic:** A character says, "The guard won't let me pass without a press ID." You find a blank ID. You find a photo. You see a lamination machine. The steps are logical.

3.  **Arbitrary Item Use:** The puzzle relies on using an item in a way that violates its "affordance" (what the item appears to be for) without any in-game justification.
    * **Moon Logic:** Using a toy monkey on a water pump (*Monkey Island 2*... though this is a comedy game, so it gets a *slight* pass).
    * **Good Logic:** Using a wrench to turn a bolt. Using a crowbar to pry open a stuck door.

---

### Analysis of Your Puzzle: Acid on a Padlock

**This is not moon logic. In fact, this is an excellent puzzle.**

Let's analyze *why* it works and is the *opposite* of moon logic:

1.  **The Goal is Clear:** The door is locked with a padlock. The player knows they must destroy or open that specific lock.
2.  **The Solution is Logical:** How do you destroy a metal lock without a key or bolt cutters? Melting it or corroding it with acid is a perfectly logical, real-world solution. The player can deduce this.
3.  **The Context is Perfect:** Where do you find strong acid in a school? The chem lab. Where do you find safety/cleaning gear? The janitor's closet. The items are exactly where the player would expect them to be.
4.  **The Cluing is Built-In:** Your idea to have a book in the lab "say which acid works best" is *perfect* signposting. This confirms the player's logical guess and guides them to the correct item.
5.  **The Extra Steps are Thematic, Not Arbitrary:** The gloves and cloth are not random. They add a layer of realism and consequence that fits a horror game.
    * **Gloves:** The player might think, "This is acid, it's dangerous." Finding gloves is a logical "safety" step.
    * **Cloth:** This shows the character is careful (or that the acid is *so* dangerous it will damage the floor). This enhances the world-building.

This is a great multi-step puzzle. The player identifies a problem (lock), brainstorms a solution (brute force? chemical?), explores a logical location (chem lab), finds a clue (book) confirming their theory, gathers the required items (acid, gloves, cloth), and executes the plan. Every step is logical.

---

### How to Avoid Moon Logic in Your Game

Here are some practical ways to keep your puzzles challenging but fair:

1.  **Clear Signposting is Everything:** You must "signpost" your solutions. This doesn't mean being obvious.
    * **Item Descriptions:** If the player examines the padlock, the text could be: "A heavy-duty steel lock. It's too thick to break, but the metal looks *pitted and vulnerable to corrosion*."
    * **Environmental Clues:** In the chem lab, maybe there's already a melted spot on a table with a "DANGER: CORROSIVE" sign.
    * **Character Dialogue:** The player character could say, "My lockpick won't work. Brute force is out... I need to find another way to *destroy* it."

2.  **Provide Logical Feedback:** When a player tries a logical-but-wrong solution, give them a helpful response.
    * **Bad Feedback:** Player uses a crowbar on the lock. Game says: "That doesn't work."
    * **Good Feedback:** Player uses a crowbar on the lock. Game says: "The lock is made of hardened steel. I can't get enough leverage to break it." (This tells the player "brute force" is the wrong *category* of solution, pushing them toward another idea, like "chemical").

3.  **Focus on Internal Consistency:** The rules of your world must be consistent. If you establish that fire burns rope, you can't later have a puzzle where fire *doesn't* burn a rope for an arbitrary reason. Your acid puzzle is great because it relies on a rule everyone already knows: "Strong acid dissolves things."

4.  **Playtest with New People:** This is the most important rule. You know the solution, so the logic is obvious to you. **Watch someone who has never seen the puzzle try to solve it.** Don't help them. If they get stuck, ask them, "What are you thinking right now?" If they are nowhere *near* the solution, your cluing is too weak. If they say, "I feel like I need to melt it, but I don't know where to find acid," you're on the right track.

### DeepSeek Response
This is an excellent question that gets to the heart of modern adventure game design. Your proposed puzzle is a fantastic case study to explore the line between a clever challenge and "moon logic."

Let's break down why your puzzle is actually **mostly good** and then refine it to ensure it crosses firmly into "fair and satisfying" territory.

### The Threshold for "Moon Logic"

"Moon logic" isn't about complexity; it's about a **complete breakdown in the player's ability to reason**. It occurs when the solution is only obvious to the puzzle designer because they have all the context, but the player has no reasonable path to connect the dots.

A puzzle becomes "moon logic" when it fails one or more of these key principles:

1.  **Internal Consistency:** The solution doesn't follow the established rules of the game world. (e.g., Using a cat's mustache hair to summon a fish ghost, as in *Gabriel Knight 3*, exists in a world where "voodoo ritual" is a known concept, but the *specific component* is absurdly obtuse and has no prior grounding).
2.  **Associative Logic:** The required action or item combination has no logical, thematic, or narrative association that the player can discern. The connection exists only in the designer's head.
3.  **Environmental Clues:** The game world provides no hints, direct or indirect, that point the player toward the solution. The player is just left clicking on everything until something works.
4.  **Reasonable Abstraction:** It requires the player to think of an object or action in a way that is completely outside of its primary, obvious function, with no setup.

### Analysis of Your "Locked Door" Puzzle

Your puzzle is **not inherently moon logic.** In fact, it's grounded in real-world physics (acid corrodes metal). However, it sits on a *slippery slope*. Whether it becomes frustrating or satisfying depends entirely on its **execution**.

**Why it's GOOD (and not moon logic):**
*   **Grounded Concept:** "Acid weakens metal" is a sound and understandable concept, especially in a school with a chemistry lab.
*   **Logical Item Locations:** The acid is in the chem lab, the cloth and gloves are in the janitor's closet. This makes perfect sense.
*   **Thematic Fit:** The method is destructive, slightly dangerous, and a bit "MacGyver-esque," which fits a horror game perfectly.

**Where it Could SLIP into Frustration (and be labeled "moon logic" by some):**
*   **The "Why" of the Cloth:** The most fragile part of your puzzle is the cloth. A player might think: "I have acid and gloves. Why can't I just carefully pour it on the lock?" Forcing them to protect the floor is a step that, without proper setup, can feel like unnecessary busywork or an arbitrary "gotcha" from the designer.
*   **Specificity of the Acid:** If there are five bottles of acid in the lab and only one works, with no way to tell which, that's moon logic.
*   **The Gloves as a "Gotcha":** If the player can pick up the acid without gloves and nothing happens, but then the game requires them to have gloves to use it, that's bad design. The danger should be established.

---

### How to Elevate Your Puzzle from "Okay" to "Great"

Here are concrete suggestions to implement your idea while ensuring it's fair and satisfying.

**1. Establish the "Rules" Before the Puzzle**
*   **Show, Don't Just Tell:** Before the player even gets to the door, have a minor environmental interaction. Perhaps in the chem lab, there's a spilled beaker that has visibly eaten through a countertop, leaving a nasty stain. This visually teaches the player "acid = dangerous to surfaces."
*   **Foreshadow the Solution:** A poster in the hallway about "Lab Safety" could list "Always wear gloves and use protective mats when handling corrosive chemicals." This isn't giving the answer away; it's establishing the *procedure*.

**2. Make the Environment Talk**
*   **The Door Itself:** The floor in front of the chained door shouldn't be pristine. Describe it as "an expensive-looking tiled floor" or, even better, show a small, old stain near the drainpipe, hinting that dripping here is a bad idea.
*   **The Janitor's Closet:** When the player finds the cloth, it shouldn't just be a "cloth." It could be a "chemical spill absorbent mat" or a "heavy-duty rubber mat." This strengthens the logical connection.

**3. Design a Logical Sequence, Not a Shopping List**
The player's thought process should be:
1.  **Problem:** Door is chained with a big padlock. I can't pick it or break it physically.
2.  **Brainstorm:** "I need to break the lock. How? Maybe chemically? I'm in a school, there's probably acid in the chem lab."
3.  **Complication (Established):** "But wait, that acid is dangerous. I saw what it did to the countertop/the safety poster said it damages floors. I need to protect the floor."
4.  **Solution:** "The janitor would have something for that. I'll check the janitor's closet for a mat and some gloves."

**4. Implement a Fail-State (for Horror)**
This is a fantastic tool for horror. If the player tries to use the acid without the mat:
*   **A dramatic event occurs:** The acid sizzles violently on the floor, creating a huge, permanent stain and releasing toxic fumes. The player has to retreat, and the game autosaves, making this mistake a permanent consequence. This makes the horror world feel more dangerous and real. (Offer a way to revert, like reloading, but make the in-world consequence severe).

### Revised Puzzle Flow (Ideal Execution)

1.  **Discover the Door:** Player finds the chained door. The description notes the "pristine floorboards" or "expensive tiles" beneath it.
2.  **Establish the Danger:** Earlier, in the chem lab, the player sees a corroded countertop from a spill. They also see a bottle of "Hydrochloric Acid" with a hazard symbol.
3.  **Find the "Key":** The player finds the acid. Picking it up triggers a line of dialogue or thought: "This looks dangerous. I should be careful not to spill any." This is the game's primary nudge.
4.  **Deduce the Safety Gear:** The player remembers the janitor's closet. Inside, they find "A Heavy-Duty Rubber Mat" and "Thick Chemical Gloves." The logical connection is now solid.
5.  **Execute the Solution:** The player combines the mat and acid in their inventory ("Prepared Acid") or uses the mat on the spot under the lock, then uses the acid with gloves on. The lock corrodes and breaks with a satisfying sizzle.

### Conclusion: Your Threshold

**The threshold for moon logic is crossed when the player cannot reconstruct the designer's thought process using the tools, clues, and world-rules provided to them.**

Your puzzle, as you've described it, is **close to the line but not over it.** By adding the layers of **environmental storytelling** and **foreshadowing** suggested above, you can move it firmly into the territory of a clever, fair, and thematically satisfying puzzle that players will solve and feel smart for figuring out, not frustrated by.

You are not aiming for "use key on lock." You are aiming for "a solution that feels inevitable in hindsight." That is the mark of a great adventure game puzzle.
