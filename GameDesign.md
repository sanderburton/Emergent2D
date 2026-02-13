# Game Design - Emergent
A 2D fantasy escape

An exercise in reducing scope

The focus of this is on extremely engaging combat. Just want to fight stuff and feel bad ass power and growth fantasy

## Mood
- High Fantasy
- Mystical, mysterious

## Gameplay - What is fun?
- Combat focused
- Emergent power fantasy
    - Start out with1v1 power fantasy that grows throughout a run
- Roguelike
- Only Sword combat
    - the idea is make one combat system, which can scale and balance much easier. Art becomes easier too, animations reduced drastically. Can really polish the combat. This makes the games combat stand out from anything else
- Cinematic camera movements and killmoves - not too difficult but lots of payoff in feel

## Combat
- Challenging combat taking a hit is devastating, single enemy can kill you especially at the beginning. Which leads to the sense of scalability and emerging.
- Unlockable attacks - tied to weapon build, unlocked separately in overworld. More powerful, but have downsides, such as cool downs or movement debuffs etc
- Blocking - you can block with sword, but it is directional (limited angle, because its strong), and some things can't be blocked. No stamina - remember the power fantasy, you feel awesome when you block
- Because blocking is strong, dodging is less so than in some games. You can dodge, but there are no i-frames. Some attacks are undodgeable, only blockable
- 1v1s in beginning, but by the mid-end of a run you are fighting entire armies. I mean hundreds of enemies. It is not fair. But you can become very op

## Progression and Why am I playing
- Enemy groups, defeating every member of group gives some small reward for the run, or a permanent reward rarely (increases for large groups or difficult enemies)
- In run rewards include:
    - Powerups with tradeoffs
    - Weak but purely positive effects
    - Occasional map markers that point to permanent unlocks or the end of the run
    - Exp
- Long term progression is based on 2 things:
    - Endowed Sword upgrades & enchantments. The sword gains whispers of battle (like exp kind of) whenever it kills something
        - Upgrade altar (think master sword in stone or excalibur) in cabin. Before leaving you must wield it (with option to customize it first)
        - Upgrades are "equippable" meaning its not permanent, you can choose per run how to pimp the sword. Hilt of power makes it slow and powerful. Graceful etchings make it faster and less damaging, imbued flames make it fiery with more damage but blocking for more than a second can hurt yourself, skills of swordstress makes it so you start with one skill already, blade of illumination lights up dark areas, etc
    - Gaining control over random rewards. You gain the ability to steer rewards towards specific builds. Some examples of this type of progression (each time you beat the goddess)
        - Instead of enemies dropping what they drop, they drop 2..x options and you pick one
        - You get 1..x rerolls per run
        - You get 1..x tears of fate per run. Crushing one lets you pick the next category of reward
        - etc

## Run mechanics
- Start with dark map, no POIs marked
- Minimap - Marked POIs will be marked by goddess's grace effects in overworld. There is a menu to expand the minimap
- World is infinite, difficulty scales with distance from cabin.
- Running straight to the goal is a terrible idea, because you will be too weak to reach it, and if you do you will be too weak to beat the goddess
- Target run length is 45min - 1hr
- Start at lvl 1 each time (like league). You gain exp by killing enemies
    - Level ups let you increase health, unlock a skill (dodge, block, extra combo attack, climb walls, etc), heal, perform a sacrifice (petition diety for a gift, by giving up dodge, block, max health, taking damage, combo attack, etc)
- The goddess gets slightly further each time you beat her (not meaningful as far as running time, maybe adds 1-2 minutes of that, but meaningful as far as difficulty zone) to a cap (when all boss rewards are unlocked)

## Setting & Story
- Environmental and isolated storytelling via text, clues, etc. Easy to implement, if the story is right it will add wonder and be a motivator to fight through it
- No need for many NPCs with this, just enemies
- Procedural world - each run feels very different than last, at the cost of more dev time on the algorithm. Need to make world have choke points to force fights, or make fighting enemies somehow desirable in a run, or both
- You wield the endowed sword (need more mystical name), a sword of diety that is bound in your death curse with you. It is actually the goddess of war's sword. She has had to forge a new weapon since afflicting you. It is slightly too big for you, which means you wield it 2h, but its not like a crazy anime sword that is annoyingly big. Its more thin in shape than most game 2h swords

You wake up in a lone fantasy cabin in a grassy field, and go out to find enemy scouts not afar off, who attack you. Through notes on their remains, and notes/"scripture" that appears in the cabin/world. You learn that you are a god or goddess of war named ____. The further you go the more enemies there are. Eventually learning that the armies of men are rallied to find and contain you. Your cabin changes location every time you die as a means of evading them. If you could only find your "insert meaningful and awestriking power source" you could ascend into the realm of diety again.

... Insert meaningful non-filler content ...

Upon completion of the first run, you learn that the actual goddess of war is framing you, to escape the same fate. You are only human, with an unbreakable blight of undeath. She will never free you because then she will be relegated back to the same fate. The curse cannot be broken, only transferred. The goddess cannot die, unless she has the curse, in which case she will become the one in the cabin. If you don't have the curse, and you die, you die forever... What a conundrum

Option for permadeath, or a simple last minute transfer that makes it impossible to die forever

## Art
- 2D pixel style, more high res pixel art than low res, because I prefer the details
- Music - a few basic things, calm, and in combat probably
- Sound - just required things like clashes, sheathes, footsteps, some voice sounds like grunts and crowd sounds

Weapon (sword) creator. This is the larger progression. Each run can unlock materials, lengths, handles, blade shapes, sheathes, engravings (procedural? O_O). Much easier than character creator. This type of art is much easier too.



## Why it won't have:

- NPC characters - too much art, dialogue system, facial animation, sounds, clothes, AI
- Character customization - Too much effort to make it good. Need dozens of hairstyles, morph weights, colors
- Inventory - the focus is combat, not collecting things. Reduced UI needed Anything that is to be collected must be held and toggled. We lose stuff, but also feels more adventurous. E.G pick up a sword, you may not be able to find the old one again.
- Magic in left hand - more animations and vfx, the spirit of the game is raw
- Multiplayer - needs a large player base. And tons of work
- Player Jumping - 4 more directional attacks, additional game balance and state machine comolexities. Some attack animations may be airborne though

Weapons other than single sword - would be awesome, but art + animations hold it back. Using only a one handed sword allows for unique interactions with off hands, such as grabs

- Multiple player outfits - again would be awesome, but it doesn't add much in terms of gameplay fun. This allows for a really awesome default outfit that doesn't feel boring
- Stamina - no need, extra design and programming
- Projectiles - no need for enemy animations for bows, magic, etc. maybe some attacks will send out a basic one, but it won't be something that goes far enough for him to matter much
