1 2 3 4 5 6 7 8 9 10

function newLevel() { clientMessage("[SilkTouch] is enabled."); clientMessage("Mod by @Scary_Enderman"); } function destroyBlock(x, y, z, side) { preventDefault(); Level.dropItem(x, y, z, 1, getTile(x, y, z), 1, 0); setTile(x, y, z, 0); }


