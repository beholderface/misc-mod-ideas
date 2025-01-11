# Lick

- Adds the ability to lick things using a keybind.

- Some blocks are given a new blockstate (ideally added dynamically, via tag) that denotes that they have previously been licked. Villagers refuse to use job site blocks with this blockstate active. Sometimes pets will just go up to random blocks and lick them.

- Licking a sponge turns it into a wet sponge, and licking farmland hydrates it. There is support for datapacks to add additional licking-triggered transmutation recipes.

- You can lick entities, bestowing the "moist" status effect. This effect causes water droplet particles to appear from affected entities.

- There are three block tags (with identically-named entity tag counterparts) that denote special behavior when you lick something: `lick:sharp`, `lick:hot`, and `lick:toxic`, which cause various negative effects.

- There is an item crafted with a wet sponge that you can rclick blocks with to turn off the licked blockstate. There is nothing stopping you from licking a sponge to get the wet sponge used for this item.
