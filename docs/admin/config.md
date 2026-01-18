The general config is located at `<serverfiles>/plugins/Networks/general.conf`.
A second config specifically for crafting recipes is located at `<serverfiles>/plugins/Networks/recipes.conf`.

## Language

The language of the plugin is set in the general config with the `lang` option.
By default, English and German are available, but you can add your own language by adding a new file to the `lang` folder using the same syntax as the other files.

## Command aliases

`/networks` is always available.

By default, you can also use `/n` and `/net`.

However, if you have another plugin using `/n` or `/net`, you can add your own aliases in the general config with the `commands` option.

## Disabling the "Have you tried Networks yet?" message

By default, the plugin will show a message in chat, when a player opens a full chest and never created a network..
You can disable this message by setting the `notice` option to `false` in the general config.

## Blast proof components

By default, components are immmune to explosions.
You can disable this by setting the `blastProofComponents` option to `false` in the general config.

## Max Networks

By default, there is a limit of 5 networks, a player can own.
You can set a limit by setting the `maxNetworks` option to a number in the general config.

`requestOwnershipTransfers` (enabled by default) might also be relevant for this option.
This means you cannot transfer a network to another player if they don't want to.


## Component blocks

Using the `component.[input|sorting|misc]` option, you can define which blocks should be recognized as a component.
By default, all blocks, where this is useful, are enabled.
Shulkerboxes and furnaces are not enabled by default, as they don't work properly.



## Auto Save

The `autoSave` option defines how often the networks should be saved.
By default, it is set to 2 minutes.

## Performance

### Load chunks

By default, you can not transfer items into unloaded chunks.
If you want to allow this though, you can enable the `performance.loadChunks` option.
This will cause the server to load chunks that are not currently loaded.
This may effect your server's performance, so use it with caution.
Also it allows malicious players to lag the server really easily, so you should only use this option on private servers.
This option may not work on Folia.

### Complex inventory checks

Networks takes a shortcut when checking whether an item can be transferred into a container, by only checking if said inventory has a free slot.
However, if you have an inventory filled with items of the same type and the last stack is not full and you try to transfer a low amount of items, it will still not be able to transfer them even though there is enough space.

By default, the plugin only checks if said inventory has a free slot (better for performance).
When this option is enabled, it checks whether the stack, that's to fill in, can be spreaded to partially filled slots with the same item type.

This should not significantly effect performance, but you should do your own testing to see if it's worth it.

## Network properties

You can change the base range of tier 0 input containers here.

Also you could define a maximum amount of users and components per network here.

## Ranges

You can define the range per tier here. The first number should be 0, the second number is the additional range for tier 1, the third the additional range for tier 2, etc..
Write the ranges in meters. A value of -1 means infinite and interdimensional.
You can also add and remove tiers here by making the list shorter or longer, but you need to add/remove crafting recipes for the tiers you want to add/remove.

If you want range upgrades to apply network wide instead of per container, set the `rangePerNetwork` option to `true`.

To disable the range system entirely, set the first number to -1, delete all other numbers and remove the crafting recipes for the tiers.

## Base materials

Antennas and installable components are shown as lightning rods and item frames in the inventory.
You can change these item types with the `baseMaterials` option.
This is mostly for cosmetics and doesn't effect the functionality of the plugin.
Please note however, that players could in fact use these items to craft other stuff, (so don't choose netherite ingots as a base material for example)