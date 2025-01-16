# Bestowal

The (probably great) spell to put a curse on something (any non-blacklisted living entity) takes a pattern list, an itemstack entity containing raw media items, and the target entity. Once the curse is applied, its pattern list is executed once every second, starting with the affected entity on top of the stack. The curse executes its hex without a casting entity, and as such cannot use your sentinel or similar. It has a 16-block radius ambit centered on the target's eye position.

The itemstack used to cast the spell becomes the curse's media reservoir, which cannot be recharged. Additionally, the spell to apply a curse must be cast directly by a player, and as such curses cannot self-perpetuate without serious shenanigans (chloe moment).

# Removal

A curse can be removed in one of three ways:
- The death of the affected entity
- The death of the caster (the caster just going offline does not count)
- A spell that removes curses

The curse-removing spell has a base cost of half again the media the curse currently has in its reservoir, but this declines to just half of the current media based on how long it has been since the curse was applied. In order to use the curse-removing spell, you must first use the curse-detecting spell, which returns a list of curse iotas representing the curses currently afflicting a target entity. These curse iotas are then used as the argument for the removal spell. There are also patterns for interacting with curse iotas in a couple other ways:
- Get the (string) name of the player who cast the curse
- Get the curse's current media reservoir
- Get the timestamp that the curse was applied at
