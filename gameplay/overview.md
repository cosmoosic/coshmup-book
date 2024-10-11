## Gameplay

Before diving into shmup-specific resources, here are some general references on game design.

The first is ABA games [Manifesto of Small Games](https://abagames.github.io/joys-of-small-game-development-en/).
It starts with constraints and ideas, and covers aspects such as juiciness (a concept of effects that make things "feel good"), as well as automation and tool development.
It's a must read!

There is also Masahiro Sakurai's Youtube channel, a good starting point being [Game essence in shooting games](https://www.youtube.com/watch?v=iN3IyqPjLkc).
This mentions how to give player agency to choose between (boring) safe actions, and high risk high reward ones, creating a natural incentive to progress.

### Story-driven ideas

Because Cosmoose is characterized by its gang of heroes, the primary choice for defining game mechanic is to have each ship implement a definite game archetype (slow tank, nimble fly, etc.) with unique power attributes, and a ship-switching mechanic.
The big slowdown could be linked to the ship switch, being tied to a simple cooldown mechanism.

A quick brainstorming gives the following ships:
- Florrie: fast and light, with hacking abilities
- Ru D: melee tools, all-rounder
- 7Cs: shield, absorption powers
- Wool: slow tank, grappling hook
- P. June: excentric (random), bomb based

Universal mechanics:
- shooting
- dash?
- bombs?

### Main genre

Do we go for the traditional shmup way, or try for a hybrid?

An interesting discussion of hybrid design by ABA games:
https://dev.to/abagames/shooting-games-shoot-and-do-something-33cd

It takes the approach that would consider Ikaruga to be a hybrid rather than a shmup, as in "shoot and do something" are hybrids. 

This reference is particularly interesting for its list of hybrids:
https://racketboy.com/retro/shmups-101-a-beginners-guide-to-2d-shooters

### Rhythm

Another obvious topic is to introduce rhythm mechanics.
Games that do it in otherwise classical game designs are:
- [Bullets Per Minute](https://store.steampowered.com/app/1286350/BPM_BULLETS_PER_MINUTE/), an FPS
- [Robobeat](https://store.steampowered.com/app/1456760/ROBOBEAT/), another FPS
- [Crypt of the necrodancer](https://store.steampowered.com/app/247080/Crypt_of_the_NecroDancer/), a roguelike

### In-depth tutorial

The long-running series by Layzy Devs Academy, [Shmup Tutorial](https://www.youtube.com/watch?v=81WM_cjp9fo&list=PLea8cjCua_P3Sfq4XJqNVbd1vsWnh7LZd&pp=iAQB).
Note that this is in Pico-8, while our current engine choice is Bevy.

### Discussions

Best design: https://www.youtube.com/watch?v=YR5O5KS9RKI

Avoid gimmicks: https://shmups.system11.org/viewtopic.php?t=43153

Boghog on the design of Gunvein [video interview](https://www.youtube.com/watch?v=1nZJMozJQI8&list=PLea8cjCua_P38GVDI3zb-y-D2SZFmlU2L), in a playlist with other interesting creators.


### Checklist

https://shmups.wiki/library/Category:Game_mechanics

These might deserve their own section.
Some of the features that to be implemented (or at least considered):
- [ ] hitboxes
- [ ] hitstun
- [ ] hitstop
- [ ] wall stick
- [ ] wall bounce
- [ ] input buffer
- [ ] scoring system
- [ ] meter-based power ups
- [ ] screen population slowdown
- [ ] point blank
- [ ] graze
- [ ] chains
- [ ] rhythm
- [ ] reflex
- [ ] memory
- [ ] tactics
- [ ] polarity
- [ ] visual inertia (with infinite acceleration)
- [ ] physics
- [ ] puzzle
