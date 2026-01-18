
The Network Wand is used to configure the filters for your sorting containers, and view more information about your network components. 
You can craft it at the crafting table.

Right Click on any network container with the wand in your main hand to view details.
Left Click to toggle the wand mode.

## Wand modes

### Material filter mode
This will be your main mode to set whitelist filters on the containers.
This means that every item on the filter for that container could go to that container. It is possible to add multiple filters to a containers and it is possible to add the same filter to multiple containers. 

This filter does not store metadata and will accept every item of the same type.
Usage example: normal block filtering like cobblestone, stone, grass, wood 

#### Adding and removing filters

There are two ways to add and remove filters:

##### Having the desired filter item in your offhand
You must have the item you are filtering in your off-hand, and the wand in your main hand.

- Sneak + Right Click on any sorting container to add a filter. 
- Sneak + Left Click on any sorting container to remove a filter.

##### Place the desired filter items into the inventory of the sorting container

- Sneak + Right Click on any sorting container to add all items inside of it as a filter, but **keep all existing filters**.
- Sneak + Left Click on any sorting container to add all items inside of it as a filter, but **remove all other existing filters**.


### Strict filter mode

This mode works similar to material filter mode, but it also filters by metadata.
If you add a potion as a filter in the material filter mode, that container will accept every potion.
If you add a potion as a filter in the strict filter mode, it will only accept the specific potion.
Usage example: potions, tools, armor, enchantment books, etc. 

The wand in this mode is used the same way as in material filter mode.

Strict filters are shown in brackets in the filter list like this: [Potion].
Material filters are shown without brackets like this: Potion.


### Priority mode

This mode is for setting priority of which containers are going to be filled first. 

You can change the priority of "output containers" (sorting containers and miscellaneous containers).
Input containers send items more or less immediately, so they do not need a priority.

- Shift + Right Click with the wand to increase the priority of a container.
- Shift + Left Click with the wand to decrease the priority of a container.

Priority is from high to low, meaning that a container with priority 10 will be filled before a container with priority 9.

Sorting containers have a higher default priority than misc containers.
If you manually set the priority of a misc container higher than that of a sorting container, it will be filled first.
(There is no real reason to do this, but it is possible if you want to)
