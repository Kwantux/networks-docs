At the moment there are 3 Types of components:

*   Input containers - Items in these containers will automatically get transferred into the miscellaneous containers.
*   Sorting containers - These containers have an item as a filter and only items matching the container's filter will get transferred here
*   Miscellaneous containers - If there is no container for an item type, the leftover items will go here

Containers can be any block that can store items, like chests, barrels, hoppers, dispensers

To add a component into your network, you first need to craft it at the crafting table.

The recipes should be unlocked at join, make sure the recipe book is set to “Show all” and not “Only craftable”.

After [selecting the network](/basics), the component can be installed in containers by right clicking them.

You should receive a confirmation message in chat.

### Input containers

Input containers can be manually filled with items.
As soon as you close the inventory, the items will be transferred into the network (if there is enough space).

You can also have a hopper run into an input container to automatically transfer items into the network.
Using this method, items are sent into the network immediately and fully automatically.

Input containers have a limited range they can transfer items to.
You can increase this range by crafting antennas and placing them on the input container.
More information on antennas can be found [here](/range).

Unless your network is full or you're using another mechanic to add items to the input containers, there should be no way of having items left over in the input containers.
If you do manage to have items left over (when the network is not full), please report it on [Discord](https://discord.gg/Q65TqRwnce) or create a [Github Issue](https://github.com/Kwantux/networks/issues/new).
As a short term fix, just open the inventory of the input container and close it again, so that the items are transferred into the network.


### Sorting containers

Sorting containers accept items that match their filter.
You can set filters for item types (like cobblestone, wood, all enchanted books) or specific items (like efficiency V book, enchanted book of binding, etc.)
To set a filter, you need a **Network Wand**.

### Miscellaneous containers

Miscellaneous containers accept all items that do not match any filter of any sorting container in range.