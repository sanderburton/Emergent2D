# Runs
## A first run experience
1. Wake up in the cabin, huh? What's going on. I hear clamors outside, better bring that sword
2. Step outside, see the world, maybe pan over it a bit. Minimap appears mostly dark. "Guess I better see if I can figure out where I am"
3. First enemy encountered once cabin is off screen ish. A scout, who has a sword and empty left hand. He sees you and attacks, signaling with a flare. "I've found her!!!!" shows dialogue on the bottom of the screen without interrupting gameplay
4. FRE pops up explaining combat:
    Attack with B
    Jump with A
5. The combat is not easy, new player might die to the enemy. He is kind of unpredictable, and sometimes jumps to dodge your attacks. His damage does
about as much to you, as you do to him. Maybe more. When the enemy dies, you gain a full level's worth of exp, endowed sword gains tiny amount of
exp, and a basic glorious victory reward drops, giving a small boost to attack, for example.
6. FRE explains you have leveled up, and you can choose:
    increase max health
    unlock a skill (block, sprint extra combo attack, climb walls, etc)
    heal
    perform a sacrifice (petition diety for a gift, by giving up dodge, block, max health, taking damage, combo attack, etc)
    
    First time player unlocks a given skill, FRE shows how to do it. e.g. Block with L
7. FRE explains the glorious victory gives positive effects, and prompts user to grab it. On grabbing, it explains the effect and lets you keep or leav it.
8. Continuing, on a group of two enemies appears
9. FRE explains sprint with R to try and catch them off gaurd (if you have sprint)
10. Player may die again, if not, then the player gains more exp, sword exp, and a better reward drops (need cool name). This one has a much stronger effect, with a negative effect to balance it.
11. FRE explains the better reward comes with tradeoffs
12. First time a map marker drops, FRE explains that following these impulses leads to great rewards, and great foes, and answers to questions
13. Reaching a map marker player will find semi-boss, a level up altar (grants fixed xp amount, so finding it early is still good), and a fragment of the ancient words,
revealing a story element. The first one hints that the player is the goddess of war, and the armies of men gathered to contain her
14. Gold map markers indicate the Goddess of War's location

15. First time sword levels up, FRE explains the sword lives on, and remembers the battles its fought

## Subsequent runs
1. Same general mechanics, a run scales quadratically in difficulty as you get further. Exp and levels scale quadratically as well, meaning its linear if you keep heading further.
2. Reaching the goddess is expected to take 30 minutes for the first time. Between combat and walk times. Mostly combat.
    - On average you might find 5 map markers in that time
    - On average you might defeat 50 enemy groups in that time, meaning you have 20 glorious victories, 10 map markers, 20 tradeoff rewards, and maybe 10 level ups or so
3. The usefulness of glorious victories, and other rewards, does scale with difficulty of the group. tradeoff rewards are in tiers, low, medium, and high, high being best, reserved for late game fights and semi-bosses. The tradeoff effects power isn't stronger in high tier, its just a more rare effect, like

## Randomness of rewards
Can we break the roguelike formula and not make every other roguelike? Where random synergy is what wins?

- Based on how you defeat an enemy, that's what category of reward will drop. E.g. power attack drops power rewards. Jump attack drop jump and slam rewards. Sprint attack drops sprint rewards.
- Pros: Can make a build semi how I want to for a given run, can combine reward types to make two pronged builds
- Cons: A repeatable OP strat ruins the fun

Skill tree based:
- When claiming a greater reward, you choose any skill tree perk. Other paths are still available, but you can consider your other tree as wasted if you are too broad.
- Pros: No randomness, I can build how I want like starting skyrim over every time.
- Cons: a repeatable OP strat ruins the fun

With either of these, they are no go unless there is a mechanic to incentivize build difference between runs. Something less random.

# Attempt 2 at designing this:
- Main idea is reducing boring stat bumps with more engaging mechanics, and reducing randomness so players feel in control of how they want to play. They get some ability to plan, but still need to adapt
- Base damage is balanced around not having many static "increase damage by x" effects. Instead the effects are more interesting, and the based damage feels good

- 8 - 10 skill trees, only 3 are available for any given run
    - The perks are emergent enough that any combinations from any trees can create synergies, or create anti-synergies
    - They are written such that a single perk tree maxed out is almost always weaker than investing in multiple with intelligent choices

- Instead of glorious victories being small stat bonuses, they are parts of perk points. 3 Combine into a perk point
- Better rewards are same, random powerful effects with tradeoffs. Perk points and better rewards should be roughly equal in power, so that they can adapt to each other throughout the run
- One of the long term randomness reducing rewards is ability to swap one of the trees for any other before leaving the cabin

some fun effects that could be rewards or perks:
- radius of slam attack is doubled
- knockback is increased 5x
- Enemies knocked back damage and knock back other enemies
- Can charge attacks for up to 2x damage over a quick charge up
- Enemies hit begin bleeding over time for x dps

some ideas for perk trees:
- power - knockback effects, radius increasing effects, power block effects, take/deal more damage, slower stronger hits
- cunning - enemy tricking effects, stealth (invisibility cloak?) effects, defeated enemies explode
- luck - critical strike effects, reward rarity effects
- willpower - sword throwing/retrieving effects, damage taken reduced effects,
- bloodthirst - killing an enemy provides a stacking buff that lasts 5 seconds, but your base state is weaker. Dying enemies scare nearby enemies, causing them to have a chance to flee or two freeze in fear. Bleed over time effect
- Holy (need better name) - Dealing damage may cause enemies to stop and worship you. Enemies who are worshipping and survive long enough will fight for you. Sword gets a golden trail hue. Heal upon killing a worshipping enemy. Gain an ability that calls down righteous swings from above. treated as an attack in 3 locations ahead of you