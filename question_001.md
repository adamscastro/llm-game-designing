## Question 001

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1hpufjc/why_are_yellow_climbable_surfaces_considered_bad

Date: 2024-12-30

## Problem Description
Why are yellow climbable surfaces considered bad game design, but red explosive barrels are not?

## Best Human-rated Answer
Here's a good article about yellow paint: https://critpoints.net/2024/03/03/yellow-paint-is-fine-actually/

"Mirror’s Edge had red object highlighting, called “runner’s vision”, for ladders, climbable pipes, balance beams, and springboards and pretty much everyone thought that was genius. People thought it was genius because it was diegetic and made sense for the story, and you can’t do that for every game, because not every game is about being a parkour runner. Why else did it work? Because the highlighted red interaction objects weren’t the only way to go, and frequently they weren’t the fastest. Mirror’s Edge actually had level design that featured multiple interconnected routes, not just a single context interaction point that you need to interact with to move the story forward."

"If climbing is as simple as knowing where the interact point is and pressing the interaction button (and maybe holding forward for a bit), then that’s not a very engaging game system. What’s disappointing about Yellow Paint is that it’s filler. It’s something the developers put into the game so that you’d do something other than simply walking from A to B. It’s variety for the sake of variety, made by a developer who cares more about content than design."

In contrast, red explosive barrels offer more interesting gameplay interactions. In a shooter, they interact with the main gameplay mechanic, shooting, instead of being a side minigame/QTE. You can make interesting decisions about when to shoot the barrel, or how to manipulate enemy movement to maximize the number of enemies near the barrel when you shoot it.

But given that the red highlighting in Mirror's edge was well-received, maybe the real takeaway is "red highlights > yellow highlights."

It's also worth noting that the red barrels are diegetic. If a company was transporting explosive materials, they would probably want it to be bright, noticeable, and clearly marked as dangerous.

## LLM Responses

### ChatGPT-5 Response
This is a really interesting and nuanced game design question — it touches on **visual language, player expectation, and world believability**. Let’s unpack what’s going on and suggest how to address the developer’s underlying concern.

---

### 💡 The Core Issue

The developer is noticing a **double standard** in player perception:

* **Yellow climbable surfaces** are often criticized as *“too game-y”* — they break immersion.
* **Red explosive barrels**, however, are widely accepted — players rarely complain about them.

Why do players forgive one and not the other?

---

### 🎯 Understanding the Difference

| Element                       | What It Does                 | Why It’s Often Accepted                                                    | Why It Might Feel Wrong                             |
| ----------------------------- | ---------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------- |
| **Red Barrels**               | Indicate danger or explosion | Fit a real-world logic (flammable = red), established convention since 80s | Overuse or illogical placement                      |
| **Yellow Climbable Surfaces** | Indicate traversable areas   | Clear readability for players                                              | Feels arbitrary, artificial, and immersion-breaking |

So the difference isn’t *mechanical*, it’s *diegetic* — the red barrel has **an in-world reason** for existing and being colored red, while the yellow ledge often exists **only to serve the gameplay**.

---

### 🧭 How to Solve or Improve the Yellow-Surface Problem

Here are several possible design approaches:

#### 1. **Integrate Visual Cues into the World’s Logic**

Make climbable objects *feel* like part of the environment:

* Use **wear patterns, moss, dirt, scratches, or paint** to signal usability.
* In an industrial world: use **yellow hazard paint** plausibly (e.g., scaffolding or construction zones).
* In a natural world: use **vine growth**, **distinct rock texture**, or **lighting contrast** instead of paint.

> Example: In *Uncharted 4*, climbable ledges blend into the environment with slightly lighter tones and logical erosion, not arbitrary color coding.

---

#### 2. **Use Multi-Layered Signaling**

Combine several subtle cues:

* Shape (edges jutting out slightly)
* Texture (scraped, worn, rope-wrapped)
* Animation (slight wind sway or lighting highlight)
* NPC behavior (someone previously climbed there)

The more cues you layer, the less you need one “gamey” color.

---

#### 3. **Contextual Consistency**

If you do use a strong color cue (like yellow), make it a **consistent part of the game’s fiction**:

* Maybe your world’s climbing tech uses **magnetic gloves** that interact with “gold alloy panels.”
* Or the in-world corporation paints maintenance areas yellow for safety.
* Players will accept *any* design choice if it has **internal logic** and consistency.

---

#### 4. **Adjust Readability vs. Immersion Balance**

There’s always a trade-off between **clarity** and **immersion**.

* In **fast-paced action games**, readability often trumps realism.
* In **immersive sims**, players expect subtlety and coherence.

If players criticize your yellow surfaces, it might mean they expect a more *diegetic* visual language than what you’re giving them.

---

#### 5. **Use Dynamic or Diegetic Highlighting**

Instead of static color coding:

* Use a **scanning mechanic**, **focus vision**, or **flashlight reflection** that highlights climbable surfaces only temporarily.
* This maintains clarity without constantly showing unrealistic markings.

---

### ⚙️ TL;DR — Ways to Fix It

| Problem                             | Possible Fix                                                |
| ----------------------------------- | ----------------------------------------------------------- |
| Yellow paint breaks immersion       | Integrate logically (e.g., safety paint, warning stripes)   |
| Players can’t tell what’s climbable | Add shape, lighting, and texture cues                       |
| Want less “gamey” design            | Replace universal color-coding with contextual storytelling |
| Need to balance clarity & realism   | Use dynamic highlighting or player-activated vision mode    |

---

### 🧠 Final Thought

Red barrels survive because they’re *anchored in both convention and logic*.
Yellow climbable surfaces fail when they’re **only convention, no logic**.

The solution isn’t to remove the color cues — it’s to **justify or naturalize them** so they feel like a natural part of the game world, not an instruction manual painted onto it.

---

Would you like me to show **specific examples from existing games** (e.g., *Uncharted*, *Tomb Raider*, *Doom*, *Half-Life*) to illustrate how they solved this issue differently?


### Gemini Response
This is a classic game design question! The core of the issue isn't about the specific *colors* (yellow vs. red) but about **diegetic design** versus **non-diegetic design**.

In short: **Red barrels feel like they belong in the game world, while yellow-painted ledges often feel like a UI element painted *onto* the game world.**

Here’s a breakdown of why one works and the other often feels "bad," along with solutions.

---

## The Core Difference: Diegetic vs. Non-Diegetic

* **Diegetic elements** are things that exist *within* the game's world and story. A character's in-game radio playing music is diegetic. A red barrel painted with a "FLAMMABLE" warning is diegetic. The character *in the game* can see it.
* **Non-Diegetic elements** are things that exist *outside* the game's world, purely for the player. Your health bar, an ammo counter, or a "Press X to Jump" prompt are non-diegetic. The character *in the game* cannot see them.

### Why Red Barrels Work (Diegetic)

The red explosive barrel is a classic example of **strong diegetic design**.

1.  **In-World Justification:** We accept that a "red barrel" exists in the game's reality. Red is a universal color for danger, warnings, and flammability. It's plausible that a company *in the game's universe* would paint a highly explosive barrel bright red for safety.
2.  **Clear Affordance:** The color and shape instantly communicate a function (an "affordance"). Decades of games have taught players: "Red Barrel = Shoot for Boom." It's a learned, consistent language.
3.  **Enhances the World:** It doesn't break immersion because it *makes sense* for the environment (a military base, an industrial site, etc.) to have dangerous, clearly-marked materials.



### Why Yellow Ledges Often Fail (Non-Diegetic)

The "yellow paint" problem is when a non-diegetic cue is disguised, poorly, as a diegetic one.

1.  **Breaks Immersion:** The player's brain asks, "Who climbed up here with a bucket of bright yellow paint and *only* painted the exact 2-inch ledge I can grab?" It makes no sense in the world. This is especially jarring in games aiming for realism (like *Tomb Raider* or *Uncharted*). It pulls the player out of the fantasy.
2.  **Feels Like "Hand-Holding":** It can feel condescending. Instead of letting the player observe the environment and find a plausible path (a cracked bit of brick, a sturdy-looking window sill), the game is just shouting, "CLIMB HERE!" It turns exploration into a "connect-the-dots" exercise.
3.  **Limits Player Agency:** The player stops *looking* for climbable surfaces and just starts *scanning* for the color yellow. They are no longer problem-solving; they are pattern-matching.

---

## How to Solve the "Yellow Ledge" Problem

You need to signpost your climbable paths, but you can do it more elegantly. The goal is to make your climbing cues **diegetic** or at least **more subtle**.

### 1. Use Diegetic Environmental Cues

Instead of *paint*, use parts of the environment that logically suggest a handhold. This is the "Uncharted" or "Horizon Zero Dawn" approach.

* **Architecture:** Use specific types of brickwork, exposed rebar, or ornamental ledges. Make the *rule* "you can always grab these specific types of bricks."
* **Vegetation:** Have ivy, thick vines, or moss growing *only* on the paths you can climb.
* **Wear and Tear:** Use scuff marks, chalk marks from previous climbers, water stains, or bird droppings to subtly highlight a ledge.
* **Lighting:** Use a spotlight or a ray of moonlight to naturally draw the player's eye to the start of a climbing path.



### 2. Justify the "Unrealistic" Cue

This is the *Mirror's Edge* solution. The game's world isn't *actually* full of red pipes and ledges. The red color is part of the "Runner's Vision," a non-diegetic UI that is *justified* by the main character's training. It's an in-game "augmented reality" overlay.

* **Create a "Visor" Mode:** Give the player a high-tech scanner (like *Metroid Prime*) or a special "sense" (like *The Witcher* or *Assassin's Creed*'s "Eagle Vision") that highlights interactive objects. The world is normal by default, but the player can *opt-in* to see the UI cues.
* **Make it Part of the Lore:** If your character is, say, an android, maybe their optical sensors naturally highlight climbable surfaces in yellow.

### 3. Lean into the "Game-y" Art Style

If your game is highly stylized, abstract, or cartoonish (like *Mario* or *Ratchet & Clank*), then **bright yellow ledges are perfectly fine!**

The problem only exists when there's a *clash* between a realistic art style and an unrealistic, game-y mechanic. If your whole world is stylized, the yellow paint fits right in.

### 4. The "Subtle Paint" Compromise

If you must use paint, don't make it bright, primary yellow.

* The *Tomb Raider* reboot (2013) famously used **white paint**. It's still artificial, but it's much more subtle than yellow. It looks more like chalk or faded paint, which feels more plausible than a bucket of wet, yellow gloss.
* Use a color that's already in your environment's palette but just a *bit* different. For example, in a blue-ish ice cave, make the climbable ice a slightly more saturated, grippable-looking teal.

### DeepSeek Response
Of course. This is an excellent question that gets to the heart of intuitive game design. The issue isn't about the colors themselves, but what they communicate to the player and how they integrate into the game world.

Here’s a breakdown of the problem and several solutions for the developer.

### The Core of the Issue: Diegesis and Player Psychology

The fundamental difference lies in **Diegesis**.

*   **Red Explosive Barrels (Non-Diegetic or Semi-Diegetic):** Their red color is often a **universal, non-diegetic signal** to the player. While a barrel in that world might have a "Danger" or "Flammable" sticker, the color red is amplified by game conventions as a meta-signal for "explosive." It's a visual shorthand that players have been trained to understand across hundreds of games. It's efficient and instantly readable.
*   **Yellow Climbable Surfaces (Purely Non-Diegetic):** Painting a ledge yellow *solely* to indicate it's climbable often feels like the developer is directly painting on the game world. There's usually no **in-world reason** (a diegetic one) for that surface to be yellow. It breaks immersion because it feels like a UI element slapped onto the environment, not a part of the environment itself.

In short: **Red barrels use a color convention. Yellow ledges often rely on a color crutch.**

---

### Suggested Solutions for the Game Developer

The goal is to make climbable surfaces feel like a natural part of the world while still being intuitively understood by the player. Here are several approaches, from simple to complex.

#### 1. The "Environmental Storytelling" Solution (Best Practice)

Make the climbable surface visually distinct for a reason that makes sense in the game's world.

*   **Use Wear and Tear:** Climbable surfaces should show evidence of use. This could be:
    *   **Scuff marks** from boots and hands.
    *   **Handholds and footholds** that are visibly carved or eroded.
    *   **Discoloration** from repeated contact.
    *   **Dripping water or moss** that follows a climbable path, suggesting a natural route.
*   **Use Architecture and Design:** The shape of the object should invite interaction.
    *   **Protruding bricks, ledges, and rebar** on a cliff face or wall.
    *   **Ladders, ropes, and vines** are universally understood.
    *   **Clear "paths"** of climbable rocks that contrast with the smoother, non-climbable surfaces around them.

**Example:** Instead of a random yellow pipe, use a pipe with obvious rivets, joints, and brackets that logically form handholds.

#### 2. The "Consistent Visual Language" Solution

If you must use color, make it part of a consistent, in-world visual language.

*   **Faction-Based Design:** Maybe a specific faction in your game uses yellow paint to mark safe routes or supply caches. This gives a *diegetic reason* for the color. It's no longer "yellow = climb," it's "the Scout Guild marks their paths with yellow."
*   **Material-Based Design:** Use a specific material that is always climbable. For example, "All surfaces made of 'Vibranium Ore' are climbable," and that ore has a distinct, shimmering blue color. This is how **Glowing Mushrooms** in *Metroid* or **Tearstone** in *Dark Souls* work.

#### 3. The "Guided Player Discovery" Solution

Teach the player to recognize climbable surfaces through subtle guidance rather than blatant color-coding.

*   **The "First Time" Tutorial:** Force the player to climb a very obvious, uniquely shaped surface early in the game. Once they understand the mechanic, they will look for similar geometry elsewhere.
*   **Placement of Props:** Place a corpse, a discarded weapon, or a glowing collectible on the first ledge of the climbable path. The player's eye is drawn to the object, and they naturally discover the path to get there.
*   **Audio Cues:** A subtle wind sound, creaking ropes, or the sound of crumbling rock can draw attention to a climbable area without altering its visual design.

#### 4. The "Hybrid" Solution (What Modern Games Do)

Combine a subtle visual highlight with the environmental logic. This is often the most player-friendly approach.

*   **Contextual "Glow":** Use a very subtle shimmer or particle effect on climbable surfaces. In *The Legend of Zelda: Breath of the Wild*, climbable surfaces don't glow, but Sheikah Slate runes highlight climbable walls in a way that feels technological and diegetic.
*   **Character Prompt:** When the player gets near a climbable surface, a button prompt (e.g., "Press X to Climb") appears. This doesn't paint the world, but it clearly communicates interactivity. *The Last of Us* and the *Uncharted* series use this method effectively alongside believable level geometry.

### Summary Table for the Developer

| Feature | Red Explosive Barrel | **Bad** Yellow Ledge | **Good** Climbable Surface |
| :--- | :--- | :--- | :--- |
| **Integration** | Semi-Diegetic (convention + in-world object) | Purely Non-Diegetic (feels like UI) | **Diegetic** (part of the world) |
| **Logic** | "Barrels explode. Red means danger." | "The developer painted this for me." | **"This looks climbable because of its shape/texture."** |
| **Player Feeling** | "I understand the game's rule." | "I'm being led on a leash." | **"I figured this out. I'm smart."** |

**Final Recommendation for the Developer:**

Audit your game's climbable surfaces. For each one, ask: **"Is there an in-world reason this looks climbable?"** If the only answer is "because it's yellow," you should redesign that asset or its context using the "Environmental Storytelling" or "Hybrid" solutions. This will make your world feel more immersive and reward player intelligence.
