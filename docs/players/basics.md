## Creating and editing a network

To create a storage network, simply run `/net create <name>`

`<name>` is the ID of your network, you will need it to edit your network.

Every network on the server has its own unique ID.

To perform any changes, you first need to select your network using `/net select <name>`

This is needed to place new network components or add new users.

## Placing and configuring components

A network consists of 3 types of components:

* Input containers - Items in here will be transferred into the network.
* Sorting containers - These containers only accept items matching their filter.
* Miscellaneous containers - If there is no container for an item type, the leftover items will go here

These components can be crafted and then right clicked on any container to install it.
You need to have a network selected to install a component.

More information on the exact behavior of the different types of containers can be found [here](/players/components).

Use the **Network Wand** to see information about a component, set filters and priorities.

More information on the **Network Wand** can be found [here](/players/wand).

Note that input containers have a limited range they can transfer items to.
You can increase this range by crafting antennas and placing them on the input container.
More information on antennas can be found [here](/players/range).

## Further network configuration

By default, only the creator of a network can add/remove/configure components.
Add users to your network to allow them to add/remove/configure components.
For more information, continue to the [users](/players/users) page.

You can also merge networks to combine multiple networks into one.
For more information, continue to the [merging](/players/merging) page.

For a list of all commands, continue to the [commands](/players/commands) page.

### Deleting a network

If you wish to delete your network, simply run `/net delete <name>`

You will be asked to confirm this action using `/net delete <name> confirm`

**But be careful: This action is not reversible!**