Anvil mod by Sokomine, originally a part of the Cottages mod but extracted to stand alone.

This anvil (and its associated hammer) allows a player to repair worn tools. Place the worn tool in the anvil's inventory and strike it with the hammer to improve its condition.

By default, a hammer can be repaired on the anvil just like any other tool, allowing for infinite recycling of worn tools. Set "anvil_hammer_is_repairable false" to prevent this.

Any tool belonging to the group "not_repaired_by_anvil" can't be repaired at an anvil.

The API function anvil.make_unrepairable(item_name) can be used as a convenience function to add this group to an already-registered tool.