# CTF++

CTF++ is a modification of the CTF ruleset to allow for a more cleaner gameplay.

Discord: [Invite](https://discord.gg/5VM73pwrxA)

Server: [51.75.77.17:27960 (DE)](steam://connect/51.75.77.17:27960/)

## Changes

### Spawns

The following changes were made for the fresh spawns to have less impact on the gameplay. Please keep in mind that in 4v4 the spawns don't have that big of an impact on the game, so if you're going to run 4v4 games it might be better to leave the default values.

Quake Live spawn system isn’t ideal and these changes allow for quick dealing with fresh spawns while maintaining your stack.

> Removal of starting health bonus, everyone spawns with 100hp.
> Machinegun damage reduced to 4 per bullet.

This on its own is nice and fine, but I do think that spawns are too weak with these changes. To counter that, the respawn duration has been lowered by more than half.

You might not be as strong as before off a spawn, but you respawn a lot faster and can get in position to intercept (or whatever) in time.

> Minimum respawn delay set to 1000ms.

### Powerups

Powerup spawn now has a fixed time for first spawn, all other spawns are still `t + 120s`.

Random powerup spawn was always bad and never rewarded the team that set up better, instead the team that happened to be there got the powerup.

> Powerup spawn fixed at 50s.

### Weapons

Railgun ammo on pickup reduced to lessen the railfests on mid, and overall the dominance railgun has in CTF. This change applies to the following maps: `courtyard`, `futurecrossings`, `ironworks`, `japanesecastles`, `pillbox`, `shiningforces`, `siberia`, `spidercrossings`, `stonekeep`, `thedukesgarden` and `troubledwaters`. To revert these changes, simply remove the `.ent` files from `baseq3/entities` or set `sv_altEntDir` to blank in `ctfpp.factories` or server console.

> Railgun pickup ammo set to 7.

### Map changes

Shining Forces used to be a very defensive map with a low scoring gameplay. The following changes were made to counter this,

> Railgun now spawns at defaultPlasmagun location.
> 
> Plasmagun now spawns at default Lightning Gun location.
> 
> Lightning Gun now spawns at default Railgun location.
> 
> Replaced Regen powerup with Quad.

The change in weapon placements might be completely unnecessary now that Quad is in play instead of Regen, but until it's tested we won't know.

## Ideas

Increase the minimum respawn time by a bit, as the general idea behind making fresh spawns weaker was for them to not obstruct flag runs and attackers off the spawn as much as they did before.

Set the powerup instead of fixed spawn to 52.5 +- 7.5 (random spawn between 45-60s).
