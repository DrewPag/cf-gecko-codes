# cf-gecko-codes
Some gecko codes for Animal Crossing: City Folk

NOTE: Any behavior or spawn condition codes, including the updated Bug Randomizer, only work on Dolphin or by using Gecko to apply the codes on a Wii/Wii U. These codes will not work when launching the game from a homebrew application using a cIOS.

[cf_gecko_codes.txt](cf_gecko_codes.txt) contains all the gecko codes with short explanations + some comments

[bug_randomizer_2.0_codes_no_spider_bagworm](bug_randomizer_2.0_codes_no_spider_bagworm) contains pre-generated codes that DO NOT include spider/bagworm spawn conditions + behaviors. These behaviors may cause crashes under certain conditions... so for now, I generated these codes without those behaviors. However, spider and bagworm will still have randomized behaviors - so in total these codes have 3 additional random spawn conditions, compared to vanilla.

[bug_randomizer_2.0_codes](bug_randomizer_2.0_codes) contains pre-generated codes & mappings for the updated randomizer (randomized bug spawn conditions + behaviors). 100 each for USA and JPN

Bug Randomizer Notes
- Bee, Ant, and Flea are completely broken, so they are always vanilla. Their behaviors and spawn conditions will not be applied to other bugs.
- The spawn condition for Fly (spawning near spoiled tunrips/candy) is broken when applied to other bugs, so it is not in the pool.
  - However, Fly can spawn under other conditions (i.e. it does not have to be vanilla). As a result, there will be one extra bug spawning from one of the non-broken spawn conditions (i.e. not flea, or from tunrips/candy, or from a beehive) compared to the vanilla game.
- There is "vanilla prevention" to ensure no other bug rolls the exact same spawn condition and behavior. However, bugs may roll another spawn condition/behvaior that is essentially the same (ex. Fruit Beetle rolling another tree spawn condition/behavior)
- The weather restrictions for all bugs still apply. Snail will only spawn while it is raining. And any bugs that couldn't spawn in the rain before still can't spawn in the rain
- Spawn condition restrictions still apply in some cases:
  - Hybrid flower - if the peacock rolls another "spawns flying from flowers" spawn condition (most other butterflies), then it will still only spawn from a blue/blakc/purple hybrid flower
  - Red flower - same as above, but for Tiger Butterfly
  - White flower - if the orchid mantis rolls another "spawns on flowers" spawn condition (Mantis, ladybug, snail), then it will still only spawn on a white flower
- [Bugs that spawn in the tree don't drop down](https://clips.twitch.tv/ArborealRealGiraffeTheRinger-2-74Hmog-ATpoAi5) - they sort of just stay in place. If it's a small bug, it will be very hard to see...
  - [...but, you can use the camera to see if there is a bug there after shaking the tree](https://clips.twitch.tv/EncouragingAuspiciousFerretMau5-9QcgMd3JG4CrDFeO)

[RUUE01.txt](RUUE01.txt) - txt file with USA region codes in a format compatible with some loaders (?)

[RUUJ01.txt](RUUJ01.txt) - txt file with (most) JPN region codes in a format compatible with some loaders (?)

[RUUJ01.gct](RUUJ01.gct) - .gct file containing the original gecko codes. Does not include the randomizer 2.0

You can convert .txt file codes to .gct by using the [Gecko Code Manager](https://www.zeldacodes.org/downloads/code-manager)
