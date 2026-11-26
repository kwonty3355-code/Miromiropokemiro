# Land / Territory Expansion Design (개척) — endless, meaningful, balanced

Research conditions (read first):
- The search tool worked, but most fetches failed. These hosts are outside the session's allowed network: techraptor.net, clashofclans.fandom.com, wiki.hoodedhorse.com, wiki.factorio.com. Many findings below therefore come from **search-result snippets** (marked [snippet]) and not from full pages. Treat the specifics as secondhand until checked.
- Items marked **[unverified background]** come from the researcher's general knowledge of these games, not from a source fetched this session. They sit only under Inferences or Gaps and must be checked before they are used as facts.
- Context: monster farm + Minecraft Create-style factory, 3rd-person base. Expansion is driven by eyes-free repetitive controller input in an "anime mode". It must be endless and unautomatable, must not break factory math, must give real (non-cosmetic) benefit, and must not add growing multipliers.

---

## Q1. How do games handle base/land expansion?

### Takeaway
There are roughly five families of designs:
1. **Pay-to-unlock fixed plots**: Hay Day/Township, Rusty's Retirement, Slime Rancher.
2. **Obstacle clearing with tool items**: Hay Day/Township, Clash of Clans.
3. **Land that is free but defended or hazardous**: Factorio, Against the Storm, Kingdom.
4. **Score-gated new maps**: Islanders.
5. **Diggable infinite worlds**: Core Keeper, Terraria/Minecraft.

In the published designs that get the most praise, land is a **constraint/space** resource and not a direct producer. The value of land comes from what it *contains* or *enables*: nodes, special terrain, room for layouts.

### Cited Findings
**Hay Day (tool-gated obstacle clearing + expansions)**
- Each clearing tool matches one obstacle type: saws for large trees, axes for small trees, TNT for large rocks, dynamite for small rocks, and shovels for swampy ponds and logs. Using these tools grants XP. — [PocketGamer: Hay Day TNT/shovels/pickaxes & expansions](https://www.pocketgamer.com/hay-day/hay-day-how-to-get-tnt-shovels-pickaxes-and-unlock-expansions) [snippet]; same mapping in [PocketGamer getting started tips](https://www.pocketgamer.com/hay-day/hay-day-getting-started-tips-hints) [snippet]
- Tools are a bottleneck for expansions: players "can be held up waiting to luck out" on getting access to Axes, Dynamite, Pickaxes, Saws, Shovels and TNT. — [PocketGamer: free coins/tools](https://www.pocketgamer.com/hay-day/hay-day-how-to-quickly-earn-more-free-coins-or-tools-for-your-farm) [snippet]
- Expansions need deeds and expansion materials, a separate currency layer. — [androidguias guide](https://en.androidguias.com/writings-there-is-day/) [snippet, title only]

**Township (sister design)**
- Clearing new expansions takes saws, shovels and axes. — [Playrix Township FAQ](https://playrix.helpshift.com/hc/en/3-township/faq/157-production-time) [snippet]

**Evergrove (Pixelberry)**
- "Trees only respond to axes, and rocks only respond to pickaxes." This is a strict tool-type match. — [Pixelberry Evergrove FAQ](https://pixelberrystudios.helpshift.com/hc/en/8-evergrove/faq/1228-how-do-i-use-my-tools-to-clear-trees-and-rocks) [snippet]

**Clash of Clans (respawning obstacles)**
- Vegetation respawns. Removing it can drop gems, so regular removal is "an unlimited (although sometimes slow) source of Gems." — [CoC Wiki: Obstacles/Home Village](https://clashofclans.fandom.com/wiki/Obstacles/Home_Village) [snippet; full fetch blocked]
- One guide says obstacles spawn every eight hours in both villages. — [Sportskeeda: farm gems faster](https://www.sportskeeda.com/esports/5-ways-farm-gems-faster-clash-clans) [snippet; secondary source]
- Removing plants costs Elixir and removing rocks costs Gold. Per one source, rocks never drop gems. — [Sportskeeda gem guide](https://www.sportskeeda.com/esports/clash-clans-gems-guide-best-ways-earn-spend) [snippet]
- Yield per removal is about 0–6 gems plus XP. One example averages about 1 gem per obstacle. — [1337wiki CoC](https://clash-of-clans.1337wiki.com/?p=212) [snippet]
- The Gem Box obstacle is 2x2 with a 30s removal time and gives 25 gems and 5 XP, with 1% respawn weight. A claim that it appears "once every week" conflicts with that low weight and is unconfirmed. — [CoC Wiki](https://clashofclans.fandom.com/wiki/Obstacles/Home_Village) [snippet]; [cocmap daily obstacles](https://cocmap.com/read/comparing-daily-obstacles-which-give-the-most-free-gems-over-time) [snippet]

**Rusty's Retirement (idle farm, fixed plot purchases)**
- Each locked area shows its purchase cost under a bulldozer icon. After you pay, Rusty or Haiku clears the junk and extends the farm. — [Pro Game Guides](https://progameguides.com/rustys-retirement/how-to-unlock-every-farm-in-rustys-retirement/) [snippet]; [Dot Esports](https://dotesports.com/indies/news/how-to-unlock-all-farm-types-in-rustys-retirement) [snippet]
- Full expansion costs 142,000 scraps per [Dot Esports](https://dotesports.com/indies/news/how-to-unlock-all-farm-types-in-rustys-retirement). [Pro Game Guides](https://progameguides.com/rustys-retirement/how-to-unlock-every-farm-in-rustys-retirement/) instead says four expansions per side totalling about 192,000. **The sources conflict** (possibly different versions). [snippets]
- Fully expanding one farm unlocks the next farm type. Expansion caps out and then converts into a new map, which is a "prestige-like" handoff. — [Pro Game Guides](https://progameguides.com/rustys-retirement/how-to-unlock-every-farm-in-rustys-retirement/) [snippet]

**Slime Rancher (fixed expansion plots with special properties)**
- The Overgrowth is a closed-in plateau with natural food nodes and chicken spawns, "ideal for free ranging". — [Slime Rancher Wiki: Overgrowth](https://slimerancher.fandom.com/wiki/Overgrowth) [snippet]
- The Grotto is a cave expansion where Phosphor Slimes can be corralled without a Solar Shield. **The new land's value is a terrain property that changes which creatures you can keep**, not raw space. — [Slime Rancher Wiki: The Ranch](https://slimerancher.fandom.com/wiki/The_Ranch) [snippet]
- Expansions chain off each other: Ogden's Retreat needs a gate unlocked *and* the Overgrowth purchased, and Mochi's Manor needs the Indigo Quarry gate *and* the Grotto. — [SR Wiki: Ogden's Retreat](https://slimerancher.fandom.com/wiki/Ogden%27s_Retreat); [SR Wiki: Mochi's Manor](https://slimerancher.fandom.com/wiki/Mochi%27s_Manor) [snippets]
- I found no price figures for the original game's plots this session.

**Palworld (hard base cap; expand by count, not radius)**
- Vanilla has no way to expand base radius. You expand by building more bases. — [Siliconera: expand your base](https://www.siliconera.com/how-to-expand-your-base-in-palworld/) [snippet]; [allthings.how](https://allthings.how/palworld-how-to-increase-base-size-and-build-beyond-the-palbox-border/) [snippet]
- One guide gives a vanilla maximum of 3 bases. Base level unlocks more working Pals and more base locations. — [SI.com: Palworld max bases](https://videogames.si.com/guides/palworld-max-bases) [snippet]; [Palworld wiki.gg: Bases](https://palworld.wiki.gg/wiki/Bases) [snippet]
- Default base range is 70 per mod pages. Mods expand the radius, and one ties it to base level (+200 per level). Players clearly want bigger bases, and the devs cap them. — [CurseForge: Better Base Range](https://www.curseforge.com/palworld/lua-code-mods/better-base-range) [snippet]; [Nexus mod 4011](https://www.nexusmods.com/palworld/mods/4011) [snippet]

**Factorio (land free, defended)**
- The pollution cloud triggers biter attacks and sets their size. — [Factorio Wiki: Pollution](https://wiki.factorio.com/Pollution) [snippet]
- Evolution has three factors: time, spawner destruction and pollution. Higher evolution means stronger enemy tiers and more HP. — [Factorio Wiki: Evolution](https://wiki.factorio.com/Evolution) [snippet]; [Factorio forum](https://forums.factorio.com/viewtopic.php?p=487291) [snippet]
- One player says biter expansion is "purely time-based". Exploring does not trigger it but gives biters more room, and unchecked "biters will fill in all the explored area with nests". — [Factorio forums](https://forums.factorio.com/viewtopic.php?p=540600) [snippet; player claim, not official]

**Kingdom series (2D side-scroll: clear forest to extend walls)**
- Nearby trees can block wall building. After forest removal a dirt mound may appear, and walls need coins plus builders. (Wiki page covers Classic/New Lands, not necessarily Two Crowns.) — [Kingdom Wiki: Walls](https://kingdomthegame.fandom.com/wiki/Walls?oldid=8079) [snippet]
- An App Store reviewer cleared the whole forest on island 1, then ran out of builders because enemies take builders' hammers, and had to restart. Over-expanding has a defensive cost. — [App Store: Kingdom Two Crowns](https://apps.apple.com/us/app/kingdom-two-crowns/id1616673187) [snippet; anecdotal]

**Islanders (score-gated new maps)**
- Reaching a score threshold unlocks a larger island. You can also stay and keep raising your score. — [Inverse: Islanders New Shores](https://www.inverse.com/gaming/islanders-new-shores-nintendo-switch-xbox-playstation-pc) [snippet]
- In the original Islanders, the points needed to restock and move to a new island rise with each unlock. — [Inverse](https://www.inverse.com/gaming/islanders-new-shores-nintendo-switch-xbox-playstation-pc) [snippet]

**Core Keeper (dig-to-expand, infinite)**
- The world is square tiles of dirt and other materials. You dig to explore and gather, and ore blocks glitter to guide digging. Players dig tunnels outward from the Core. — [Wikipedia: Core Keeper](https://en.wikipedia.com/wiki/Core_Keeper) [snippet]
- You start boxed in by a Great Wall. Activating the Core reveals new biomes and an infinitely generated map. — [Gamepur: edge of the map](https://vip-develop.gamepur.com/?p=377118) [snippet]
- Infinite outer biomes (Azeos' Wilderness, Sunken Sea, Desert of Beginnings) start about 520 tiles out, in randomized angular segments. — [atma.gg Core Keeper wiki: World](https://corekeeper.atma.gg/en/World) [snippet]. The [shapes.inc mirror](https://www.shapes.inc/fandom/core-keeper/biomes) instead describes concentric rings. **The two sources conflict on layout.**

### Inferences
- For "must not break factory math", the most relevant designs are **Slime Rancher** (land = terrain property) and **Palworld** (land = a fixed cap of space). Neither lets land itself produce output. The output still comes from what the player builds or keeps there.
- Hay Day and Clash of Clans attach rewards (XP, gems) to *each clearing action*. That works as a steady drip but brings in exactly the economy coupling the user wants to avoid. If copied, the per-clear reward should be non-economic: cosmetics, lore, collection entries, or space.
- [unverified background] Stardew Valley's farm map is fixed. Expansion comes as new *specialized* spaces (Greenhouse = season-free crops; Ginger Island farm = season-free tropical land) and not more of the same land. "Expansion = new rule-space" is another way to stay meaningful without endless output.
- [unverified background] Anno: new islands carry specific fertilities (e.g., only some islands grow certain crops), so expansion unlocks *kinds* of production. Volume comes from building there and costs workforce and upkeep.

### Gaps
- Exact Township/Hay Day expansion cost curves: the search returned irrelevant real-world township pages.
- Timberborn, Satisfactory, Dorfromantik, Townscaper, Settlers, Ooblets, Dinkum, Minecraft Create base growth, and the idle games Idle Miner and Unnamed Space Idle were not searched within the 15-call budget. No sourced facts.
- Slime Rancher plot prices were not found.

---

## Q2. Endless vs. finite expansion; how to avoid "infinite land = infinite production"

### Takeaway
Endless designs keep the economy in check with one or more of five levers:
- **External pressure that scales**: Factorio pollution and evolution; Kingdom raiders.
- **Rising unlock cost**: Islanders score thresholds; Rusty's tiers.
- **Hard caps that convert into new maps or prestige**: Rusty's Retirement (full expansion unlocks the next farm); Palworld's base count.
- **Content-limited value**: land matters for what it holds, such as Slime Rancher's terrain properties or Core Keeper's ores and biomes.
- **Diminishing marginal value**: more empty space is worth less once your layout fits.

### Cited Findings
- Factorio: production creates pollution, and pollution triggers attacks sized by absorbed pollution. — [Factorio Wiki: Pollution](https://wiki.factorio.com/Pollution) [snippet]
- Factorio: one wave from 1350 absorbed pollution is 6 small biters + 1 medium, or 6 small spitters + 2 medium, depending on spawner and evolution. — [Factorio Wiki: Pollution](https://wiki.factorio.com/index.php?title=Pollution) [snippet]
- Factorio: trees and ground absorb pollution, which slows pollution-driven evolution. Untouched land therefore has a *functional* buffer value. — [Factorio forum](https://forums.factorio.com/viewtopic.php?p=289059) [snippet; player claim]
- Factorio: the pollution, time and destroy factors are map settings, and pollution can be turned off. The devs treat pressure as a tunable dial. — [Factorio Wiki: Pollution](https://wiki.factorio.com/pollution) [snippet]; [Lua API: EnemyEvolutionSettings](https://lua-api.factorio.com/latest/types/MapGenPresetEnemyEvolutionSettings.html) [title]
- Islanders: thresholds rise with each island unlock. — [Inverse](https://www.inverse.com/gaming/islanders-new-shores-nintendo-switch-xbox-playstation-pc) [snippet]
- Rusty's Retirement: expansion is finite per farm, and completing it unlocks a new farm type. — [Pro Game Guides](https://progameguides.com/rustys-retirement/how-to-unlock-every-farm-in-rustys-retirement/) [snippet]
- Palworld: base radius is fixed, and base count is capped at about 3 by default. — [SI.com](https://videogames.si.com/guides/palworld-max-bases) [snippet]
- Clash of Clans: obstacles respawn endlessly, but rewards are tiny (about 1 gem average) and random. This is an endless loop with negligible economic weight. — [1337wiki](https://clash-of-clans.1337wiki.com/?p=212) [snippet]
- Core Keeper: the map is infinite past the wall, but value comes from biome-specific materials and bosses, not area. — [Fandom: Biomes](https://core-keeper.fandom.com/wiki/Biomes) [snippet]

### Inferences
- **Separate "space" from "output".** If the factory's throughput is capped by things land doesn't supply (machine tiers, monster count, power, recipe speed), extra land only gives layout freedom. That meets "helps the base" without moving the factory math.
- **Ring-based or tiered expansion with rising effort** (Islanders-style thresholds, Core Keeper-style distance rings) gives endlessness. The marginal effort per tile grows, while the marginal benefit per tile flattens once layouts fit. This is a natural soft cap without hard walls.
- **Cap-then-convert** (Rusty's Retirement) is a clean answer to "endless but not inflationary": once a zone is finished, new effort opens a *different kind* of zone, not more of the same.
- Pressure systems (Factorio biters, Kingdom raiders) violate the user's "no fail" constraint, so they are not directly usable. But the idea of **"land has a non-production cost"** can be kept in passive forms such as upkeep-free yet layout-bound decoration space.
- One way to give land real value without multipliers: each cleared cell yields a **one-time, non-renewable** thing. Examples: a stash of building materials, a monster-habitat property, a blueprint fragment. Nothing on it is a perpetual output node.

### Gaps
- No sourced data on idle games (Idle Miner, Unnamed Space Idle) and how they balance infinite map growth.
- No sourced dev postmortem (GDC/Game Developer) on land expansion balance. Searches were not run within budget.

---

## Q3. What do new lands contain, and is it revealed at once or gradually?

### Takeaway
Contents range across:
- **empty build space** (Rusty's Retirement, Palworld)
- **space plus special terrain properties** (Slime Rancher Overgrowth/Grotto)
- **resource nodes and biomes** (Core Keeper, Factorio)
- **authored events with risk/reward** (Against the Storm glades)

Gradual reveal through forest cutting or digging creates anticipation. Purchase-revealed plots show everything up front.

### Cited Findings
- Against the Storm: glades come in tiers. Small/standard glades usually hold no major threat, dangerous glades always contain at least one threat, and forbidden glades carry the most severe events. — [TechRaptor glades guide](https://techraptor.net/gaming/guides/against-the-storm-glades-guide) [snippet; fetch blocked]
- Against the Storm: opening dangerous or forbidden glades raises Hostility. One effect (Release Empathy) adds +2 hostility per opened dangerous/forbidden glade. — [Hooded Horse wiki: Glade Events](https://wiki.hoodedhorse.com/Against_the_Storm/Dangerous_Glade_Event) [snippet; fetch blocked]
- Against the Storm: players say forbidden glades often give better rewards, with events "only slightly harder". Others argue that opening only dangerous glades and skipping small ones is optimal. — [Steam discussion](https://steamcommunity.com/app/1336490/discussions/0/3946902677727091217) [snippet; player opinion]; [Steam discussion](https://steamcommunity.com/app/1336490/discussions/0/4137186326777798145) [snippet]
- Against the Storm: a dev said that in Update 1.1 the Secure Perimeter cornerstone's hostility bonus triggers only after solving a forbidden glade event, and that players often confuse dangerous and forbidden glades. — [Steam discussion](https://steamcommunity.com/app/1336490/discussions/4/4039231802322438173) [snippet]
- The wiki has separate event lists for Settler and Pioneer glade events (e.g., "Small Encampment"). Glade contents are authored event pools. — [Hooded Horse wiki: Pioneer Glade Events](https://wiki.hoodedhorse.com/Against_the_Storm/Pioneer_Glade_Events); [Small Encampment](https://wiki.hoodedhorse.com/Against_the_Storm/Small_Encampment) [titles/snippets]
- Core Keeper: gradual tile-by-tile reveal by digging, with glittering ore as a directional hint. — [Wikipedia: Core Keeper](https://en.wikipedia.com/wiki/Core_Keeper) [snippet]
- Slime Rancher: expansions contain fixed, known features (food nodes, chicken spawns, cave shade). — [SR Wiki: Overgrowth](https://slimerancher.fandom.com/wiki/Overgrowth) [snippet]
- Rusty's Retirement: the purchased land is junk-cleared empty farm space. — [Dot Esports](https://dotesports.com/indies/news/how-to-unlock-all-farm-types-in-rustys-retirement) [snippet]
- Clash of Clans: obstacle contents are hidden until removed (0 gems or some gems). The rare Gem Box is a visible jackpot obstacle. — [CoC Wiki](https://clashofclans.fandom.com/wiki/Obstacles/Home_Village) [snippet]

### Inferences
- The **Against the Storm** model is the strongest example of "clearing = discovery". Cutting forest opens a glade with an authored event, cache or resource. But its events need decisions and carry failure risk, which conflicts with the anime-mode constraints. An adapted version would resolve the *clearing* eyes-free and *bank* the discovery (e.g., "a ruin was found"), so the player inspects or resolves it whenever they like, with no timer. Against the Storm's glade events do have timers [unverified background], so the timer would have to be removed.
- **Glitter hints** (Core Keeper) are a cheap way to make gradual reveal feel directed without requiring decisions.
- For a monster farm, Slime Rancher's pattern fits well: **new land = new habitat conditions** (cave, wetland, high plateau) that let a different monster type live there. This benefit is real, but it adds variety, not volume.

### Gaps
- Full Against the Storm glade content lists (resource deposits, caches, ruins, event timers) could not be fetched.
- [unverified background, needs sourcing] In Against the Storm, woodcutters cut forest tiles, and reaching a glade boundary opens it. Forest density and "dangerous" status show on the map before opening, which is a partial-reveal design.
- Dorfromantik's tile quests and Timberborn's map structure were not researched.

---

## Q4. Manual-only vs. automatable clearing, and why

### Takeaway
The few sourced cases point to three patterns:
- Clearing that is a **paid, gated action** (Hay Day tools, Clash of Clans resources, Rusty's purchase) is effectively manual and limited by currency.
- Clearing that is **worker-driven** (Against the Storm woodcutters, Kingdom builders, Rusty/Haiku bots) is "automated" but bounded by worker supply and risk.
- **Hard-capped** systems (Palworld) avoid the question entirely.

I found no sourced developer statement explaining *why* clearing is kept manual.

### Cited Findings
- Hay Day: clearing needs consumable tools that drop by luck, which is the real throttle. — [PocketGamer](https://www.pocketgamer.com/hay-day/hay-day-how-to-quickly-earn-more-free-coins-or-tools-for-your-farm) [snippet]
- Clash of Clans: removal costs Elixir or Gold and occupies a builder for a duration (a 30s example for the Gem Box). — [CoC Wiki](https://clashofclans.fandom.com/wiki/Obstacles/Home_Village) [snippet]
- Kingdom: clearing and walls use builders and coins. Losing builders' hammers to enemies can stall expansion. — [Kingdom Wiki: Walls](https://kingdomthegame.fandom.com/wiki/Walls?oldid=8079); [App Store review](https://apps.apple.com/us/app/kingdom-two-crowns/id1616673187) [snippets]
- Rusty's Retirement: once paid, the bots do the clearing automatically. Gold gates it, not labor. — [Pro Game Guides](https://progameguides.com/rustys-retirement/how-to-unlock-every-farm-in-rustys-retirement/) [snippet]
- Core Keeper: digging is player-tool labor. — [Wikipedia](https://en.wikipedia.com/wiki/Core_Keeper) [snippet]

### Inferences
- In free-to-play games the throttle is usually a **scarce consumable** (tools, deeds), which ties expansion to the economy and to monetization. The user's design instead wants a throttle tied to **player time in anime mode**. That pattern is closer to "labor-gated" (Core Keeper digging) than "currency-gated".
- To keep anime-mode clearing unautomatable inside a Create-style factory, the clearing "work" should be a resource the factory **cannot produce**: a per-player "pioneering effort" that only anime-mode input generates. Factory machines then have no recipe that substitutes for it, and land expansion stays out of the production graph.
- The risk to watch: if anime-mode effort can be spent on anything *besides* land, it becomes a currency and will be min-maxed. Keeping it single-purpose (land only) avoids that.

### Gaps
- No sourced GDC/Game Developer article explains the design reasons for manual vs. automated clearing.
- [unverified background] Minecraft Create players clear land with mechanical drills, deployers and contraptions, and Factorio uses bots to deconstruct trees and rocks. Factory games tend to let clearing be automated because clearing is not the gated resource there. Needs sourcing.

---

## Q5. Expansion driven by player time/effort, independent of economy

### Takeaway
I found no sourced example of a pure "survey/exploration points" land currency within budget. The closest sourced analogues are:
- Islanders: **score thresholds**, earned from play quality and not currency.
- Core Keeper: **labor-only digging**.
- Clash of Clans: **endless, slow, low-value obstacle respawn**.

### Cited Findings
- Islanders: new islands unlock from points, with rising thresholds. The currency is play performance, not stockpiled resources. — [Inverse](https://www.inverse.com/gaming/islanders-new-shores-nintendo-switch-xbox-playstation-pc) [snippet]
- Core Keeper: expansion is pure digging effort through tiles, with infinite generation past the wall. — [Gamepur](https://vip-develop.gamepur.com/?p=377118); [Wikipedia](https://en.wikipedia.com/wiki/Core_Keeper) [snippets]
- Clash of Clans: obstacle removal is a slow, endless, effort-based drip of small rewards. — [CoC Wiki](https://clashofclans.fandom.com/wiki/Obstacles/Home_Village) [snippet]
- Factorio: one player says enemy expansion is time-based, not exploration-based. "Time" is used as an independent driver there too, though for pressure and not reward. — [Factorio forums](https://forums.factorio.com/viewtopic.php?p=540600) [snippet; player claim]

### Inferences (design candidates for the user's anime mode)
- **Effort-meter land**: anime-mode input fills a "pioneering progress" bar, the only currency that opens new land. Each tile costs more effort the farther it is from the core (ring cost curve). This is endless and scales effort, not output.
- **Bank-and-inspect reveals** (adapted Against the Storm): completed clearings queue discoveries such as ruins, habitats or one-time caches. The player views them whenever they like, with no timers and no failure.
- **Value without multipliers**: new land offers (a) build space, (b) habitat or terrain properties that unlock which monsters can live there (Slime Rancher), and (c) one-time material caches. It never offers perpetual output nodes, or if it does, they are capped by existing production limits.
- **Cap-then-convert** (Rusty's): finishing one biome ring opens a new biome type instead of more of the same.
- **Factorio-style buffer value**: untouched forest/fog could carry a passive role, but anything that pressures the player conflicts with the "no fail" constraint and should be avoided.

### Gaps
- No sourced idle-game examples. Rusty's Retirement plot expansion is currency-gated, not time-gated.
- No sourced examples of fog-of-war reveal driven by a non-economic "exploration point" currency (e.g., 4X scouting) were collected.
- Timberborn, Satisfactory, Terraria, Dinkum and Ooblets expansion mechanics remain unresearched in this session because of the tool budget and blocked fetch hosts.
