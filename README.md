# Skrypty-Minecraft

```
PLAYER_POS: Position = None

def __make_house_block():
    player.say("Making house block...")
    
    for i in range(3):
        blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(6 + i, -1, 6 + i)), 
        positions.add(PLAYER_POS, pos(-6 - i, -1, 6 + i)), FillOperation.REPLACE)
        blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(6 + i, 3, 6 + i)), 
        positions.add(PLAYER_POS, pos(-6 - i, 3, 6 + i)), FillOperation.REPLACE)
        blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(6 + i, 7, 6 + i)), 
        positions.add(PLAYER_POS, pos(-6 - i, 7, 6 + i)), FillOperation.REPLACE)

        blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(5, 4 * i, 6)),
        positions.add(PLAYER_POS, pos(5, 2 + 4 * i, 6)), FillOperation.REPLACE)
        blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(2,  4 * i, 6)),
        positions.add(PLAYER_POS, pos(2, 2 + 4 * i, 6)), FillOperation.REPLACE)
        blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(-5,  4 * i, 6)),
        positions.add(PLAYER_POS, pos(-5, 2 + 4 * i, 6)), FillOperation.REPLACE)
        blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(-2, 4 * i, 6)),
        positions.add(PLAYER_POS, pos(-2, 2 + 4 * i, 6)), FillOperation.REPLACE)

        blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(4, 4 * i, 6)),
        positions.add(PLAYER_POS, pos(3, 2 + 4 * i, 6)), FillOperation.REPLACE)
        blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(-4, 4 * i, 6)),
        positions.add(PLAYER_POS, pos(-3, 2 + 4 * i, 6)), FillOperation.REPLACE)

        blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(6, 4 * i, 14)),
        positions.add(PLAYER_POS, pos(2, 2 + 4 * i, 14)), FillOperation.REPLACE)
        blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(-6, 4 * i, 14)),
        positions.add(PLAYER_POS, pos(-2, 2 + 4 * i, 14)), FillOperation.REPLACE)

        blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(4, 1 + 4 * i, 14)),
        positions.add(PLAYER_POS, pos(3, 1 + 4 * i, 14)), FillOperation.REPLACE)
        blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(-4, 1 + 4 * i, 14)),
        positions.add(PLAYER_POS, pos(-3, 1 + 4 * i, 14)), FillOperation.REPLACE)
    
    blocks.fill(STONE, positions.add(PLAYER_POS, pos(1, 0, 5)),
    positions.add(PLAYER_POS, pos(-1, 11, 5)), FillOperation.REPLACE)
    blocks.fill(STONE, positions.add(PLAYER_POS, pos(1, 0, 15)),
    positions.add(PLAYER_POS, pos(-1, 11, 15)), FillOperation.REPLACE)
    
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(9, -1, 9)),
    positions.add(PLAYER_POS, pos(-9, -1, 14)), FillOperation.REPLACE)
    blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(9, 3, 9)),
    positions.add(PLAYER_POS, pos(-9, 3, 14)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(9, 7, 9)),
    positions.add(PLAYER_POS, pos(-9, 7, 14)), FillOperation.REPLACE)

    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(5, 7, 5)),
    positions.add(PLAYER_POS, pos(2, 7, 5)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-5, 7, 5)),
    positions.add(PLAYER_POS, pos(-2, 7, 5)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(6, 7, 15)),
    positions.add(PLAYER_POS, pos(2, 7, 15)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-6, 7, 15)),
    positions.add(PLAYER_POS, pos(-2, 7, 15)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(6, 7, 4)),
    positions.add(PLAYER_POS, pos(-6, 7, 4)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(10, 7, 16)),
    positions.add(PLAYER_POS, pos(-10, 7, 16)), FillOperation.REPLACE)

    for i in range(4):
        blocks.fill(GRAY_CONCRETE, positions.add(PLAYER_POS, pos(6 + i, -1, 5 + i)),
        positions.add(PLAYER_POS, pos(6 + i, 10, 5 + i)), FillOperation.REPLACE)
        blocks.fill(GRAY_CONCRETE, positions.add(PLAYER_POS, pos(-6 - i, -1, 5 + i)),
        positions.add(PLAYER_POS, pos(-6 - i, 10, 5 + i)), FillOperation.REPLACE)

        blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(7 + i, 7, 4 + i)))
        blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(7 + i, 7, 5 + i)))
        blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-7 - i, 7, 4 + i)))
        blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-7 - i, 7, 5 + i)))

    blocks.fill(GRAY_CONCRETE, positions.add(PLAYER_POS, pos(-10, -1, 9)),
    positions.add(PLAYER_POS, pos(-10, 10, 15)), FillOperation.REPLACE)
    blocks.fill(GRAY_CONCRETE, positions.add(PLAYER_POS, pos(-9, -1, 15)),
    positions.add(PLAYER_POS, pos(-7, 10, 15)), FillOperation.REPLACE)
    blocks.fill(GRAY_CONCRETE, positions.add(PLAYER_POS, pos(10, -1, 9)),
    positions.add(PLAYER_POS, pos(10, 10, 15)), FillOperation.REPLACE)
    blocks.fill(GRAY_CONCRETE, positions.add(PLAYER_POS, pos(9, -1, 15)),
    positions.add(PLAYER_POS, pos(7, 10, 15)), FillOperation.REPLACE)

    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(11, 7, 8)),
    positions.add(PLAYER_POS, pos(11, 7, 16)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-11, 7, 8)),
    positions.add(PLAYER_POS, pos(-11, 7, 16)), FillOperation.REPLACE)

    blocks.fill(blocks.block_with_data(QUARTZ_SLAB, 14), positions.add(PLAYER_POS, pos(7, 7, 3)),
    positions.add(PLAYER_POS, pos(-7, 7, 3)), FillOperation.REPLACE)
    blocks.fill(blocks.block_with_data(QUARTZ_SLAB, 14), positions.add(PLAYER_POS, pos(11, 7, 17)),
    positions.add(PLAYER_POS, pos(-11, 7, 17)), FillOperation.REPLACE)
    blocks.fill(blocks.block_with_data(QUARTZ_SLAB, 14), positions.add(PLAYER_POS, pos(12, 7, 7)),
    positions.add(PLAYER_POS, pos(12, 7, 17)), FillOperation.REPLACE)
    blocks.fill(blocks.block_with_data(QUARTZ_SLAB, 14), positions.add(PLAYER_POS, pos(-12, 7, 7)),
    positions.add(PLAYER_POS, pos(-12, 7, 17)), FillOperation.REPLACE)

    blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(7, 8, 3)),
    positions.add(PLAYER_POS, pos(-7, 8, 3)), FillOperation.REPLACE)
    blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(11, 8, 17)),
    positions.add(PLAYER_POS, pos(-11, 8, 17)), FillOperation.REPLACE)
    blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(12, 8, 7)),
    positions.add(PLAYER_POS, pos(12, 8, 17)), FillOperation.REPLACE)
    blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(-12, 8, 7)),
    positions.add(PLAYER_POS, pos(-12, 8, 17)), FillOperation.REPLACE)

    for i in range(4):
        blocks.place(blocks.block_with_data(QUARTZ_SLAB, 14), positions.add(PLAYER_POS, pos(8 + i, 7, 3 + i)))
        blocks.place(blocks.block_with_data(QUARTZ_SLAB, 14), positions.add(PLAYER_POS, pos(8 + i, 7, 4 + i)))
        blocks.place(blocks.block_with_data(QUARTZ_SLAB, 14), positions.add(PLAYER_POS, pos(-8 - i, 7, 3 + i)))
        blocks.place(blocks.block_with_data(QUARTZ_SLAB, 14), positions.add(PLAYER_POS, pos(-8 - i, 7, 4 + i)))

        blocks.place(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(8 + i, 8, 3 + i)))
        blocks.place(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(8 + i, 8, 4 + i)))
        blocks.place(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(-8 - i, 8, 3 + i)))
        blocks.place(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(-8 - i, 8, 4 + i)))

        blocks.fill(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(8 + i, 11, 3 + i)),
        positions.add(PLAYER_POS, pos(-8 - i, 11, 3 + i)), FillOperation.REPLACE)

    blocks.fill(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(12, 11, 7)),
    positions.add(PLAYER_POS, pos(-12, 11, 17)), FillOperation.REPLACE)
    blocks.fill(STONE, positions.add(PLAYER_POS, pos(1, 11, 5)),
    positions.add(PLAYER_POS, pos(-1, 11, 15)), FillOperation.REPLACE)
    
    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(0, 7, 5)))
    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(0, 7, 15)))
    blocks.place(blocks.block_with_data(DARK_OAK_DOOR, 3), positions.add(PLAYER_POS, pos(0, 8, 5)))
    blocks.place(blocks.block_with_data(DARK_OAK_DOOR, 1), positions.add(PLAYER_POS, pos(0, 8, 15)))


def __make_stairs():
    player.say("Making stairs...")
    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(6, 0, 4)))
    blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(6, 1, 4)))
    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(6, 0, 3)))
    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(10, 0, 3)))
    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(11, 0, 4)))
    blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(11, 1, 4)))

    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-6, 0, 4)))
    blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(-6, 1, 4)))
    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-6, 0, 3)))
    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-10, 0, 3)))
    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-11, 0, 4)))
    blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(-11, 1, 4)))

    blocks.fill(OAK_WOOD_SLAB, positions.add(PLAYER_POS, pos(7, 0, 3)), positions.add(PLAYER_POS, pos(9, 0, 3)), FillOperation.REPLACE)
    blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(7, 0, 4)), positions.add(PLAYER_POS, pos(10, 0, 4)), FillOperation.REPLACE)
    blocks.fill(OAK_WOOD_SLAB, positions.add(PLAYER_POS, pos(-7, 0, 3)), positions.add(PLAYER_POS, pos(-9, 0, 3)), FillOperation.REPLACE)
    blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(-7, 0, 4)), positions.add(PLAYER_POS, pos(-10, 0, 4)), FillOperation.REPLACE)

    _odd = 2
    _even = 2
    last_step = 0
    for i in range(5):
        if i == 4:
            last_step = 1

        if i % 2 == 0:
            for j in range(_odd):
                blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(7 + i, j, 5 + i)))
                blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-7 - i, j, 5 + i)))
                if i < 4:
                    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(12 + i, j, 5 + i)))
                    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-12 - i, j, 5 + i)))
                else:
                    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(11 + i, j, 5 + i)))
                    blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-11 - i, j, 5 + i)))
            blocks.fill(OAK_WOOD_SLAB, positions.add(PLAYER_POS, pos(8 + i, _odd - 1, 5 + i)), 
            positions.add(PLAYER_POS, pos(11 + i - last_step, _odd - 1, 5 + i)), FillOperation.REPLACE)
            blocks.fill(OAK_WOOD_SLAB, positions.add(PLAYER_POS, pos(-8 - i, _odd - 1, 5 + i)), 
            positions.add(PLAYER_POS, pos(-11 - i + last_step, _odd - 1, 5 + i)), FillOperation.REPLACE)
            _odd += 1
        else:
            for j in range(_even):
                blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(7 + i, j, 5 + i)))
                blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-7 - i, j, 5 + i)))
                blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(12 + i, j, 5 + i)))
                blocks.place(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-12 - i, j, 5 + i)))
            blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(7 + i, _even, 5 + i)))
            blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(-7 - i, _even, 5 + i)))
            blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(12 + i, _even, 5 + i)))
            blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(-12 - i, _even, 5 + i)))
            blocks.fill(blocks.block_with_data(OAK_WOOD_SLAB, 8), positions.add(PLAYER_POS, pos(8 + i, _even - 1, 5 + i)), 
            positions.add(PLAYER_POS, pos(11 + i, _even - 1, 5 + i)), FillOperation.REPLACE)
            blocks.fill(blocks.block_with_data(OAK_WOOD_SLAB, 8), positions.add(PLAYER_POS, pos(-8 - i, _even - 1, 5 + i)), 
            positions.add(PLAYER_POS, pos(-11 - i, _even - 1, 5 + i)), FillOperation.REPLACE)
            _even += 1
    
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(15, 0, 10)), positions.add(PLAYER_POS, pos(15, 3, 16)), FillOperation.REPLACE)
    blocks.fill(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(15, 4, 10)), positions.add(PLAYER_POS, pos(15, 4, 16)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(14, 0, 16)), positions.add(PLAYER_POS, pos(6, 3, 16)), FillOperation.REPLACE)
    blocks.fill(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(14, 4, 16)), positions.add(PLAYER_POS, pos(6, 4, 16)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(6, 0, 15)), positions.add(PLAYER_POS, pos(6, 3, 15)), FillOperation.REPLACE)
    blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(6, 4, 15)))
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-15, 0, 10)), positions.add(PLAYER_POS, pos(-15, 3, 16)), FillOperation.REPLACE)
    blocks.fill(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(-15, 4, 10)), positions.add(PLAYER_POS, pos(-15, 4, 16)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-14, 0, 16)), positions.add(PLAYER_POS, pos(-6, 3, 16)), FillOperation.REPLACE)
    blocks.fill(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(-14, 4, 16)), positions.add(PLAYER_POS, pos(-6, 4, 16)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-6, 0, 15)), positions.add(PLAYER_POS, pos(-6, 3, 15)), FillOperation.REPLACE)
    blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(-6, 4, 15)))

    blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(14, 3, 10)), positions.add(PLAYER_POS, pos(11, 3, 15)), FillOperation.REPLACE)
    blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(-14, 3, 10)), positions.add(PLAYER_POS, pos(-11, 3, 15)), FillOperation.REPLACE)


def __add_details():
    player.say("Adding details...")
    blocks.fill(AIR, positions.add(PLAYER_POS, pos(10, 4, 13)), positions.add(PLAYER_POS, pos(10, 5, 12)), FillOperation.REPLACE)
    # blocks.place(blocks.block_with_data(DARK_OAK_DOOR, 2), positions.add(PLAYER_POS, pos(10, 4, 13)))
    # blocks.place(blocks.block_with_data(DARK_OAK_DOOR, 2), positions.add(PLAYER_POS, pos(10, 4, 12)))
    blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(10, 3, 13)), positions.add(PLAYER_POS, pos(10, 3, 12)), FillOperation.REPLACE)
    blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(11, 4, 15)))
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(11, 4, 14)), positions.add(PLAYER_POS, pos(11, 10, 14)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(11, 4, 11)), positions.add(PLAYER_POS, pos(11, 10, 11)), FillOperation.REPLACE)
    blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(11, 4, 10)))
    blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(10, 9, 13)), positions.add(PLAYER_POS, pos(10, 9, 12)), FillOperation.REPLACE)
    blocks.place(blocks.block_with_data(QUARTZ_STAIRS, 5), positions.add(PLAYER_POS, pos(11, 6, 13)))
    blocks.place(blocks.block_with_data(QUARTZ_STAIRS, 5), positions.add(PLAYER_POS, pos(11, 6, 12)))
    blocks.place(blocks.block_with_data(QUARTZ_STAIRS, 5), positions.add(PLAYER_POS, pos(11, 10, 13)))
    blocks.place(blocks.block_with_data(QUARTZ_STAIRS, 5), positions.add(PLAYER_POS, pos(11, 10, 12)))

    blocks.fill(AIR, positions.add(PLAYER_POS, pos(-10, 4, 13)), positions.add(PLAYER_POS, pos(-10, 5, 12)), FillOperation.REPLACE)
    # blocks.place(blocks.block_with_data(DARK_OAK_DOOR, 2), positions.add(PLAYER_POS, pos(-10, 4, 13)))
    # blocks.place(blocks.block_with_data(DARK_OAK_DOOR, 2), positions.add(PLAYER_POS, pos(-10, 4, 12)))
    blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(-10, 3, 13)), positions.add(PLAYER_POS, pos(10, 3, 12)), FillOperation.REPLACE)
    blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(-11, 4, 15)))
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-11, 4, 14)), positions.add(PLAYER_POS, pos(-11, 10, 14)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-11, 4, 11)), positions.add(PLAYER_POS, pos(-11, 10, 11)), FillOperation.REPLACE)
    blocks.place(QUARTZ_SLAB, positions.add(PLAYER_POS, pos(-11, 4, 10)))
    blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(-10, 9, 13)), positions.add(PLAYER_POS, pos(-10, 9, 12)), FillOperation.REPLACE)
    blocks.place(blocks.block_with_data(QUARTZ_STAIRS, 4), positions.add(PLAYER_POS, pos(-11, 6, 13)))
    blocks.place(blocks.block_with_data(QUARTZ_STAIRS, 4), positions.add(PLAYER_POS, pos(-11, 6, 12)))
    blocks.place(blocks.block_with_data(QUARTZ_STAIRS, 4), positions.add(PLAYER_POS, pos(-11, 10, 13)))
    blocks.place(blocks.block_with_data(QUARTZ_STAIRS, 4), positions.add(PLAYER_POS, pos(-11, 10, 12)))

    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(10, -1, 2)), positions.add(PLAYER_POS, pos(6, -1, -2)), FillOperation.REPLACE)
    blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(9, -1, 2)), positions.add(PLAYER_POS, pos(7, -1, -2)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(10, 0, -2)), positions.add(PLAYER_POS, pos(10, 1, -2)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(6, 0, -2)), positions.add(PLAYER_POS, pos(6, 1, -2)), FillOperation.REPLACE)
    blocks.place(IRON_TRAPDOOR, positions.add(PLAYER_POS, pos(10, 2, -2)))
    blocks.place(IRON_TRAPDOOR, positions.add(PLAYER_POS, pos(6, 2, -2)))
    blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(10, 0, 2)), positions.add(PLAYER_POS, pos(10, 0, -1)), FillOperation.REPLACE)
    blocks.place(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(6, 0, 2)))
    blocks.place(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(6, 0, -1)))
    blocks.fill(blocks.block_with_data(QUARTZ_STAIRS, 0), positions.add(PLAYER_POS, pos(6, -1, 1)), positions.add(PLAYER_POS, pos(6, -1, 0)), FillOperation.REPLACE)

    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-10, -1, 2)), positions.add(PLAYER_POS, pos(-6, -1, -2)), FillOperation.REPLACE)
    blocks.fill(PLANKS_OAK, positions.add(PLAYER_POS, pos(-9, -1, 2)), positions.add(PLAYER_POS, pos(-7, -1, -2)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-10, 0, -2)), positions.add(PLAYER_POS, pos(-10, 1, -2)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-6, 0, -2)), positions.add(PLAYER_POS, pos(-6, 1, -2)), FillOperation.REPLACE)
    blocks.place(IRON_TRAPDOOR, positions.add(PLAYER_POS, pos(-10, 2, -2)))
    blocks.place(IRON_TRAPDOOR, positions.add(PLAYER_POS, pos(-6, 2, -2)))
    blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(-10, 0, 2)), positions.add(PLAYER_POS, pos(-10, 0, -1)), FillOperation.REPLACE)
    blocks.place(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(-6, 0, 2)))
    blocks.place(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(-6, 0, -1)))
    blocks.fill(blocks.block_with_data(QUARTZ_STAIRS, 1), positions.add(PLAYER_POS, pos(-6, -1, 1)), positions.add(PLAYER_POS, pos(-6, -1, 0)), FillOperation.REPLACE)

    blocks.fill(AIR, positions.add(PLAYER_POS, pos(5, -2, -1)), positions.add(PLAYER_POS, pos(-5, 0, 5)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(5, -2, -2)), positions.add(PLAYER_POS, pos(-5, -1, -2)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(6, -2, -2)), positions.add(PLAYER_POS, pos(6, -2, 5)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(6, -1, 3)), positions.add(PLAYER_POS, pos(6, -1, 5)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-6, -2, -2)), positions.add(PLAYER_POS, pos(-6, -2, 5)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(-6, -1, 3)), positions.add(PLAYER_POS, pos(-6, -1, 5)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(5, -2, 6)), positions.add(PLAYER_POS, pos(-5, -2, 6)), FillOperation.REPLACE)
    blocks.fill(BLOCK_OF_QUARTZ, positions.add(PLAYER_POS, pos(5, -3, -1)), positions.add(PLAYER_POS, pos(-5, -3, 5)), FillOperation.REPLACE)
    blocks.fill(BLACK_STAINED_GLASS_PANE, positions.add(PLAYER_POS, pos(5, 0, -2)), positions.add(PLAYER_POS, pos(-5, 0, -2)), FillOperation.REPLACE)
    blocks.fill(STONE, positions.add(PLAYER_POS, pos(1, 0, 5)), positions.add(PLAYER_POS, pos(-1, -2, 5)), FillOperation.REPLACE)

    blocks.fill(LEAVES_OAK, positions.add(PLAYER_POS, pos(11, 0, -2)), positions.add(PLAYER_POS, pos(11, 0, 3)), FillOperation.REPLACE)
    blocks.fill(LEAVES_OAK, positions.add(PLAYER_POS, pos(-11, 0, -2)), positions.add(PLAYER_POS, pos(-11, 0, 3)), FillOperation.REPLACE)

    for i in range(4):
        blocks.place(LEAVES_OAK, positions.add(PLAYER_POS, pos(12 + i, 0, 3 + i)))
        blocks.place(LEAVES_OAK, positions.add(PLAYER_POS, pos(12 + i, 0, 4 + i)))
        blocks.place(LEAVES_OAK, positions.add(PLAYER_POS, pos(-12 - i, 0, 3 + i)))
        blocks.place(LEAVES_OAK, positions.add(PLAYER_POS, pos(-12 - i, 0, 4 + i)))

    blocks.fill(LEAVES_OAK, positions.add(PLAYER_POS, pos(16, 0, 7)), positions.add(PLAYER_POS, pos(16, 0, 16)), FillOperation.REPLACE)
    blocks.fill(LEAVES_OAK, positions.add(PLAYER_POS, pos(16, 0, 17)), positions.add(PLAYER_POS, pos(6, 0, 17)), FillOperation.REPLACE)
    blocks.fill(LEAVES_OAK, positions.add(PLAYER_POS, pos(5, 0, 17)), positions.add(PLAYER_POS, pos(5, 0, 15)), FillOperation.REPLACE)
    blocks.fill(LEAVES_OAK, positions.add(PLAYER_POS, pos(4, 0, 15)), positions.add(PLAYER_POS, pos(2, 0, 15)), FillOperation.REPLACE)

    blocks.fill(LEAVES_OAK, positions.add(PLAYER_POS, pos(-16, 0, 7)), positions.add(PLAYER_POS, pos(-16, 0, 16)), FillOperation.REPLACE)
    blocks.fill(LEAVES_OAK, positions.add(PLAYER_POS, pos(-16, 0, 17)), positions.add(PLAYER_POS, pos(-6, 0, 17)), FillOperation.REPLACE)
    blocks.fill(LEAVES_OAK, positions.add(PLAYER_POS, pos(-5, 0, 17)), positions.add(PLAYER_POS, pos(-5, 0, 15)), FillOperation.REPLACE)
    blocks.fill(LEAVES_OAK, positions.add(PLAYER_POS, pos(-4, 0, 15)), positions.add(PLAYER_POS, pos(-2, 0, 15)), FillOperation.REPLACE)

    blocks.fill(WATER, positions.add(PLAYER_POS, pos(5, -1, -1)), positions.add(PLAYER_POS, pos(-5, -2, 4)), FillOperation.REPLACE)
    blocks.fill(WATER, positions.add(PLAYER_POS, pos(5, -1, 5)), positions.add(PLAYER_POS, pos(2, -2, 5)), FillOperation.REPLACE)
    blocks.fill(WATER, positions.add(PLAYER_POS, pos(-5, -1, 5)), positions.add(PLAYER_POS, pos(-2, -2, 5)), FillOperation.REPLACE)
    
    blocks.fill(AIR, positions.add(PLAYER_POS, pos(-2, 3, 13)), positions.add(PLAYER_POS, pos(1, 3, 12)), FillOperation.REPLACE)
    blocks.fill(AIR, positions.add(PLAYER_POS, pos(-4, 7, 13)), positions.add(PLAYER_POS, pos(-1, 7, 12)), FillOperation.REPLACE)
    for i in range(4):
        blocks.fill(blocks.block_with_data(QUARTZ_STAIRS, 0), positions.add(PLAYER_POS, pos(-1 + i, i, 13)), positions.add(PLAYER_POS, pos(-1 + i, i, 12)), FillOperation.REPLACE)
        blocks.fill(blocks.block_with_data(QUARTZ_STAIRS, 0), positions.add(PLAYER_POS, pos(-3 + i, 4 + i, 13)), positions.add(PLAYER_POS, pos(-3 + i, 4 + i, 12)), FillOperation.REPLACE)
        if i < 3:
            blocks.fill(blocks.block_with_data(QUARTZ_STAIRS, 5), positions.add(PLAYER_POS, pos(i, i, 13)), positions.add(PLAYER_POS, pos(i, i, 12)), FillOperation.REPLACE)
            blocks.fill(blocks.block_with_data(QUARTZ_STAIRS, 5), positions.add(PLAYER_POS, pos(-2 + i, 4 + i, 13)), positions.add(PLAYER_POS, pos(-2 + i, 4 + i, 12)), FillOperation.REPLACE)
    
    blocks.fill(blocks.block_with_data(QUARTZ_STAIRS, 5), positions.add(PLAYER_POS, pos(-3, 3, 13)), positions.add(PLAYER_POS, pos(-3, 3, 12)), FillOperation.REPLACE)


def make_house():
    global PLAYER_POS
    PLAYER_POS = player.position()
    gameplay.set_weather(CLEAR)
    gameplay.time_set(gameplay.time(DAY))
    player.teleport(positions.add(PLAYER_POS, pos(0, 0, -5)))
    __make_house_block()
    __make_stairs()
    __add_details()
    player.say("Finished!")


player.on_chat("house", make_house)

```
