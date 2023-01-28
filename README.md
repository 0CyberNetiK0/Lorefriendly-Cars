# Lore friendly Cars
A collection of high rated lore friendly vehicles from GTA5-mods. This pack contains add-on, replace and tuning cars and sounds.
* All cars except the `zion4` run at <40 MiB of physical memory. `zion4` runs at 49 MiB of physical memory.
* Handling files are mostly lore friendly. If you do anything with the files and want to make a PR, feel free!
* Quality models and sounds. 

# Important ⚠️
* All credits to go the original creators of these vehicles. These vehicles may be removed from the pack if the owners will it.
* Treat all vehicles in this pack as the following: *Modifying this package and it's contents except the text data such as handling, meta files and mod-kit, uploading or hosting it elsewhere as is or in a modified state and selling, paywalling or monetizing in any shape or form is prohibited.*
* Most of these cannot be used as one of one's or as donator cars.

# Install
* Drag and drop
* Ensure Lorefriendly-Cars

# For use of sounds
* Drag [lf-cars-sounds] into your `resources` folder
* Ensure [lf-cars-sounds] in your server CFG

# Support
* I will not offer support on any of these vehicles, everything on my part is in the README. If you want to change any handling files (which for some it's needed), you need to configure it yourself.

# Adding cars to dealerships
* Add to `qb-core/shared/vehicles.lua` make sure to change the prices on these (it's only 30 cars, how bad could it be?)
```lua
-- Lorefriendly-Cars
    ['akumac'] = {
		['name'] = 'Akuma Classic',
		['brand'] = 'Dinka',
		['model'] = 'akumac',
		['price'] = 1,
		['category'] = 'motorcycles',
		['hash'] = `akumac`,
		['shop'] = 'pdm',
    },
    ['atlas'] = {
		['name'] = 'Atlas',
		['brand'] = 'Karin',
		['model'] = 'atlas',
		['price'] = 1,
		['category'] = 'suvs',
		['hash'] = `atlas`,
		['shop'] = 'pdm',
    },
    ['baller7r'] = {
		['name'] = 'Baller Raid',
		['brand'] = 'Gallivanter',
		['model'] = 'baller7r',
		['price'] = 1,
		['category'] = 'suvs',
		['hash'] = `baller7r`,
		['shop'] = 'pdm',
    },
    ['buffalo4h'] = {
		['name'] = 'Buffalo Hellfire',
		['brand'] = 'Bravado',
		['model'] = 'buffalo4h',
		['price'] = 1,
		['category'] = 'sports',
		['hash'] = `buffalo4h`,
		['shop'] = 'luxury',
    },
    ['burritor'] = {
		['name'] = 'Burrito Racing',
		['brand'] = 'Declasse',
		['model'] = 'burritor',
		['price'] = 1,
		['category'] = 'vans',
		['hash'] = `burritor`,
		['shop'] = 'pdm',
    },
    ['cheetahfel'] = {
		['name'] = 'Cheetah Veloce',
		['brand'] = 'Grotti',
		['model'] = 'cheetahfel',
		['price'] = 1,
		['category'] = 'sportsclassics',
		['hash'] = `cheetahfel`,
		['shop'] = 'luxury',
    },
    ['clique2'] = {
		['name'] = 'Clique Deluxe',
		['brand'] = 'Vapid',
		['model'] = 'clique2',
		['price'] = 1,
		['category'] = 'coupes',
		['hash'] = `clique2`,
		['shop'] = 'pdm',
    },
    ['coquette4c'] = {
		['name'] = 'Coquette D10 Widebody',
		['brand'] = 'Invetero',
		['model'] = 'coquette4c',
		['price'] = 1,
		['category'] = 'sports',
		['hash'] = `coquette4c`,
		['shop'] = 'luxury',
    },
	['dominatorgtc'] = {
		['name'] = 'Dominator GTC',
		['brand'] = 'Vapid',
		['model'] = 'dominatorgtc',
		['price'] = 1,
		['category'] = 'muscle',
		['hash'] = `dominatorgtc`,
		['shop'] = 'pdm',
    },
    ['elegant'] = {
		['name'] = 'Elegant',
		['brand'] = 'Willard',
		['model'] = 'elegant',
		['price'] = 1,
		['category'] = 'sedans',
		['hash'] = `elegant`,
		['shop'] = 'pdm',
    },
    ['eva'] = {
		['name'] = 'EVA',
		['brand'] = 'Hijak',
		['model'] = 'eva',
		['price'] = 1,
		['category'] = 'compacts',
		['hash'] = `eva`,
		['shop'] = 'pdm',
    },
    ['f620s2'] = {
		['name'] = 'F620 Sleeper',
		['brand'] = 'Ocelot',
		['model'] = 'f620s2',
		['price'] = 1,
		['category'] = 'sports',
		['hash'] = `f620s2`,
		['shop'] = 'luxury',
    },
    ['gauntletstx'] = {
		['name'] = 'Gauntlet STX',
		['brand'] = 'Bravado',
		['model'] = 'gauntletstx',
		['price'] = 1,
		['category'] = 'muscle',
		['hash'] = `gauntletstx`,
		['shop'] = 'pdm',
    },
	['glendalelimo'] = {
		['name'] = 'Glendale Stretch',
		['brand'] = 'Karin',
		['model'] = 'glendalelimo',
		['price'] = 1,
		['category'] = 'sedans',
		['hash'] = `glendalelimo`,
		['shop'] = 'luxury',
    },
    ['gstyosemite1'] = {
		['name'] = 'Yosemite DRT',
		['brand'] = 'Declasse',
		['model'] = 'gstyosemite1',
		['price'] = 1,
		['category'] = 'offroad',
		['hash'] = `gstyosemite1`,
		['shop'] = 'pdm',
    },
    ['hotwee'] = {
		['name'] = 'Hotring Weevil',
		['brand'] = 'BF',
		['model'] = 'hotwee',
		['price'] = 1,
		['category'] = 'compacts',
		['hash'] = `hotwee`,
		['shop'] = 'pdm',
    },
    ['italigts'] = {
		['name'] = 'Itali GTS',
		['brand'] = 'Grotti',
		['model'] = 'italigts',
		['price'] = 1,
		['category'] = 'sports',
		['hash'] = `italigts`,
		['shop'] = 'luxury',
    },
    ['kawaii'] = {
		['name'] = 'Kawaii',
		['brand'] = 'Annis',
		['model'] = 'kawaii',
		['price'] = 1,
		['category'] = 'sports',
		['hash'] = `kawaii`,
		['shop'] = 'luxury',
    },
    ['panorama'] = {
		['name'] = 'Panorama',
		['brand'] = 'Classique',
		['model'] = 'panorama',
		['price'] = 1,
		['category'] = 'sedans',
		['hash'] = `panorama`,
		['shop'] = 'pdm',
    },
	['paradox'] = {
		['name'] = 'Paradox',
		['brand'] = 'Willard',
		['model'] = 'paradox',
		['price'] = 1,
		['category'] = 'muscle',
		['hash'] = `paradox`,
		['shop'] = 'pdm',
    },
    ['paradox2'] = {
		['name'] = 'Paradox',
		['brand'] = 'Willard',
		['model'] = 'paradox2',
		['price'] = 1,
		['category'] = 'muscle',
		['hash'] = `paradox2`,
		['shop'] = 'pdm',
    },
    ['peanut'] = {
		['name'] = 'Peanut',
		['brand'] = 'Weeny',
		['model'] = 'peanut',
		['price'] = 1,
		['category'] = 'compacts',
		['hash'] = `peanut`,
		['shop'] = 'pdm',
    },
	['roxanne'] = {
		['name'] = 'Roxanne',
		['brand'] = 'Annis',
		['model'] = 'roxanne',
		['price'] = 1,
		['category'] = 'tuner',
		['hash'] = `roxanne`,
		['shop'] = 'luxury',
    },
    ['sheavas'] = {
		['name'] = 'Sheava',
		['brand'] = 'Emperor',
		['model'] = 'sheavas',
		['price'] = 1,
		['category'] = 'sports',
		['hash'] = `sheavas`,
		['shop'] = 'luxury',
    },
    ['stardust'] = {
		['name'] = 'Stardust',
		['brand'] = 'Pfister',
		['model'] = 'stardust',
		['price'] = 1,
		['category'] = 'sportsclassics',
		['hash'] = `stardust`,
		['shop'] = 'luxury',
    },
	['streiter2'] = {
		['name'] = 'Streiter',
		['brand'] = 'Benefactor',
		['model'] = 'streiter2',
		['price'] = 1,
		['category'] = 'coupes',
		['hash'] = `streiter2`,
		['shop'] = 'pdm',
    },
	['sunrise1'] = {
		['name'] = 'Sunrise R',
		['brand'] = 'Maibatsu',
		['model'] = 'sunrise1',
		['price'] = 1,
		['category'] = 'tuner',
		['hash'] = `sunrise1`,
		['shop'] = 'luxury',
    },
	['vigout'] = {
		['name'] = 'Vigero Outlaw',
		['brand'] = 'Declasse',
		['model'] = 'vigout',
		['price'] = 1,
		['category'] = 'offroad',
		['hash'] = `vigout`,
		['shop'] = 'pdm',
    },
    ['vulture'] = {
		['name'] = 'Vulture',
		['brand'] = 'Bravado',
		['model'] = 'vulture',
		['price'] = 1,
		['category'] = 'muscle',
		['hash'] = `vulture`,
		['shop'] = 'pdm',
    },
    ['zion4'] = {
		['name'] = 'Zion Classic Custom',
		['brand'] = 'Übermacht',
		['model'] = 'zion4',
		['price'] = 1,
		['category'] = 'tuner',
		['hash'] = `zion4`,
		['shop'] = 'luxury',
    },
    ```
    
