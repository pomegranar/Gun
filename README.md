# 🔫 Anar's fabulous fictitious gun generator

Guns and gaming go hand in hand to create the extremely popular genre of shooter games. Developers work day and night to perfect the feel, realism, and fun-ness of their guns. This project aims to discover a way to generatively create new and unique guns through parametric design.

![example](guns.png)

## These parameters include:

- Barrel length
- Barrel height
- Weight (affects rotation speed and recoil)
- Body silhouette
- Gun body colors
- Magazine size
- Firing mode (single-fire, burst, shotgun, automatic, auto shotgun)
- Fire rate
- Bullet color
- Bullet trajectory
- Bullet speed (proportional to barrel length)
- Bullet spread (for shotguns)
- Accuracy
- Single/burst fire cooldown time
- Recoil intensity (affected by weight)

## Parameter definition

The above parameters all depend on the seed, which is determined by converting the gun's name (a string) to a numerical value, so you can reproduce the same gun from its name alone.

# How to run

## For mac users:

1. Download the latest `.dmg` from the releases page on the right. 
2. Open `GunGame-Installer.dmg` and drag gun.app into Applications. 
3. Open the game from your applications menu. 

> If it doesn't work, download Java 17 or higher.

## For any other case:

1. Download Processing.
2. Clone this repo.
3. Run gun.pde in Processing.

# How to play

1. Use WASD to move your gun.
2. Use Mouse1 to shoot the balloons.
3. Hit R to reload ammo (you start with 3 magazines, so don't waste it all).
4. Clearing all balloons will progress you to the next level, with tougher balloons (+1 magazine for clearing a round, with 3 mags max).
5. Game ends if you run out of ammo.
6. Press Escape to quit.
