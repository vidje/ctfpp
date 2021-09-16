# CTF++

CTF++ is a modification of the CTF ruleset to allow for a more cleaner gameplay.

Discord: [Invite](https://discord.gg/RVHpEGRrmf)

## Changes

### Spawns

The following changes were made for the fresh spawns to have less impact on the gameplay. Please keep in mind that in 4v4 the spawns don't have that big of an impact on the game, so if you're going to run 4v4 games it might be better to leave the default values.

Quake Live spawn system isn’t ideal and these changes allow for quick dealing with fresh spawns while maintaining your stack.

> Removal of starting health bonus, everyone spawns with 100hp.

This on its own is nice and fine, but I do think that spawns are too weak with these changes. To counter that, the respawn duration has been lowered by more than half.

You might not be as strong as before off a spawn, but you respawn a lot faster and can get in position to intercept (or whatever) in time.

> Minimum respawn delay set to 2000ms.

### Powerups

Powerup spawn now has a fixed time for first spawn, all other spawns are still `t + 120s`.

Random powerup spawn was always bad and never rewarded the team that set up better, instead the team that happened to be there got the powerup.

> Powerup spawn fixed at 50s.

### Weapons

Railgun ammo on pickup reduced to lessen the railfests on mid, and overall the dominance railgun has in CTF. This change applies only to the CTF++ map pool. To revert these changes, simply remove the `.ent` files from `baseq3/entities` or set `sv_altEntDir` to blank in `ctfpp.factories` or server console.

> Railgun pickup ammo set to 7.

### Map changes

**Shining Forces** used to be a very defensive map with a low scoring gameplay. The following changes were made to counter this,

Variant 1:

> Railgun now spawns at default Plasmagun location.
> 
> Plasmagun now spawns at default Railgun location.
> 
> Railgun ammo now spawns instead of rocket ammo in both bases.
> 
> Replaced Regen powerup with Quad.

Variant 2:

> Railgun now spawns at middle Shotgun location.
> 
> Shotgun now spawns at default Plasmagun location.
> 
> Plasmagun now spawns at default Railgun location.

The change in weapon placements might be completely unnecessary now that Quad is in play instead of Regen, but until it's tested we won't know.

Refer to `changelog` for all map changes.

### Map pool

The following maps were changed in mind for CTF++ gameplay:

> Bastir (`bastir`, needs testing)
> 
> Capture the Karin (`rota3ctf2`, needs testing)
>
> Infinity (`ct3ctf1`)
>
> Reflux
> 
> Shining Forces
> 
> Shot Through (`gooctf5`)

## Ideas

Suggest one on discord.
