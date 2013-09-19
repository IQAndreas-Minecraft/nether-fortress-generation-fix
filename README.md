
If you are like me, you did not create an entirely new save when MineCraft 1.6.2 came along, but where instead content with your old world. Alas, you may have noticed that certain parts of your Nether Fortresses are not spawning mobs such as Withers or Blazes like they used to.

#### Why?

Because Minecraft uses seeded random numbers for structure generation, structures will always look the same when generated in two different worlds, as long as the seed in both worlds are the same. But every time the "structure generation" code in MineCraft changes, the location, size, or even the existence of a structure may change. 

Structure generation hasn't changed much since before 1.5.2, so up until now, your nether fortresses, strongholds, and villages have been farily consistent beetween Minecraft versions. But in 1.5.2, random chests were able to spawn in nether fortresses, which required changes to be made in the structure generation. This means that fortresses may start out looking like they did in a previous version, but once they hit a component containing a chest, they diverge and generate differently.

**Great news!** Mojang has added code in MineCraft 1.6.3 which "locks" these structures in place, so even if the structure generation code should change, your old structures will still function as expected.

**The bad news?** These structures will be locked in place as they were in MineCraft 1.6.3, so if your structures were generated before that, you are stuck with parts of your fortresses being "inactive", and meanwhile Nether Fortress mobs may start spawning in regions outside of the fortress.

#### That's where this patch comes in

This patch makes sure the bounding boxes look just like they did before 1.6.2.

Currently, those changes are **not permanent**, and fortresses revert back to their previous state if Minecraft is updated, or for any other reason the mod is uninstalled. However, once Minecraft 1.6.3 is available, I will mod 

If you would like to view these bounding boxes and compare the _before_ and _after_ versions, there is [a great mod which lets you view them](http://www.minecraftforum.net/topic/1538820-bounding-box-outline/), or you can use a "slimmed down" version of that mod in [Kabo PC's Show Monsters mod](http://www.minecraftforum.net/topic/1544812-162-showmonsters/). When the mod is installed, activate it with `F3+N`.

#### Installation

Installation is just like any other mod. 

You can either do it manually ([Xisumavoid created a tutorial on this](http://www.youtube.com/watch?v=73Zops0kgOM)), or with a tool such as [Magic Launcher](http://www.minecraftforum.net/topic/939149-launcher-magic-launcher-117-mods-options-profiles-news/).

This mod will not make any permanent changes to your world, and can be un-installed and re-installed without affecting or corrupting your save.

#### Extra details

If you go far enough away so as to generate new terrain, new Fortresses will spawn with chests, but will look slightly different than if they had been generated in 1.6.2 (this does not affect the spawning areas). New chests will not appear in existing fortresses.

According to my tests, other structures, such as Mineshafts, Witch Huts, and Villages, were not affected by changes in 1.5.2, only Nether Fortresses. But if someone needs a fix which covers structure genration before that, let me know and I will generate a version accordingly.



