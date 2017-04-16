<img src="https://github.com/elytra/GlassHearts/raw/1.11.2/doc/logo.png" align="right" width="180px"/>

# Glass Hearts
*A novel and balanced way to increase your max health.*

Glass Hearts adds five things:

 * An enchantment, called Sapping
 * A fluid, called Lifeforce
 * A block, called a Glass Heart
 * A few gems, to supplement the ones in vanilla
 * A completely overhauled health bar renderer, with sub-half-heart accuracy

Sapping allows you to fill bottles with Lifeforce by killing mobs. By default,
you cannot gain Lifeforce from undead mobs, and there's a config option to only
allow getting it from players.

Glass Hearts allow you to increase your max health, *but don't refill on their
own*. You can adorn these hearts with 1 gem to give special effects, dependent
on the gem.

Automated piping can refill Glass Hearts, but only so fast. In addition,
multiple players can share a Glass Heart.

But beware; Glass Hearts are targetted by creepers (configurable), and can be
difficult to refill! In a PvP setting, enemy players might break it instead!

Glass Hearts do not chunkload and instead store their data out-of-band in a
global map. This means you can utilize a Glass Heart in an unloaded chunk
without worrying about it, unless you have an automated refill system.

Not even Regeneration will work on a Glass Heart, nor healing offered by other
mods.

This mod idea was originally intended for a factions PvP server, but I'm
releasing it as an open-source Forge mod because I can't just continue to not
implement this idea. I hope you enjoy!

*In accordance with the MIT License, this mod may be used in any modpacks on
any platform for any purpose. You can even charge for it, though that's against
Mojang's EULA.*

This will probably evolve into a lifeforce alchemy mod! Stay tuned.