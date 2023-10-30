# CHANGES

## Common

### Artifacts
Changes made to increase rarity since many of the items are very overpowered.

- **Artifact Rarity**: 1 > 100
- **Campsite Count**: 4 > 1 (Generated too frequently)
- **Mimic chance**: 0.3 > 0.45 (To account for decreased campsite count)
- **Everlasting Beef Chance**: Now 1/10000 chance of dropping

### Create
- **Powered Train Top Speed**: 40 > 50
- **Powered Train Turning Speed**: 20 > 25

### Spelunkery
- **Obtaining crying obsidian from Piglins and breaking a portal**: disabled > enabled (Compat with Terratorial)
- **Creative Tab**: disabled > enabled

### Promenade
- **Disabled spawning for some mobs**: Lush Creeper (Too many creepers), Ducks (Already added by naturalist)
- **Modified Sunken Skeletons spawn rate**: 20 > 10 (Spawned too frequently)
- **No Palm trees**: Added by Regions Unexplored already
- **Decreased generation weight for all biomes**: Where generating to frequently

### Bewitchment
- **Disabled silver generation**: Mythic metals variant looks better
- **Replaced all silver related recipes**: Substituted with Mythic metals silver
- **Replaced all salt related recipes**: Substituted with Spelunkery salt

### Minecells
- **Disabled recipes for MineCells elevator**: Encourage peeps to use create instead
- **Reduced portal spawn chance & restricted to biomes with plenty of trees**:  Portals where generating too frequently and generation looks better in denser area where it's covered better. Valid biomes are the **Dark Forest**, **Rainbow Forest (Terrestria)** and **Dense Forests (Terrestria)**

### Wilder Wild
- **Disable Milkweed + Datura** - Too many flowers, even for me
- **Added rough compatibility with Terrestria biomes** - Modified datapack files manually. It was a pita lol.

### Wildlife
- **Removed insects, fish, and some other animals such as crabs**: Removed due to bad textures, AI or plenty of the provided mob type already exists. For e.g. Fishes with Hybrid Aquatic.

### Hybrid Aquatic
- **Stopped Anglerfish spawning**: Replaced with it's terrifying cousin from Aquamirae

### Mythic Metals
- **Removed the following ores**:
    - Tin Ore (Redundant, No special properties). Also disables creation of bronze.
    - Osmium Ore (Redundant, No special properties)

### The Graveyard
- **Decreased the spawn chance for all mobs** (Spawn rate was too frequent)

### Blockus
- **Remove white oak trees**: Don't blend in well with the terrain

### Regions Unexplored
- **Reduced the biome weights down signfiicantly**: Allow vanilla biomes to spawn more frequently instead of getting overwhelmed with RU biomes
- **Removed some individual biomes**:
    - Bamboo Forest, Golden Boreal Taiga, Mauve Hills (All a bit boring)
    - Magnolia Woodland, Aumtumnl Maple Forest, Deciduous Forests, Magnolia Woodland, Silver Birch Forest, Willow Forest (Reduce the amount of forests, increase generation of swamps, desert biomes)
    - Redstone caves (Over powered)
    - Scorching caves (Too Dangerous)
    - Maple forest (Replaced with Natures Spirit alternative)
    - Alpha Grove. Grass textures conflict with structure datapack generation
- **Replaced various blocks with Natures Spirit alternatives**: Hibiscus Flower

### Cammies Minecart tweaks
- **Minecart speed**: 8 > 14
- **Furnace Minecart Chunk Loading**: false > true (Means furnace minecarts can load chunks)

### Natures Spirit
- **Disabled the following biomes**:
    - Cypress fields, Redwood Forest (Regions Unexplored has better looking biomes)
- **Disabled Joshua trees & wood type**: Conflict with Regions Unexplored

### Visual Overhaul
- **Disabled Furnace model & button icons**: Personal preference, didn't look great

### Inmin Backpacks
- **Reduced size**: Reduced there size considerably (for the purpose of balancing)

## The Graveyard
- **Removed some structure generation**: Medium Graveyard (To reduce the total number of Graveyard Structures), Lich Prison (Boss spawning is disabled)
- **Remove mob spawns entirely for the following mobs**: Ghouls, Revenant, Nightmare, Ghouling, Corrupted Champion (Bad models and(or) animations)
- **Removed some individual Blocks & Items**: Skeleton Hand, Bone Staff blocks & items (All my homies hate Mixels)
- **Disabled Horde Spawns**: Neat idea but to difficult for the average player
- **Give a spawn chance to the wraith**: Substitute for the lack of other mob spawns. Same spawning weight as the Reaper with a maximum group chance of 1


## Known Bugs

- Signs from the following mods when placed will display as oak signs: Regions Unexplored, Natures Spirit. This is a consequence of a debug mod implemented to stop in-correct wood type registries crashing the server. See: [Issue #16 for Natures Spirit](https://github.com/Team-Hibiscus/NatureSpirit/issues/16) for an explanation.
- Cammies minecarts chains don't render
- Natures Spirit flowers can be too big causing a weird black box rendering issue
- Slight texture issue for pocket computers with the ccc resourcepack (Probably wont fix, too small)


