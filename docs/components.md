At the moment there are 3 Types of components:

*   Input containers - Items in these chests will automatically get transferred into the miscellaneous chests.
*   Sorting containers - These chests have an item as a filter and only items matching the chest's filter will get transferred here
*   Miscellaneous containers - If there is no chest for an item type, the leftover items will go here

To add a component into your network, you first need to craft it at the crafting table.

The recipes should be unlocked at join, make sure the recipe book is set to “Show all” and not “Only craftable”.

After [selecting the network](/basics), the component can be installed in chests by right clicking them.

You should receive a confirmation message in chat.

#### Network Wand

For further editing, you need a **Network Wand**, which can also be crafted.

Using left-click (without shift), you can switch between material filter, strict filter and priority editing mode.

By right-clicking on a network component, you can see basic information about it.

For Sorting Containers to function, they need to be given at least one item as a filter.

This is done by shift + right-clicking a Sorting Container with a **Network Wand** (on one of the two filter modes) in the main hand and your filter item in the offhand.  
To remove the filter, do the same, but shift + left click.

Alternatively, you can also put the desired items into the inventory of the Sorting Container and shift + left/right-click with the **Network Wand** in the main hand and an empty offhand, to add all items in the inventory as a filter.
Using this method with shift + left-click will remove all existing filters and then add only the items in the inventory as a filter.
Using this method with shift + right-click will keep existing filters and add all items in the inventory as additional filters.

When on **Material Filter** mode, the entire item type is added as a filter. (For example: All Enchanted books)

When on **Strict Filter** mode, only this specific item with its metadata is added. (For example: Only Efficiency V books)

For items without metadata (like wood, stone, etc..), the material filter will automatically be used, no matter which mode you are in.

#### Priority

If you have multiple sorting containers with the same filter or multiple miscellaneous containers, you can set their priority, so that higher priority components will be filled first.

(By default, sorting containers are prioritized over misc containers)

To change a component's priority, make sure your wand is set to **Priority Mode** and shift + right/left click on a Sorting/Miscellaneous container.
