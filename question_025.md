## Question 025

Question's subreddit link: https://www.reddit.com/r/gamedesign/comments/1n1kmt8/how_do_people_make_so_many_items

Date: 2025-08-27

## Problem Description
How do people make so many items? — A lot of games, at some point, need a big list of items. Especially if you're making something with roguelike elements, chances are the items end up being the thing that make the game feel alive.
Therefore, it'd make sense you'd want to have a lot of items. Like, at least 100. Some could be bought, some would drop from enemies, and some would be looted from special events. Making up enemy or event related items, while tough, is a little bit easier: just connect the item to one of the enemy's mechanics or concept and you're done.
But with stores, I feel like i have nothing. There's no restriction, nor is there that big of a theme. That's kind of the point, a store is meant to sell the "generic" items. But now, how do I even come up with a bunch of generic items with no deep theme behind them? How do I come up with their mechanics? How do I make sure they feel unique and distinct, while still having enough ideas to make a big list out of it?

Edit: Maybe I should've been more detailed and specific to my game's struggle, I'll accept that. I tried to make this wide and abstract assuming that the solutions would be similar for most games, but it seems like I was wrong given most of the comments are asking for clarification lol.

My game is a card roguelike similar to Balatro, based on a real card game and adapted into a videogame. To make the game more fun (as with balatro), I'm trying to brainstorm a bunch of items that would work a bit like Jokers (aka powerful, build-defining items that feel very cool to find). But I'm stuck in the sense that, for the items that aren't tied to any specific story aspect (I do have a bigger story focus than Balatro), it's proving tough to get inspiration for the at least 15 items I need. I figured that many other games probably run into a similar problem (shooters need unique weapons, platformers and metroidvanias need unique buffs and weapons, etc), so I tried to keep it general for this post

## Best Human-rated Answer
That depends a lot on your specific game mechanics.

As a general rule, I would go through every mechanic you have -with a high degree of detail- and think of ways you can interact with it.

For instance, say you have an armor mechsnic that reduces damage taken.

You can have: Set armor to specific value Increase armor (flat amount) Increase armor (percentage) Decrease armor (flat amount) Decrease armor (percentage) Penetratr armor (percentage) Penetrate armor (flat amount) Penetrate armor (threshold) Break armor Do dps to armor Repair armor Steal armor

Then you can combine a few of these on one item, across different categories. You can also have modifiers and conditions, like

Only active at max health Only active at low health Only active for a limited duration Only active after being hit Only active after using ability

You can combine all of these in a system to create random loot, or you can use this as a framework to help you identify possibilities for custom handmade items.

## LLM Responses

### ChatGPT-5 Response
That’s a fantastic and very real design struggle — nearly every developer who’s made a roguelike, card game, or loot-heavy game runs into the “content generation wall.” The good news is that there are several proven *design approaches* and *creative systems* that can help you build a large, interesting item list without burning out or resorting to pure randomness.

Below are several ways to tackle this — both general design frameworks and some that fit your **card roguelike / Balatro-like** game specifically.

---

## 🧠 1. Start with Systems, Not Items

Instead of brainstorming 100 items directly, brainstorm **mechanical levers** — the categories of things that can be modified.

For a card roguelike, that might include:

* 🔹 Hand size (e.g., draw +1 card)
* 🔹 Card value multipliers (e.g., doubles points for Hearts)
* 🔹 Synergies (e.g., extra reward when playing pairs, flushes, etc.)
* 🔹 Resource modifiers (e.g., more money per round, or cheaper rerolls)
* 🔹 Deck manipulation (e.g., discard effects, copy cards, burn cards)
* 🔹 Event interactions (e.g., more likely to get rare cards, safer from bad events)

Once you’ve identified 10–15 levers, you can mix and match them to generate many unique-sounding items.

> Example:
>
> * “Lucky Coin” – +25% chance to draw a Heart card.
> * “Dealer’s Smile” – Start each hand with +1 card drawn.
> * “Twisted Fate” – Flushes also count as Straights.

Each uses the same lever (probability, draw size, or combination rule), but feels distinct.

---

## 🧩 2. Use **Combinatorial Design**

Take two lists and combine them algorithmically or manually.
For example:

**List A (mechanical effect):**

* Increases X
* Decreases Y
* Converts A into B
* Adds condition on Z
* Triggers bonus under N condition

**List B (theme hook):**

* Card suits (Hearts, Spades, etc.)
* Card ranks (Face cards, Jokers, etc.)
* Casino tropes (Dealers, Chips, Tables, Smoke, Drinks)
* Emotions (Greed, Luck, Deception, Hope)
* Archetypes (Magician, Trickster, Gambler, Banker)

Combine them randomly, then tweak.

> Example results:
>
> * “Greedy Joker” — gain +1 multiplier per $100 earned.
> * “Smoky Room” — doubles the score of flushes but hides next round’s cards.
> * “Magician’s Coin” — converts Clubs into random suits each hand.

You can easily generate 100+ drafts this way — and keep the best 20%.

---

## ⚙️ 3. Think in **Item Archetypes**

Every roguelike item list can be categorized by *what it asks the player to do*.
Create one or two items in each archetype:

| Archetype              | Example effect             | In a card roguelike                                   |
| ---------------------- | -------------------------- | ----------------------------------------------------- |
| **Multiplier**         | Boost an existing strategy | “Doubles points for Straights.”                       |
| **Transformer**        | Change how something works | “Hearts act as wildcards.”                            |
| **Economy**            | Modify meta-resource       | “+1 money for each discard.”                          |
| **Risk/Reward**        | Big bonuses with drawbacks | “Triple your score but halve HP.”                     |
| **Combo Engine**       | Encourage synergy          | “Every time you play a pair, gain +1 draw next turn.” |
| **Chaos / Randomness** | Add unpredictability       | “Each hand, a random card suit gets +100% value.”     |

You’ll notice Balatro and other deckbuilders follow these patterns closely.

---

## 🧩 4. Create “Item Families”

Group items by subtle variations to make bulk creation easier:

* “Royal Series”: King’s Charm, Queen’s Wit, Jack’s Blade — all give bonuses for their respective face cards.
* “Suit Relics”: Heartstone, Spade Idol, Club Totem, Diamond Chalice — each buffs a suit.
* “Dealer Tools”: Card Shuffler, Weighted Dice, Loaded Chip — modify random mechanics.

This keeps items feeling *coherent*, helps with naming/theming, and gives players collectible goals.

---

## 🎲 5. Procedural or Modular Item Generation

If you want hundreds of items without manually designing them all:

* Define *prefixes* (Lucky, Cursed, Golden, Rusty)
* Define *base types* (Coin, Card, Deck, Chip)
* Define *suffixes* (of Fortune, of Pain, of Doubt)

Combine them to generate interesting procedural items, with a few handcrafted “specials.”

> “Golden Deck of Fortune” = +25% chance for rare draws.
> “Cursed Coin of Doubt” = doubles score, halves payout.

This technique works great if you want replayability and “loot flavor.”

---

## 🧭 6. Pull Inspiration from the Metaphor of Gambling

Your game’s theme gives you a *goldmine* of metaphors:

* **Luck** → random buffs, probability shifts
* **Greed** → gain more now, lose more later
* **Bluffing** → hidden information, risk for reward
* **Addiction** → stacking bonuses that grow dangerous
* **Fate / Fortune** → rerolls, prophecy-like effects

Each theme can inspire entire subsets of items.
For instance, “Fate” items might all involve predicting or pre-determining outcomes.

---

## 🧩 7. Steal Structure, Not Content

Study other games’ *structure* of items (not their names or effects).
Examples:

* **Balatro:** synergies + simple math tweaks (×2, +10%, etc.)
* **Slay the Spire:** each relic changes a core rule slightly.
* **Hades:** boons combine thematic flavor + mechanical impact.
* **Binding of Isaac:** items alter base systems, often visually reflected.

Make a chart of *what system each item modifies* in those games — then see what’s missing in yours.

---

## 🧠 8. “Negative Space” Design Prompt

Ask: *What’s missing or underused in my game’s system?*
Items that fill gaps tend to feel unique.

Example:

> If players never care about discards → make an item that rewards discards.
> If everyone ignores low cards → make one that boosts low-card combos.

These items arise naturally from the game’s current balance rather than from random invention.

---

## ⚒️ 9. Use a Generative Brainstorm Workflow

Here’s a lightweight production loop for your 15–100 items:

1. List your 10–15 mechanical levers.
2. Generate combinations with thematic hooks (as above).
3. Write one-line prototypes (“When X, gain Y.”).
4. Quickly test or simulate a few.
5. Keep the ones that feel fun, rename them with flair, and discard the rest.

You don’t need to design them all “correctly” — just make a few categories of fun discoveries.

---

## 💡 10. Quick Creative Prompts (for your case)

Try rolling dice or using random seeds with these prompts:

* “What if a card rule was reversed?”
* “What if an emotion or casino vice became a mechanic?”
* “What if this item punished the player slightly, but made them feel clever?”
* “What if it rewarded a bad hand instead of a good one?”
* “What if it turned a low-value card into a combo enabler?”

Even five minutes with prompts like that can give you a dozen solid concepts.

---

Would you like me to show you an **example brainstorming table** (e.g., 20 new Balatro-style item ideas, categorized by archetype)?
That could give you a jumpstart to see how these methods look in practice.

### Gemini Response
Here are several strategies game developers use to brainstorm and create a large list of items, especially for a *Balatro*-like roguelike.

The key is to **stop thinking of them as "generic."** In a game like *Balatro*, the "store" items (Jokers) are the *opposite* of generic. They are the core mechanical engines of the game. Their "theme" isn't story-based; their theme is *mechanics*. They are tools that manipulate the game's core rules.

Since your game is a card roguelike, your items should be all about **interacting with the core rules and systems of your card game.**

Here are some structured methods to brainstorm your 15+ items.

### 1. The "Deconstruct Your Core" Method

This is the most powerful method, and it's exactly what *Balatro* does. List every single noun, verb, and system in your game. Then, create items that interact with each one.

Let's use Poker (like *Balatro*) as an example.

**Your Game's Nouns (The "Things"):**
* **Cards:** The individual units.
* **Ranks:** (Ace, 2, 3... King)
* **Suits:** (Hearts, Spades...)
* **Hands:** (Pair, Straight, Flush...)
* **Deck:** The pile you draw from.
* **Discard Pile:** The pile you discard to.
* **Score/Chips:** The "base" points.
* **Multiplier:** The... multiplier.
* **Money:** The meta-currency.
* **Shop:** The place you buy things.

**Your Game's Verbs (The "Actions"):**
* **Play (a card):**
* **Hold (a card):**
* **Discard (a card):**
* **Draw (a card):**
* **Score (a hand):**
* **Buy (an item):**
* **Sell (an item):**
* **Reroll (the shop):**

Now, for each noun and verb, brainstorm items that **modify, reward, or break** it.

* **Interacting with Ranks:**
    * "All 7s are considered Wild."
    * "Face cards (J, Q, K) give +X Mult when scored."
    * "Aces score 3x their normal chip value."
* **Interacting with Suits:**
    * "All Hearts count as Spades (helps build flushes)."
    * "First Heart played in a hand gives +$1."
    * "+4 Mult for each Diamond in your scored hand."
* **Interacting with Hand Types:**
    * "Playing a Pair also gives you 100 Chips."
    * "Straights can now have one 'gap' (e.g., 2, 3, 5, 6, 7)."
    * "Flushes are now easier to get (e.g., only need 4 cards)."
* **Interacting with Verbs (Play/Discard):**
    * "The first card you discard each round gives +5 Mult."
    * "Playing your last card in hand gives a 2x Mult."
    * "For every card you *don't* play (i.e., hold over), gain $1."
* **Interacting with Meta-Systems (Money/Shop):**
    * "Gain 5% interest on your money at the end of each round."
    * "Shop rerolls are free."
    * "The first item you buy each round is 50% off."

You can see how this method alone can generate 100+ ideas.

### 2. The "Archetype" Method

Instead of 15 unique items, think of 3-4 **build archetypes** you want to support. Then, design 4-5 items for each archetype. This naturally creates the "build-defining" feel you want.

* **Archetype 1: The "Spades" Build**
    * Item 1: "+4 Mult for each Spade played."
    * Item 2: "All Clubs are considered Spades."
    * Item 3: "If you play a 5-card Spades-only Flush, re-trigger all cards."
* **Archetype 2: The "Face Card" Build**
    * Item 1: "Face Cards (J, Q, K) give +50 Chips."
    * Item 2: "Aces are considered Face Cards."
    * Item 3: "Playing a hand with 3 or more Face Cards gives a 2x Mult."
* **Archetype 3: The "Discard" Build**
    * Item 1: "Get +1 Discard per round."
    * Item 2: "+1 Mult for every 2 cards discarded this run (caps at +50)."
    * Item 3: "Discarding a card has a 25% chance to give you $1."

### 3. The "Flavor First" Method

Your store doesn't have a "deep theme"? **Give it one.** The theme doesn't have to be tied to the story. The theme can be the shop itself. This is purely for inspiration.

* **Theme: The Gambler's Den.** Items are about risk/reward.
    * **"Loaded Die":** 50% chance to 3x your score, 50% chance to score 0.
    * **"Marked Deck":** You can see the top card of the deck.
    * **"Backroom Deal":** Gain $25, but your next two 'blinds' (bosses) are 2x as hard.
* **Theme: The Magician's Shop.** Items are about illusion and subversion.
    * **"Sleight of Hand":** The first card you play returns to your hand.
    * **"Smoke & Mirrors":** All cards in your hand appear as a different, random card until played. Get +X Mult for playing with this active.
    * **"Misdirection":** The highest-scoring hand type (e.g., Straight Flush) now scores the lowest, and the lowest (e.g., High Card) scores the highest.
* **Theme: The Accountant's Office.** Items are about math, scaling, and economy.
    * **"Compound Interest":** At the end of a round, gain $1 for every $20 you have.
    * **"Ledger":** +1 Chip for every $1 you have.
    * **"Tax Man":** At the start of a round, lose $3, but gain +1 Mult for the round.

### 4. The "Modifier Stack" Method (Simple -> Complex)

Create your items by stacking simple modifiers. This makes generation easy and creates items of varying complexity.

1.  **Start with a Simple Stat:** `+X Chips`, `+X Mult`, `+X Money`.
    * *Example:* "Item: Strong Arm" -> `+50 Chips`.
2.  **Add a Simple Condition:** `If...`, `When...`, `For every...`
    * *Example:* "Item: Specialist" -> `+100 Chips` **if** `your hand is a Pair`.
3.  **Add a Scaler:** `...per X`.
    * *Example:* "Item: Collector" -> `+1 Mult` **for every** `item you own`.
4.  **Add a Rule-Break:** `Ignores...`, `Allows...`, `Counts as...`
    * *Example:* "Item: Master Key" -> "Straights **no longer need** to be in sequence."

### A Concrete Action Plan for Your 15 Items

Use this formula to get your 15 items quickly.

* **5 "Simple Stat" Items:**
    * 1.  `+X Chips`
    * 2.  `+X Mult`
    * 3.  `X Mult` (multiplicative, not additive)
    * 4.  `+$X per round`
    * 5.  `+1 Hand Size` or `+1 Discard`
* **5 "Conditional" Items:** (These reward specific playstyles)
    * 6.  "If you play a [Specific Suit], get +X Mult."
    * 7.  "If you play a [Specific Rank], get +X Chips."
    * 8.  "If you play a [Specific Hand, e.g., Two Pair], get $X."
    * 9.  "If you *don't* use any discards, get a 2x Mult."
    * 10. "The *last* hand of the round gets +X Mult."
* **5 "Build-Defining / Rule-Breaking" Items:** (The exciting ones)
    * 11. "All [Rank, e.g., 2s] are Wild."
    * 12. "All [Suit, e.g., Hearts] count as [Suit, e.g., Spades]."
    * 13. "You can play 6 cards in a hand instead of 5."
    * 14. "Money now gives you +Mult (e.g., +1 Mult per $20), but you no longer earn interest."
    * 15. "Your score is squared, but your hand size is 1." (A weird, risky item).

This structure gives you a solid base of simple, understandable items while also providing the foundation for the "build-defining" items you're looking for. Good luck!

### DeepSeek Response
Of course! This is a classic game design hurdle. Moving from a handful of core ideas to a large, robust list of content is where the real work begins. The shift in your edit is very helpful—designing "build-defining" items is a different challenge than designing "generic" ones.

Here are several strategies to break through that creative block and generate a substantial list of unique, powerful items.

### Strategy 1: Systematize Your Creativity (The "Generator" Approach)

Instead of trying to dream up items from nothing, create a system that generates ideas for you. This is the most effective way to ensure variety and cover all the mechanical bases.

**The Core Formula: "Trigger + Effect + Modifier"**

Break down an item into its components and mix and match.

*   **Trigger:** When does the item's effect happen?
    *   On playing a Spade/Heart/Diamond/Club.
    *   On scoring a Straight, Flush, etc.
    *   On discarding.
    *   At the start/end of a round.
    *   When your score is a multiple of X.
    *   When you have exactly Y chips.
*   **Effect:** What does it do?
    *   Add Chips.
    *   Add Mult.
    *   Add a multiplier to a specific suit/rank.
    *   Destroy/Transform other cards in your hand.
    *   Generate gold.
    *   Create a copy of a played card.
    *   Retrigger another item's effect.
*   **Modifier:** What makes it special or conditional?
    *   The effect is doubled if you have no other items.
    *   The effect scales with the number of discards left.
    *   It has a negative effect that you must build around (e.g., "Gives +50 Mult, but you can no longer play Heart cards").

**Example:** Let's combine these.
*   Trigger (On playing a Flush) + Effect (Add Mult) + Modifier (equal to the number of Discards remaining) = **"Gambler's Resolve"**: *When you play a Flush, gain +2 Mult for each Discard remaining.*
*   Trigger (On Discarding) + Effect (Add Chips) + Modifier (but destroy a random Joker/Item) = **"Volatile Investment"**: *When you discard, gain 100 Chips. There is a 25% chance to destroy a random owned Item.*

By creating lists for each column and rolling the dice, you can generate 50+ item concepts in minutes. Many will be bad, but some will be gems, and they'll all be starting points.

### Strategy 2: Thematic Archetypes & "Build-Around" Items

Since your items are build-defining, design them to enable or enhance specific playstyles. Think of your game's core mechanics and create an archetype for each.

*   **The "High-Roller":** Items that reward risk and big numbers.
    *   **"All or Nothing"**: *Double your total score, but if you don't meet the blind's target score, you lose all money.*
    *   **"Ante Up"**: *Gain +10 Mult for every 10 gold you have. Lose 10 gold at the end of each round.*
*   **The "Combo Master":** Items that chain actions together.
    *   **"Chain Reaction"**: *After you play a hand, if you played the same hand type as the previous round, trigger its effects again at 50% power.*
    *   **"Echo Chamber"**: *The first card you play each round is played twice.*
*   **The "Control Freak":** Items that manipulate your deck and hand.
    *   **"Pocket Dimension"**: *You may hold an extra card in your hand at the end of the round.*
    *   **"The Curator"**: *At the start of the round, you may banish a card from your hand. For the rest of the run, cards of that rank are worth +50 Chips.*
*   **The "Deviant":** Items that break the fundamental rules of the game.
    *   **"Rule of Six"**: *You may now form straights that wrap from King to Ace to 2. (A,2,3,4,5 is a straight, and so is Q,K,A,2,3).*
    *   **"Wild Card"**: *Once per round, you may designate one card in your hand as any suit.*

### Strategy 3: Iterate on Existing Concepts (The "Upgrade" Path)

Don't just think of items in isolation. Think of them in families or tiers.

*   **Linear Upgrades:** Take a simple idea and make a more powerful, often more conditional, version.
    *   Basic: **"Steel Dagger"**: *Spade cards give +10 Chips.*
    *   Advanced: **"Assassin's Blade"**: *Spade cards give +30 Chips, but you cannot play Heart cards.*
    *   Legendary: **"Kingslayer"**: *Spade cards give +100 Chips. If your hand contains a King, Spade cards give +Mult instead.*
*   **Lateral Upgrades:** Create items that are side-grades or offer a different flavor of the same core concept.
    *   Item A: **"Lucky Coin"**: *Gain $1 at the end of every round.*
    *   Item B: **"Piggy Bank"**: *Gain $1 for every 50 Chips you score in a round.*
    *   Item C: **"Divining Rod"**: *When you skip a shop, gain $5.*

### Strategy 4: Inject Narrative and "Flavor" (Even for "Generic" Stores)

Even in an abstract game like Balatro, the item names and flavor text do a lot of work. Your "generic" store can have a personality. Give your items a "flavor" that inspires the mechanic.

*   **"The Pawnbroker's" Section:** Items about small, consistent gains.
    *   **"Broken Watch"**: *Gain +3 Mult at the start of the 3rd round of an ante.*
    *   **"Tarnished Locket"**: *The first Heart card you play each round gives +20 Chips.*
*   **"The Alchemist's" Section:** Items that transform or consume things.
    *   **"Philosopher's Stone"**: *You may sell a card from your hand for triple its sell value.*
    *   **"Elixir of Fate"**: *Once per run, you may re-roll a boss blind.*
*   **"The Curio Shop" Section:** Weird, unpredictable items with high potential.
    *   **"Cursed Monkey's Paw"**: *Double the effects of all your positive Jokers, but also double the effects of all your negative ones.*
    *   **"Deck of Many Things"**: *At the start of the shop, destroy half your items at random. Create a copy of the remaining ones.*

### Putting It All Together: Your Action Plan

1.  **Define Your Archetypes:** List 5-7 core playstyles in your game (e.g., Chip Stacker, Multiplier Builder, Discard Engine, Hand Manipulator, etc.).
2.  **Build the Generator:** Create your lists of Triggers, Effects, and Modifiers.
3.  **Brainstorm in Batches:**
    *   For each Archetype, use the generator to create 3-5 item concepts.
    *   For the "store flavor," pick 3 themes (like Pawnbroker, Alchemist, Curio) and generate 2-3 items for each.
    *   Look at your favorite items from other games and ask, "What is the *opposite* of this item?" or "What if this item was applied to a different trigger?"
4.  **Don't Be Afraid to Cut and Combine:** You only need 15 for now. Generate 30-40 ideas, then pick the 15 that feel the most distinct, fun, and supportive of your desired game balance. A "meh" idea combined with another "meh" idea can often create a fantastic, complex one.

The key is to stop asking "What's a cool item?" and start asking **"What problem does this item solve?"** or **"What fantasy does this item enable?"** By systematizing the process, you move from being a pure creator to a clever curator, which is far more sustainable for filling a large game with content.
