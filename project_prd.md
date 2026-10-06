# 1v1 Sci-Fi Boss Rush

## My Idea and Who It Is For

This project is a 1v1 2D sci-fi boss rush game focused on delivering a polished, fair, and engaging boss battle.

It is designed for casual players and classmates, emphasizing clear telegraphs, tight movement, and satisfying counter-play rather than overwhelming complexity or frustration.

## What the Player or User Does

* **Title Screen:** The player starts at a clean title screen and clicks a "Start" button to begin.

* **Tutorial Area:** The player enters a safe room to learn and practice the core controls: melee hits, dashing, and deflecting.

* **Arena Transition:** Walking through a door leads the player into a small, flat arena. A brief pause occurs to give the player time to prepare.

* **Observe & React:** The player watches the wall-mounted turret boss for visual telegraphs and responds using their toolkit:
  * **Ranged Bullets:** Dodging standard projectile bursts.
  * **Electric Shock:** Timing a deflect move to send the energy shock back or neutralize it.
  * **Sweeping Laser:** Dashing through or over the beam to avoid high damage.

* **Punish & Counter:** During attack cooldowns, the player dashes close to land melee strikes.

* **Adapt:** Every 15–20 seconds, the boss shifts to the opposite wall, requiring the player to re-position and adapt until the turret is defeated.

## My First Version and Ideas for Later

### First Version (Essentials)

* **Core Player Mechanics:** 2D movement, melee attack, dash, and deflect.

* **Boss 1 (Turret Attacks & Mechanics):** A wall-mounted turret that repositions to opposite walls every 15–20 seconds. It features three specific attack patterns:
  * **Standard Ranged Bullets:**
    * *Telegraph:* The barrel flashes/pulses briefly while locking onto the player's position.
    * *Attack:* Fires a rapid sequence of standard projectiles directly at the player.
    * *Counter:* Player moves or dashes laterally to step out of the line of fire.
  * **Deflectable Electric Shock:**
    * *Telegraph:* The turret glows with electrical sparks/charging aura.
    * *Attack:* Fires a glowing shockwave or energy orb across the arena floor.
    * *Counter:* Player times their deflect button just before hit to reflect or neutralize the shockwave.
  * **Sweeping Laser:**
    * *Telegraph:* A thin red targeting line appears across the screen showing the laser path.
    * *Attack:* A heavy beam sweeps across the room from top to bottom (or along the floor).
    * *Counter:* Player uses their invincibility dash to pass cleanly through the laser beam without taking damage.

* **Flow & Environment:** Title screen with play button, tutorial area, door transition, and single 1v1 arena.

* **Design Focus:** Bug-free, consistent boss behaviors and clear telegraph timing over high feature quantity.

### Ideas for Later

* **Boss 2:** Designed and added only after Boss 1 is fully complete and polished.

* **Expanded Features:** Additional boss mechanics, complex room layouts, or advanced game modes.

## Open Questions and My Next Step

### Open Questions / Unknowns

* **Telegraph Timing:** Exactly how long should the delay be between a visual telegraph and the attack damage to ensure it feels fair?

* **Anti-Spam Logic:** How can timers or state logic be set up so the boss does not pick the same attack back-to-back?

* **Pacing Check:** Does the 15–20 second wall-switch timer feel like a true boss encounter, or does it feel too much like chasing a moving target?

* **Undecided:** The specific game engine setup and technical implementation details to be finalized with the instructor.

### Next Step

* Build a bare-bones visual prototype of a single telegraph-and-attack cycle.

* Have a classmate playtest it without instruction to see if they can naturally learn to dodge or counter the attack.

### Questions for Mr. Bird

1. What is the simplest way in our game engine to set up delays between a telegraph animation and attack damage?

2. How can I write basic logic or timers so the boss doesn't repeat the exact same attack twice in a row?