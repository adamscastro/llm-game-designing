## Question 013

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1m37r4r/do_there_exist_crafting_systems_that_allow_for

Date: 2025-07-18

## Problem Description
Do there exist crafting systems that allow for "discovery and experimentation" without brute forcing a crazy number of unique combinations? — A friend of mine is planning a cooking + resource gathering game but I'm seeing some red flags in the design.

In his game, there are about 20 base ingredients (meat, fruit, spices, various herbs and mushrooms) and they can all be combined with each other to create different dishes. These dishes can then be further combined with each other or additional ingredients to make even more dish recipes. The final goal is to create a legendary super dish that involves multiple repeated combinations of different dish recipes and ingredients in a very specific order.

I typed a rough approximation of this description into chatgpt and it said there are potentially a million different combinations (no idea how accurate but I'm pretty sure the actual number is stupid big regardless)

Obviously the game can't handle a million different recipes so most combinations would have to be a bust.

But just telling the player the recipes also removes the fun of discovery of the game and more or less trivializes the final goal.

So basically I think this game's design is running into a deep hole, but maybe there are other games out there that's tried something spiritually similar and succeeded?

## Best Human-rated Answer
There are several ways to successfully manage something like this without it spiralling into a million unique recipes.

Converging recipes: 'Root Veg' + 'Protein' = 'Stew' - think BotW. It doesn't matter whether it's [Carrot and Chicken], or [Potato and Beef], but you get a stew at the end. Effectively means that your unique ingredients combine in less unique ways. But people still get the fun of experimentation without a bunch of recipes failing on principle, while not spiralling outwards to too many unique recipes to handle.

Give people recipes: Discourage too much experimentation. This is the most likely I think to make people stop and look up recipes. But it is a valid route to take. Make a lot of recipes fail, but give the player a lot of routes to find the recipes in other ways (through whatever reward system your game is going to take).

Guided experimentation: When a recipe fails (or even when it succeeds), suggest a different way to take it. "Oh, this didn't work, maybe you should try adding meat" or "A simple dish, maybe you could add mushrooms next time for flavour".

Don't let recipes fail: If the recipe wouldn't work then just say "Nope, this won't work" and don't use the ingredients. I think people are more likely to try and brute force a bunch with this method - which may be contrary to what you're trying to achieve.

Those are some quick thoughts off of the top of my head. There's probably a bunch more that others will expound on.

## LLM Responses

### ChatGPT-5 Response
Excellent question — this is a **classic game design problem** that sits at the intersection of combinatorial explosion and player-driven discovery. The short version: you *can* absolutely have crafting systems that encourage **experimentation and discovery** without overwhelming players or developers — but it requires introducing **structure**, **meaningful feedback**, and **constraints** to avoid brute-force chaos.

Let’s break it down.

---

## 🧩 The Core Problem

Your friend’s idea suffers from **combinatorial explosion**:

* 20 base ingredients → possible combinations = 20² = 400 for 2-item recipes, 20³ = 8,000 for 3-item recipes, etc.
* Add chaining of recipes → exponential growth.

Even if only 1% of combinations are valid, that’s still hundreds or thousands of recipes — too many to design, test, and balance.

The key is to **limit combinations while maintaining a sense of discovery**.

---

## ✅ Strategies That Have Worked in Other Games

### 1. **Categorical / Tagged Ingredients (The “Spelunky” Approach)**

Give ingredients **tags** like:

* “Sweet,” “Savory,” “Protein,” “Spicy,” “Filling,” “Poisonous,” etc.

Then, recipes are based on **tag combinations**, not individual items.

**Example:**

* “Sweet + Protein” = “Candied Meat”
* “Savory + Spicy + Protein” = “Curry”
* “Sweet + Spicy” = “Sweet Chili Sauce”

Players can still experiment freely, but the number of unique recipes becomes **combinatorially smaller** (e.g., 6–8 tags → dozens, not millions, of outcomes).

Games that do this:

* *Don’t Starve* (crockpot cooking system)
* *Breath of the Wild* (ingredient categories)
* *Potion Craft* (alchemical properties on axes)

---

### 2. **Property-Based Synthesis (Alchemy-Style Systems)**

Each ingredient contributes **properties or stats** rather than being a unique node in a combination tree.

For example:

* Apple → +Sweet +Health
* Chili → +Spicy +Energy
* Mushroom → +Earthy +Stamina

The result is a **recipe outcome that reflects the property mix**, not exact items.

This creates *emergent results* from limited rules, and players can intuitively predict outcomes.

Games that do this:

* *Atelier* series
* *Noita* (chemistry system)
* *Skyrim’s* alchemy (discover properties via experimentation)

---

### 3. **Hierarchical Crafting with Milestones**

Instead of allowing *any* dish to combine with *any* dish, restrict progression to **tiers** or **phases**:

* Tier 1: Raw ingredients → simple dishes
* Tier 2: Simple dishes + condiments → complex dishes
* Tier 3: Combine a few specific “core” dishes → legendary dish

This prevents unbounded mixing and provides a **sense of direction**.

Games that do this:

* *Minecraft* (tiered crafting)
* *Valheim* (progressive tech tree)
* *Cook, Serve, Delicious!* (structured upgrades)

---

### 4. **Fuzzy Discovery Systems**

Instead of binary “success/failure,” give **graded feedback**:

* “That combination smells odd.”
* “This looks edible but bland.”
* “You sense potential synergy between these flavors.”

Players learn *through feedback*, not brute force.
Later, you can introduce tools or NPCs that give **hints**, e.g., “I heard spicy and sweet go well together!”

Games that do this:

* *Don’t Starve* (dish previews)
* *Little Alchemy*
* *Potion Permit*

---

### 5. **Hidden Formula with Pattern Learning**

Have a **secret logical structure** to recipes, so players who experiment can *learn patterns*, not memorize random recipes.

Example logic:

* Dish name = primary + secondary + seasoning type
* Rules like:

  * “Two ingredients of same tag amplify effect.”
  * “Contradictory tags cancel out.”
  * “Adding spice after cooking doubles flavor.”

This way, discovery becomes **deductive reasoning**, not blind guessing.

Games that use this:

* *Opus Magnum* (logical synthesis)
* *Paper Mario: TTYD* (predictable recipe patterns)

---

### 6. **Social Discovery / Shared Knowledge**

If it’s multiplayer or community-oriented, let **players share recipes** via journals, rumors, or marketplace clues.
That turns recipe discovery into a **social metagame** rather than a solitary grind.

Games that use this:

* *Minecraft* (wiki-driven crafting)
* *No Man’s Sky* (community recipe lists)
* *Monster Hunter* (shared meal systems)

---

## 🧠 Recommended Design Mix for Your Friend

To preserve fun *and* sanity:

1. **Use tags for ingredients** (6–8 meaningful types max).
2. **Limit combination scope** (max 3 ingredients per recipe).
3. **Add feedback** that gives hints about what’s working.
4. **Gate higher-tier recipes** behind story or items.
5. **Reward pattern recognition**, not guessing.

That structure would yield:

* <100 meaningful combinations,
* A strong sense of experimentation,
* Manageable development load,
* Clear learning curve for players.

---

Would you like me to sketch a **sample rule system** (like a small prototype design table) that shows how tagging + feedback could work for this kind of cooking game? It could help your friend visualize how to keep the system deep but manageable.

### Gemini Response
You've hit on one of the most difficult "deep holes" in crafting game design: the tension between **Combinatorial Freedom** and **Meaningful Discovery**.

Your friend's concern is 100% valid. A system where 20+ items can be combined with each other, and *then* those results can be combined again, doesn't just create a "million" combinations. The number is astronomically, unmanageably large.

This is called **Combinatorial Explosion**. Players will *not* find this fun. They will either brute-force combinations (which is tedious) or, more likely, immediately go to a wiki. Both outcomes destroy the intended "discovery" loop.

Yes, many games have solved this! The solution is to *not* have a truly "free" system. Instead, successful crafting systems use clever "scaffolding" to guide the player and make discovery feel logical and rewarding, not random.

Here are possible ways to solve this, ranging from simple to complex, with examples.

---

### 1. The "Tags and Categories" System (like *Breath of the Wild*)

This is probably the most elegant solution for a cooking game. The 20 ingredients don't matter as *unique items*, but for the *properties* or "tags" they have.

* **How it works:** You don't have 20 unique ingredients. You have 5-6 *categories* of ingredients.
    * **Categories:** `Base` (Meat, Fish, Tofu), `Vegetable` (Carrot, Potato, Onion), `Spice` (Salt, Pepper, Chili), `Fruit` (Apple, Banana), `Garnish` (Herb, Mushroom).
* **Recipes are based on categories, not specific items:**
    * `Base` + `Vegetable` = "Simple Stew"
    * `Base` + `Spice` = "Seasoned Skewer"
    * `Fruit` + `Fruit` = "Fruit Salad"
* **The "Discovery":** The *specific* ingredient used provides a *bonus effect* or *variation*.
    * `Boar Meat` (Base) + `Carrot` (Vegetable) = "Simple Stew" (Heals 3 hearts)
    * `Prime Meat` (Base) + `Carrot` (Vegetable) = "Hearty Stew" (Heals 6 hearts)
    * `Boar Meat` (Base) + `Spicy Pepper` (Spice) = "Spicy Skewer" (Heals 3 hearts + Cold Resist)

**Why this works:**
* It slashes the number of *base recipes* from millions to a few dozen.
* Experimentation is immediately rewarded. The player thinks, "What happens if I use a *spicy* ingredient instead of a regular spice?" or "What if I use *better* meat?"
* It's logical. The player can *deduce* recipes. "I made a stew with meat and a vegetable. I bet I can make a mushroom stew with meat and a mushroom."
* "Busts" are rare. `Meat` + `Apple` might just make "Dubious Food," but it's a logical failure, not one of a million random failures.

### 2. The "Recipe Fragment & Hint" System (like *Stardew Valley* or *Minecraft*)

In this system, you *cannot* craft an item until you have "learned" the recipe. The "discovery" is not about guessing combinations, but about *finding the recipe itself*.

* **How it works:** The world is full of hints.
    * **NPCs:** An old lady gives you a quest: "My back hurts. My grandma used to make a 'Soothing Herbal Balm'. I think it had `Rivercress` and `Honey`..." (Recipe learned!)
    * **Quests:** A quest reward is "Recipe: Warrior's Steak."
    * **Exploration:** The player finds a "Burnt Recipe Page" in a dungeon that has `[illegible]` + `Mushroom` + `Spice`. The player must now *experiment* to find the missing ingredient (a much smaller, more guided task).
    * **Leveling Up:** A "Cooking" skill unlocks new recipes at each level.
* **The "Legendary Dish":** This is the perfect solution for the "super dish." It's not something you *guess*. It's the ultimate quest. The player must find 10 "Legendary Recipe Fragments" hidden across the world, which, when combined, reveal the final, complex recipe. The challenge becomes *finding* the recipe and *gathering* its rare components, not the random guesswork.

**Why this works:**
* It completely eliminates brute-forcing. You *must* engage with the game world.
* It ties crafting directly to exploration, questing, and character progression.
* It allows for very complex recipes (like the super dish) without feeling unfair.

### 3. The "Property-Based" System (like *Atelier* or *Potion Craft*)

This is the most complex but also the most rewarding for pure "experimentation." The goal is not to find a discrete recipe (`A + B = C`), but to create an item with specific *properties*.

* **How it works:** Every ingredient has hidden (or visible) traits.
    * `Boar Meat`: {Quality: 10, Flavor: 'Salty', Effect: 'Stamina'}
    * `Fire Herb`: {Quality: 5, Flavor: 'Spicy', Effect: 'Cold Resist'}
    * `Rivercress`: {Quality: 7, Flavor: 'Bitter', Effect: 'Poison Resist'}
* **Crafting is about combining properties:**
    * `Boar Meat` + `Fire Herb` = "Dish" {Quality: 15, Flavor: 'Salty', 'Spicy', Effects: 'Stamina', 'Cold Resist'}
* **The "Discovery":** The game is not about finding "recipes." It's about finding ingredients with the best properties. The player thinks, "I need to make a dish for a quest that is 'Spicy' and has 'Stamina'. I know `Fire Herb` is spicy and `Boar Meat` has stamina. Let's combine them!"
* **The "Legendary Dish":** The final goal isn't a specific recipe. It's a *challenge*: "Create a dish with `Quality > 100`, a `Divine` flavor profile, and the `Immortality` effect." The player must then experiment for hundreds of hours, finding the *rarest* ingredients with the *best* traits to stack and combine until they hit that target.

**Why this works:**
* *Every* combination yields a result. There are no "busts," only "weaker" or "stronger" outcomes.
* This is *true* experimentation. The player is a "food scientist" optimizing a formula.
* It supports infinite complexity without a wiki, because the results are based on a visible, logical system of properties.

---

### My Recommendation for Your Friend:

A **hybrid of System 1 and System 2** is the most proven and effective model for this type of game.

1.  **Use the "Tags and Categories" (System 1) for all *base* cooking.** This lets players experiment freely and logically ("Meat + Veggie," "Fish + Spice," "Fruit + Sugar"). This forms the fun, minute-to-minute gameplay loop.
2.  **Use the "Recipe Fragment & Hint" (System 2) for all *special* dishes, and especially for the "Legendary Super Dish."** This multi-step, complex recipe should be the reward for a long and difficult quest line. The player should feel like they *earned* this knowledge, not that they *guessed* it.

This approach gives you the best of both worlds:
* **Casual Experimentation:** Players can play around with basic ingredients.
* **Guided Discovery:** Players are rewarded for exploring and talking to NPCs.
* **No Brute-Forcing:** The "search space" is small and logical for base items, and non-existent (recipe-locked) for complex items.

### DeepSeek Response
Of course. This is a classic and challenging game design problem. Your intuition about the "deep hole" is correct—a purely combinatorial system with mostly "bust" combinations leads to player frustration, not discovery. The good news is that many games have tackled this, and there are elegant solutions.

The core principle to solve this is: **Guide the player's intuition instead of relying on random chance.** You need to create a system that feels vast and experimental but is actually built on a logical, learnable framework.

Here are several proven strategies, often used in combination.

### 1. The "Grammar" or "Cuisine" System (Top-Down Logic)

Instead of every ingredient having unique properties with every other ingredient, you create categories and rules. This is the most effective way to reduce the combinatorial explosion while preserving discovery.

*   **How it works:** Ingredients belong to categories like **Protein, Starch, Vegetable, Aromatic, Spice (Sweet), Spice (Savory), Liquid**. Recipes are then valid combinations of these categories, not specific ingredients.
    *   **Example Rule:** `Protein + Starch + Vegetable + Liquid = Stew`
    *   It doesn't matter if the player uses `Beef` or `Chicken` (both Protein), the result is a "Basic Stew." The specific ingredients might change the stew's name, visual appearance, or provide minor stat variations, but the core recipe is the same.

*   **Discovery through Sub-systems:** The real discovery comes from learning the "grammar" of the cuisine.
    *   **Example:** The player discovers that adding a `Spice (Savory)` to the stew upgrades it to "Savory Stew" with better effects. Adding a `Herb` instead creates "Herbed Stew." Now they are experimenting with rules, not just items.

*   **Real-World Example:** **The Legend of Zelda: Breath of the Wild/Tears of the Kingdom** uses this brilliantly. `Meat + Mushroom + Herb` makes a dish, and the quality of the ingredients determines the potency of the healing. The system is intuitive because it's based on categories (hearty, energizing, fiery, etc.).

### 2. The "Experiment & Research" System (Unlocking Recipes)

This system acknowledges that most random combinations fail, but makes the process of failing meaningful and progressive.

*   **How it works:**
    1.  The player tries a combination (e.g., `Meat + Herb`).
    2.  If it's invalid, it's a "failed dish," but the game logs this attempt.
    3.  After a number of failed attempts with related ingredients, the player "researches" or "discovers" a real recipe. For example, failing with `Meat + HerbA`, `Meat + HerbB`, and `Meat + Mushroom` might unlock the knowledge that "Meat can be combined with Foraged Goods," and the game then reveals the `Meat + Mushroom` recipe specifically.
    4.  An NPC, a "Recipe Book" item, or a skill tree could be the visual representation of this progress.

*   **Real-World Example:** This is similar to how research works in many strategy/crafting games like **Guild Wars 2** (for crafting disciplines) or **Stardew Valley** (to some extent, by watching Queen of Sauce or finding notes).

### 3. The "Clue-Based" or "Narrative" System

The world and its characters provide direct clues about recipes, turning discovery from a guessing game into a treasure hunt.

*   **How it works:**
    *   An old cookbook in a library might have a page missing, but the remaining text says "...and the sweetness of a Sun Berry is the only counter to the bitterness of Shadow Root."
    *   An NPC might say, "My grandmother's famous pie used the feathers of a Sky-fin to make the crust extra flaky." This is a direct hint that `Sky-fin Feather + Flour` is a valid combination.
    *   This method is perfect for the "legendary super dish," which should be a multi-step quest with clues scattered throughout the game world, not something found by brute force.

*   **Real-World Example:** **The Secret of Monkey Island** and other point-and-click adventures use this for their puzzles. The "crafting" is solving the puzzle of the clue.

### 4. The "Affinity" or "Flavor Profile" System (Bottom-Up Logic)

Each ingredient has a set of tags or numeric values (e.g., Sweet=5, Savory=2, Bitter=1, Umami=4). A recipe is valid if the combined values meet certain thresholds or create a specific profile.

*   **How it works:**
    *   The `Legendary Sweet Sauce` might require a combined `Sweetness > 15` and `Umami > 10`.
    *   The player can see the rough flavor profile of individual ingredients (e.g., "This mushroom is very earthy and bitter").
    *   This allows for massive experimentation *within constraints*. The player knows that to make a sweet dish, they need to combine their sweetest ingredients. They might discover that `Honey (Sweet=8) + Golden Fruit (Sweet=7)` works, but so does `Honey + Sugar Cane (Sweet=10)`.

*   **Real-World Example:** **Potion Craft** is the absolute master of this system. You literally navigate an alchemy map by adding ingredients with different directional properties. It's all experimentation, but it's informed and strategic.

### Synthesis: How to Apply This to Your Friend's Game

The best solution is a hybrid approach. Here’s a concrete proposal:

1.  **Implement a Category System (Strategy #1):** Define 6-8 ingredient types (Protein, Veg, Starch, Fruit, Herb, Spice, Fungi, Liquid). Basic recipes are combinations of types. This drastically reduces the initial chaos and gives the player a solid foundation. `Protein + Starch = Basic Meal`.

2.  **Add a Flavor/Stat Layer (Strategy #4):** Each ingredient also has a hidden "flavor stat" (e.g., Sweet, Salty, Spicy). The combination of types *and* the total flavor stats determine the final dish's quality and name. `Basic Meal (with high Spicy)` becomes "Spicy Stir-Fry" and grants a temporary strength buff.

3.  **Use Clues and NPCs for Advanced Recipes (Strategy #3):** The "legendary super dish" shouldn't be combinatorial at all. It should be a quest. The player finds a torn recipe scroll: "Start with the Soup of the Sun (found in a temple), then add a Feather from the Sky-Whale (a rare drop), then stir with a Diamond Spoon (a key item)." This makes it an epic achievement, not a lottery win.

4.  **Make Failure Informative (Strategy #2):** When a combination fails, the game can give feedback.
    *   "These textures don't go together..." (trying to combine two solids without a liquid).
    *   "This tastes awful and unbalanced!" (the flavor stats are wildly conflicting).
    *   This teaches the player the underlying rules without spelling them out.

By using these techniques, the game can have:
*   **A manageable number of actual recipes** (e.g., 50-100 well-designed ones).
*   **A huge space for experimentation** as players learn the "culinary grammar."
*   **A satisfying sense of discovery** as they piece together the rules and hunt for legendary recipes.
*   **A non-trivial, epic endgame** that feels earned.

The key is to move the design from "simulate all possible combinations" to "design a system that teaches the player how to be a great chef in this specific game world." The fun isn't in the million combinations; it's in mastering the two dozen rules that make those combinations make sense.
