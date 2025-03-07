# Minecraft Achievement Creator 🦄

-   Quickly create custom Minecraft achievements for yourself. ✨
-   Choose the one you like among more than 100 icons. 💯

# Usage ✅

-   commonJS (`const {} = require("module")`)

```js
const { ICONS, AchievementCreator } = require("mc-achievements");

// this is not necessary
const { writeFileSync } = require("fs");

AchievementCreator.create(
	ICONS.ironLeggings,
	"This is title!",
	"This is content",
).then((buffer) => {
	/*
    Buffer of the achievement you created.
    Do whatever you want with buffer.
    In this example, we save buffer as a local file.
    */
	writeFileSync("./achievement.png", buffer);
});
```

-   es6 (`import {} from "module"`)

```ts
import { ICONS, AchievementCreator } from "mc-achievements";

// this is not necessary
import { writeFileSync } from "fs";

AchievementCreator.create(ICONS.egg, "This is title!", "This is content").then(
	(buffer) => {
		/*
    Buffer of the achievement you created.
    Do whatever you want with buffer.
    In this example, we save buffer as a local file.
    */
		writeFileSync("./achievement.png", buffer);
	},
);
```

# Contributing / Issues 🐛

-   Feel free to open pull requests or issues 🙀

# Icons 💡

-   Use `ICONS.icon_name` to access icons (eg. `ICONS.apple`)
-   apple: "apple"
-   arrow: "arrow"
-   bed: "bed"
-   bedrock: "bedrock"
-   blazePowder: "blaze_powder"
-   blazeRod: "blaze_rod"
-   blockOfDiamond: "block_of_diamond"
-   blockOfGold: "block_of_gold"
-   blockOfIron: "block_of_iron"
-   boat: "boat"
-   bone: "bone"
-   bonemeal: "bonemeal"
-   book: "book"
-   bottleOfEnchanting: "bottle_of_enchanting"
-   bottle: "bottle"
-   bow: "bow"
-   bowl: "bowl"
-   bread: "bread"
-   brewingStand: "brewing_stand"
-   bucket: "bucket"
-   cake: "cake"
-   chainmailBoots: "chainmail_boots"
-   chainmailChestplate: "chainmail_chestplate"
-   chainmailHelmet: "chainmail_helmet"
-   chainmailLeggings: "chainmail_leggings"
-   charcoal: "charcoal"
-   chest: "chest"
-   coalOre: "coal_ore"
-   coal: "coal"
-   cobblestone: "cobblesonte"
-   compass: "compass"
-   cookedChicken: "cooked_chicken"
-   cookedFish: "cooked_fish"
-   cookedPorkchop: "cooked_porkchop"
-   cookie: "cookie"
-   diamondAxe: "diamond_axe"
-   diamondBoots: "diamond_boots"
-   diamondChestplate: "diamond_chestplate"
-   diamondHelmet: "diamond_helmet"
-   diamondHoe: "diamond_hoe"
-   diamondLeggings: "diamond_leggings"
-   diamondOre: "diamond_ore"
-   diamondPickaxe: "diamond_pickaxe"
-   diamondShovel: "diamond_shovel"
-   diamondSword: "diamond_sword"
-   diamond: "diamond"
-   dirt: "dirt"
-   dragonEgg: "dragon_egg"
-   egg: "egg"
-   enchantmentTable: "enchantment_table"
-   enderPearl: "ender_pearl"
-   eyeOfEnder: "eye_of_ender"
-   feather: "feather"
-   fenceGate: "fence_gate"
-   fence: "fence"
-   flintAndSteel: "flint_and_steel"
-   flint: "flint"
-   furnance: "furnance"
-   glowstoneDust: "glowstone_dust"
-   goldApple: "gold_apple"
-   goldAxe: "gold_axe"
-   goldBoots: "gold_boots"
-   goldChestplate: "gold_chestplate"
-   goldHelmet: "gold_helmet"
-   goldHoe: "gold_hoe"
-   goldIngot: "gold_ingot"
-   goldLeggings: "gold_leggings"
-   goldNugget: "gold_nugget"
-   goldOre: "gold_ore"
-   goldPickaxe: "gold_pickaxe"
-   goldShovel: "gold_shovel"
-   goldSword: "gold_sword"
-   grass: "grass"
-   ironAxe: "iron_axe"
-   ironBoots: "iron_boots"
-   ironChestplate: "iron_chestplate"
-   ironHelmet: "iron_helmet"
-   iron_hoe: "iron_hoe"
-   ironIngot: "iron_ingot"
-   ironLeggings: "iron_leggings"
-   ironOre: "iron_ore"
-   ironPickaxe: "iron_pickaxe"
-   ironShovel: "iron_shovel"
-   ironSword: "iron_sword"
-   ladder: "ladder"
-   lapisLazuli: "lapis_lazuli"
-   lavaBucket: "lava_bucket"
-   leather: "leather"
-   leatherBoots: "leather_boots"
-   leatherChestplate: "leather_chestplate"
-   leatherHelmet: "leather_helmet"
-   leatherLeggings: "leather_leggings"
-   map: "map"
-   melonSlice: "melon_slice"
-   milkBucket: "milk_bucket"
-   minecart: "minecart"
-   musicDisk: "music_disk"
-   obdisian: "obdisian"
-   paper: "paper"
-   piston: "piston"
-   potion: "potion"
-   pumpkin: "pumpkin"
-   rails: "rails"
-   rawBeef: "raw_beef"
-   rawChicken: "raw_chicken"
-   rawFish: "raw_fish"
-   rawPorkchop: "raw_porkchop"
-   redstoneDust: "redstone_dust"
-   redstoneOre: "redstone_ore"
-   redstoneRepeater: "redstone_repeater"
-   redstoneTorch: "redstone_torch"
-   redstoneWire: "redstone_wire"
-   rottenBeef: "rotten_beef"
-   saddle: "saddle"
-   shears: "shears"
-   sign: "sign"
-   slimeball: "slimeball"
-   snowball: "snowball"
-   splashPotion: "splash_potion"
-   steak: "steak"
-   stick: "stick"
-   stickyPiston: "sticky_piston"
-   stone: "stone"
-   stoneAxe: "stone_axe"
-   stoneButton: "stone_button"
-   stoneHoe: "stone_hoe"
-   stonePickaxe: "stone_pickaxe"
-   stonePressurePlate: "stone_pressure_plate"
-   stoneShovel: "stone_shovel"
-   stoneSword: "stone_sword"
-   string: "string"
-   waterBottle: "water_bottle"
-   waterBucket: "water_bucket"
