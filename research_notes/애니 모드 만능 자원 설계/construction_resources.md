# Construction-only vs. production resources in factory and economy games (build costs, refunds, scaling, and redesign)

Context for the writer: the target game is a monster farm plus a Minecraft Create-style factory (shafts, gears, RPM, stress, ratio math). The handmade universal resource "실타래" (thread skein) is earned only in an eyes-free "anime mode". It must never be a production input, it has no daily caps, and rebuilding must not be punished.

Research method note: wiki.hoodedhorse.com, wiki.factorio.com, en.wikipedia.org, timberborn.featureupvote.com and ideas.captain-of-industry.com all failed DNS in this session. They are outside the allowed network. Claims from those sites therefore come from search-result snippets and are marked [snippet]. Facts I know from general game knowledge but could not verify with a source in this session are kept in Inferences or Gaps and labelled "(unverified, general knowledge)".

## Q1. Concrete examples: build-only resources vs. buildings made from the factory's own outputs

### Takeaway
Games fall on a spectrum:
- **Build cost made of the factory's own outputs:** Factorio, Satisfactory, Create's andesite alloy. Building and production compete for the same items.
- **Dedicated construction-material goods:** Anno, Against the Storm. These goods are produced by the economy but mostly spent on placement, and in Against the Storm they also feed production.
- **Fully non-producible or no build currency:** shapez 2 has no costs at all. Islanders and Dorfromantik give out buildings or tiles as rewards for scoring.

The 실타래 design is a fourth variant: a build currency that comes from outside the factory, which almost no factory game uses. The closest analogues are the Islanders and Dorfromantik reward stacks and Kingdom Two Crowns coins.

### Cited Findings
- **Against the Storm: building materials feed production too.** A Human House costs 4 Planks + 2 Bricks; a Guild House costs 10 Planks + 6 Fabric — [Against the Storm wiki, Building Materials [snippet]](https://wiki.hoodedhorse.com/Against_the_Storm/Building_Materials)
- **Against the Storm Workshop.** Its recipes produce Planks, Fabric and Bricks (each ★★) and Pipes (☆). So building materials are produced goods, made in the same production buildings as everything else — [ATS wiki, Workshop [snippet]](https://hoodedhorse.com/wiki/Against_the_Storm/Workshop)
- **Against the Storm Fabric page.** Fabric has its own goods page. In ATS, Fabric, Planks and Bricks also appear as inputs to other recipes and to trade, so they are not purely build-only — [ATS wiki, Fabric [snippet]](https://hoodedhorse.com/wiki/Against_the_Storm/Fabric); [Pack of Building Materials [snippet]](https://hoodedhorse.com/wiki/Against_the_Storm/Pack_of_Building_Materials)
- **Against the Storm hidden stock.** A Steam thread notes that "when you need planks you may not know they're sitting in a production building". Construction demand collides with production storage — [Steam discussion [snippet]](https://steamcommunity.com/app/1336490/discussions/0/4039231211457190088/?l=italian)
- **Anno 1800.** Buildings cost coins plus construction goods, for example a Depot at 2500 coins + 10 planks + 10 bricks. Construction goods (timber, bricks, steel beams, windows and so on) are produced by production chains — [SegmentNext Anno 1800 buildings guide [snippet]](https://segmentnext.com/guides/anno-1800-buildings-guide)
- **Create mod: andesite alloy is the build-cost bottleneck.** It is "a material used in Andesite Casing and simple kinetic blocks, which serves as an entry-point to the mechanical components of Create" — [Create wiki (GitHub), Andesite Alloy](https://github.com/Creators-of-Create/Create/wiki/Andesite-Alloy)
- **Create recipe dependencies.** Andesite alloy is an essential ingredient for Shafts and both regular and large Cogwheels, plus Andesite Casing, Millstones, Propellers and Whisks. It is made from andesite + iron or zinc nugget, and mixing in a Basin is faster than hand crafting — [Create fandom wiki, Andesite Alloy](https://create.fandom.com/wiki/Andesite_Alloy)
- **Create alloy farms.** Players build dedicated farms to mass-produce the alloy for building. One community schematic claims over 23,000 alloy per hour (user claim, unverified) — [createmod.com schematic](https://createmod.com/schematics/23-000-andesite-alloy-per-hour)
- **Create schematicannon.** It places blueprints but needs both the block items and gunpowder as a per-placement fuel. Hovering the indicator shows how many blocks the loaded gunpowder can place. Blocks replaced by the Schematicannon will not drop any items — [Create wiki, Printing a Schematic](https://github.com/Creators-of-Create/Create/wiki/Printing-a-Schematic)
  - Gunpowder here is a separate placement consumable, layered on top of item costs. It is a real precedent for a "placement-only currency" inside Create itself.
- **Create storage add-ons.** Add-ons (Schematic Energistics, Refined Schematics) auto-extract items and auto-refill gunpowder from storage networks. Players want to automate placement-cost logistics away — [CurseForge, Schematic Energistics](https://www.curseforge.com/minecraft/mc-mods/schematic-energistics); [Refined Schematics](https://www.curseforge.com/minecraft/mc-mods/refined-schematics)
- **shapez 2 (contrast: no build cost).** The Steam listing calls it "the purest factory simulation game imaginable" where building costs are removed and resources are unlimited — [Steam, shapez 2 [snippet]](https://store.steampowered.com/app/2162800/shapez_2__Factory/)
- **Original shapez.** A RAWG review notes that story mode is where buildings have a cost — [RAWG, shapez [snippet]](https://rawg.io/games/shapezio)
- **shapez vs. Factorio.** A GOG review argues shapez's core loop is more satisfying than Factorio's because crafting costs make everything slower in Factorio — [GOG, shapez reviews [snippet]](https://www.gog.com/en/game/shapez)
- **Factorio "Free Buildings" mod.** A fan mod that makes Factorio buildings free to craft, citing shapez in its tagline. It shows demand for removing build costs in a production-item game — [Factorio mod portal, Free Buildings](https://mods.factorio.com/mod/FreeBuildings)
- **Kingdom Two Crowns: one universal coin pays for everything.** Town Center tiers cost Campfire 3, Camp 6, Village 9, Town 12, Fort 15, Castle 18 and Iron Castle 20 coins. The Stone Mine costs 10 coins and the Iron Mine 20 coins — [Magic Game World guide [snippet]](https://www.magicgameworld.com/kingdom-two-crowns-buildings-kingdom/)
  - Figures conflict across Kingdom versions; the fandom wiki gives a campfire cost of 1 in Classic and 3 in New Lands — [Kingdom wiki, Town center [snippet]](https://kingdomthegame.fandom.com/wiki/Town_center)
- **Kingdom Two Crowns build timing.** After you pay, 1-2 random workers go build it, so late-day orders take time — [Magic Game World [snippet]](https://www.magicgameworld.com/kingdom-two-crowns-buildings-kingdom/)
- **Mindustry.** The Large Deconstructor block refunds the full build cost of what it breaks down. Mindustry buildings are paid from core-stored items that the factory itself produces — [Mindustry block DB, Deconstructor [snippet]](https://game-platform-web-5a2.pages.dev/en/mindustry/block/deconstructor)
- **Captain of Industry.** Unity is a separate, non-item currency. Spending it lets you speed up construction, instantly deliver construction material to a new site, enact edicts and claim world-map resources. It is a soft "construction accelerator" currency on top of item costs — [Captain of Industry wiki, Unity [snippet]](https://wiki.captain-of-industry.com/Unity)

### Inferences
- **The 실타래 is a fourth category.** Every factory game found (Factorio, Satisfactory, Mindustry, Create, Captain of Industry, ATS, Anno) makes build costs out of goods the economy produces. The 실타래 is closer to Kingdom's coins or Islanders' building stock, a currency whose income is decoupled from factory output.
  - Consequence: the classic factory loop "expand the factory to afford more factory" (the snowball) is cut. Factory growth instead scales with time spent in anime mode.
- **Create precedent for a placement surcharge.** The schematicannon's gunpowder is a placement-only consumable stacked on item costs. Players accepted it, then modded in automation to stop caring about it. A 실타래 surcharge that is non-automatable by design should therefore be modest and refundable, or it becomes the friction players try to eliminate.
- **Avoid ATS-style collisions.** In ATS, build materials double as production inputs, which creates allocation tension. The user's constraint (never a production input) removes that tension. That is good for keeping ratio math clean.
- **Not covered here (unverified, general knowledge).** Timberborn, Frostpunk, Banished, Palworld, Slime Rancher, ONI, Townscaper and tower defense build points all fit the same pattern:
  - Timberborn, Frostpunk and Banished: build costs in produced logs, planks, steel, stone and so on.
  - Townscaper: free, with no costs at all.
  - Slime Rancher: plots cost newbucks earned by selling plorts, the produced output.
  - Tower defense: build points or gold come from kills, not from production. This is the nearest "external income" analogue to the 실타래.

### Gaps
- I could not fetch primary wiki pages for Anno, Timberborn, Frostpunk, Banished, Palworld, Slime Rancher, ONI or RimWorld build-cost tables (blocked hosts). Specific numbers for those games are not included.
- I found no developer post explaining why shapez 2 removed building costs; the Steam store text is the only source.

## Q2. Build currencies the factory cannot produce: do they bottleneck or pace?

### Takeaway
Non-producible placement currencies exist mostly outside factory games:
- Islanders: building packs unlocked by score.
- Dorfromantik: a tile stack refilled by quests.
- Kingdom: coins.
- Captain of Industry: Unity, as an accelerator.

They are generally received as calm pacing when income is tied to an activity the player enjoys and the cap feels "earned". They turn into frustration when randomness or scarcity blocks a plan the player has already formed (Cubed3 on Islanders).

### Cited Findings
- **Islanders: pack choices.** Players choose between two building packs, "each of which provides a limited number of buildings according to a theme". Buildings are a finite stock, not purchasable with produced resources — [Wikipedia, Islanders [snippet]](https://wikipedia.com/wiki/Islanders_(game))
- **Islanders: scaling score thresholds.** The points required to restock the inventory and unlock new buildings or islands increase with each unlock — [search summary of Islanders sources [snippet]](https://www.pcgamer.com/uk/islanders-is-the-most-relaxing-strategy-game-ever)
- **Islanders replaces resources with points.** PocketGamer: "Islanders: Mobile Replaces Resource Gathering with Points" — [PocketGamer review [snippet]](https://www.pocketgamer.com/islanders-mobile/review)
- **Kotaku on Islanders.** The absence of systems measuring population, happiness, finances or resources "is a little odd at first" but elegant — [Kotaku [snippet]](https://kotaku.com/islanders-is-almost-the-perfect-city-building-game-1833729123)
- **PC Gamer on Islanders.** "soothing, charming… maybe the most relaxing strategy game I've ever played" — [PC Gamer [snippet]](https://www.pcgamer.com/uk/islanders-is-the-most-relaxing-strategy-game-ever)
- **Cubed3 on Islanders (frustration side).** The random pack choices and proximity scoring "can turn an otherwise relaxing game into a source of annoyance" — [Cubed3 review [snippet]](https://www.cubed3.com/games/reviews/nintendo-switch/islanders-console-edition)
- **Dorfromantik: the stack is a non-producible placement currency.** The game ends when the tile stack runs out. Quests refill it with 5-8 tiles each, and a "Perfect" tile (all six edges matching) gives +1 tile — [Pro Game Guides](https://progameguides.com/dorfromantik/how-to-get-more-tiles-in-dorfromantik/)
- **Dorfromantik quest examples.** A windmill wants six adjacent grain fields; a locomotive wants ten connected tracks — [Xbox store listing [snippet]](https://www.xbox.com/en-US/games/store/-/9PB1LXV5XTF3)
- **Dorfromantik player tactic.** Players deliberately fail quests to recover tiles when low. Scarcity of a non-producible build currency drives meta-optimisation (user tip, unofficial) — [Steam discussion [snippet]](https://steamcommunity.com/app/1455840/discussions/0/3185738120273761317)
- **Captain of Industry.** Unity, the non-item currency, lets players skip construction logistics: it instantly delivers construction material — [CoI wiki, Unity [snippet]](https://wiki.captain-of-industry.com/Unity)

### Inferences
- **Satisfying vs. frustrating.** Both reception patterns above are clear:
  - Satisfying: the external currency is earned through an activity that is itself the fun (scoring in Islanders, tile matching in Dorfromantik).
  - Frustrating: the player has a concrete plan and the currency is randomly or arbitrarily short (Cubed3's Islanders complaint).
  - For 실타래, the activity is watching anime, which the user does anyway. That is a strong fit for "earned pacing". The risk window is when the player is in factory mode, has a redesign in mind, and is short of 실타래.
- **Hard caps vs. accumulation.** Islanders and Dorfromantik are run-based games where the stack running out ends the session. In a persistent factory there is no run end, so a non-producible build currency acts as a soft size cap: total placed structures ≤ total 실타래 earned (if refunds are 100%).
  - That is closer to a "supply cap" or "command points" (RTS-style) than to a consumable, which avoids the "spent forever" feeling.
- **Capping placements, not ownership.** With 100% refund on removal, 실타래 effectively becomes a budget of simultaneously placed parts. A budget is psychologically closer to RTS supply caps or Islanders' inventory than to Anno's sunk material costs.

### Gaps
- I found no factory-game example whose build currency is earned from a non-game or out-of-game activity (like watching anime). Mobile games with ad-watch or idle currencies are the closest, but none were researched here.
- I found no player-sentiment data, such as surveys or reviews, specifically about "command point" caps in base builders (for example Mindustry unit caps or Factorio-like caps). This is not covered.

## Q3. Scaling: flat cost vs. cost rising with building count; refunds; relocation

### Takeaway
- **Refunds:** most factory games refund 100% because the building is an item you get back (Factorio, Satisfactory, Mindustry's Large Deconstructor, ONI). Colony and city sims often refund partially (RimWorld 50-75%, Captain of Industry 75%, Anno via a setting).
- **Escalating costs:** these appear in score- or tier-driven games (Islanders thresholds, Kingdom tiers, mobile "price increases with each purchase").
- **Relocation:** Anno offers free relocation on standard difficulty, which is the cleanest precedent for "move without penalty".

### Cited Findings
- **Satisfactory.** In Blueprint Mode, "anything you dismantle will have all of its resources returned to your inventory" — [Escapist guide [snippet]](https://escapistmagazine.com/?p=286587)
  - Dismantling a structure also refunds its stored contents — [Satisfactory wiki, Construction Tool [snippet]](https://satisfactory.wiki.gg/wiki/Construction_Tool)
- **Factorio.** In vanilla, buildings are items, so mining returns the item. There is no recycling of crafting ingredients at 100%. A Steam commenter argues "the only way to balance such a thing is to not have a 100% return rate", and mods add uncrafting — [Steam discussion [snippet]](https://steamcommunity.com/app/427520/discussions/0/4141691052149371461); [Factorio mods, Reverse Factory](https://mods.factorio.com/mod/reverse-factory/discussion/5a5f1b0dadcc441024d75be2)
  - Space Age bug: deconstructing machines on a platform voided their contents — [Factorio forums](https://forums.factorio.com/viewtopic.php?p=662656)
- **Captain of Industry.** Deconstruction yields a flat 75% refund (player suggestion; may be outdated). The suggestion says this "feels disincentivizing to iterate on designs" and proposes a difficulty-scaled refund — [CoI ideas board [snippet]](https://ideas.captain-of-industry.com/suggestions/275935/deconstruction-refund-variable-with-difficulty)
  - A later CoI patch added a "new entity replace/upgrade system" — [SteamDB patch notes [snippet]](https://steamdb.info/patchnotes/19457848)
- **Timberborn.** A feature request asks for recovering materials when demolishing. A commenter argues that "if you don't get some or all of your resources back it discourages editing your setup" — [Timberborn feature upvote [snippet]](https://timberborn.featureupvote.com/suggestions/214863/comment/308919)
- **RimWorld (sources conflict).** The wiki talk page says deconstructing returns 75% of cost, rounded, so components average 3.75 but land at 3 or 4 — [RimWorld wiki, Talk:Deconstruct [snippet]](https://rimworldwiki.com/wiki/Talk:Deconstruct)
  - A mod commenter says base RimWorld "normally halves what you get back" — [Steam workshop comments [snippet]](https://steamcommunity.com/sharedfiles/filedetails/comments/2579588683)
  - Items worth 1 material or less return nothing; the governing field is `resourcesFractionWhenDeconstructed` — [RimWorld wiki talk [snippet]](https://rimworldwiki.com/wiki/Talk:Deconstruct)
- **Oxygen Not Included.** A Klei bug report says the deconstruct tooltip promised a full refund but only half was returned, on the preview branch — [Klei bug tracker [snippet]](https://forums.klei.com/klei-bug-tracker/oni/deconstruct-tool-tip-lies-about-full-refund-r12668/)
  - Another Klei thread argues that deconstructing damaged buildings "shouldn't give full resources", which implies that is the behaviour — [Klei forums [snippet]](https://forums.kleientertainment.com/forums/topic/104981-deconstructing-damaged-buildings-shouldnt-give-full-resources/)
  - Treat ONI as full refund by default (unverified).
- **Anno 1800: refunds are a game setting.** A Steam thread lists "Refund costs?" among the custom options — [Steam discussion [snippet]](https://steamcommunity.com/app/916440/discussions/0/3835424220122307262)
  - The 2019 devblog "Have it your way" asks: "If you destroy buildings to make space… do you want to get some previously used materials?" — [Ubisoft devblog [snippet]](https://www.ubisoft.com/en-gb/game/anno/1800/news-updates/5jpMEFTsLQiwlXEjtyYcaR/devblog-have-it-your-way)
  - A player has "Full Refunds" set in settings and reports elder housing not refunding wood — [DevTrackers [snippet]](https://devtrackers.gg/anno-1800/p/4f7a3fc2-land-of-lions-elder-housing-costs)
  - A bug report says a Large Warehouse refunds more steel and glass than it cost, at a cost of 30 wood — [DevTrackers [snippet]](https://devtrackers.gg/anno-1800/p/df576089-bug-anno-1800-inconsistent-refund-costs-of-warehouses)
  - Refund accounting is error-prone when costs vary (upgrades, tiers).
- **Anno 1800 relocation.** On standard difficulty you can move any structure at any moment for free. A patch note covers cases where relocation is blocked by difficulty settings and adds downgrade refunds for skyscrapers on normal and advanced — [PCWorld review [snippet]](https://www.pcworld.com/article/3387965/anno-1800-review.html); [anno-union patch notes [snippet]](https://anno-union.com/?p=9969)
- **Escalating costs.** Islanders' score thresholds increase per unlock (see Q2). Kingdom Two Crowns tiers rise from 3 to 20 coins (see Q1). A mobile FAQ exists titled "Why does the price increase when purchasing buildings" — [Helpshift FAQ [snippet]](https://gagale.helpshift.com/hc/en/12-tuscany-adventure/faq/629-3-why-does-the-price-increase-when-purchasing-buildings)

### Inferences
- **Partial refunds read as "don't iterate".** Two independent communities (Captain of Industry at 75%, Timberborn with none) explicitly link partial or no refunds to reluctance to redesign. For a user who loves redesigning, 100% refund on removal is the evidence-supported default.
- **Refund what was actually paid.** Anno's refund bugs show that when costs vary (escalation, upgrades), the "refund what you paid" bookkeeping gets messy.
  - If 실타래 costs escalate with count, refund the current marginal price, not the original price, so placing and removing never generates or loses currency. Or keep costs flat per part type.
  - Escalation plus 100% refund of the last-paid price means removing any part refunds the most recent (highest) tier. This is equivalent to the cost being a function of the current count, which is arbitrage-free.
- **Free relocation is the cleanest no-penalty mechanic.** Anno's free relocation on standard difficulty is a mainstream precedent. A Create-style "pick up the assembled contraption or section and move it" should cost 0 실타래, since nothing new is placed.

### Gaps
- I found no authoritative source for Factorio's vanilla rules beyond the forum and Steam snippets (wiki.factorio.com blocked). That mined entities return as items is general knowledge.
- Anno's exact refund percentages per difficulty are unconfirmed.
- Mindustry's default deconstruct refund for ordinary player deconstruction is unconfirmed (the search tool suggested about 50% from memory; not verified).

## Q4. How games keep build costs from discouraging experimentation

### Takeaway
Four tools recur:
- 100% refund (Satisfactory, Factorio's items).
- Free relocation (Anno).
- Ghost or blueprint planning that is placed before it is paid for (Factorio ghosts, Satisfactory Blueprint Designer, Create schematics).
- A separate cost-free design space (shapez 2's no-cost design, Anno's Creative Mode, Factorio community requests for a blueprint sandbox).

Players actively ask for a cost-free design layer even when refunds are 100%. The friction they complain about is time and fetching, not only currency.

### Cited Findings
- **Factorio sandbox detour.** Players described saving, quitting, opening a sandbox to experiment, then blueprinting and importing. They requested a "Blueprint Creative Mode" or "Limitless Construction Plane", "a layer outside the normal game layer with checkerboard background", to design without live-map constraints — [Factorio forums, Edit blueprint / Blueprint Creative Mode](https://forums.factorio.com/viewtopic.php?p=335278); [same thread](https://forums.factorio.com/viewtopic.php?p=464444)
- **Factorio ghost planning.** Proposals for shift-placed ghost buildings that teammates can see but that don't interact with the world, with blueprints as collections of ghosts. These came out of Friday Facts discussions — [Factorio forums](https://forums.factorio.com/viewtopic.php?p=290424)
- **Factorio blueprint editing (FFF #250 thread).** Players asked to reassign new contents to an existing blueprint, and for a blueprint editor with zoom and pan. Iteration friction is about editing, not only cost — [FFF #250 discussion](https://forums.factorio.com/viewtopic.php?p=371188)
- **Satisfactory Blueprint Mode.** Full resource return on dismantle supports trial and error — [Escapist [snippet]](https://escapistmagazine.com/?p=286587)
- **Anno 1800 Creative Mode.** A dedicated mode exists (fan wiki page) — [Anno 1800 wiki, Creative Mode [snippet]](https://anno1800.fandom.com/wiki/Creative_Mode)
- **Create schematics.** These let players design once and print. The schematicannon still charges gunpowder plus items, and blocks it replaces drop nothing (a potential loss on rebuild) — [Create wiki, Printing a Schematic](https://github.com/Creators-of-Create/Create/wiki/Printing-a-Schematic)
- **Refunds and iteration in other games.** A Captain of Industry player calls the 75% refund "disincentivizing to iterate"; a Timberborn player says no refund "discourages editing your setup" — [CoI ideas [snippet]](https://ideas.captain-of-industry.com/suggestions/275935/deconstruction-refund-variable-with-difficulty); [Timberborn feature upvote [snippet]](https://timberborn.featureupvote.com/suggestions/214863/comment/310632)

### Inferences
Recommended stack for 실타래, synthesised from the precedents above:
1. **100% refund on removal**, credited instantly to a wallet, not dropped as items to collect.
2. **Free move or rotate** of already-placed parts and contraptions.
3. **Ghost or blueprint planning that costs nothing until "committed".**
   - The ghost should simulate RPM, stress and ratio math, so players can test designs without spending.
   - This directly answers the Factorio community's "sandbox detour" complaint.
4. **Optionally, a design or test bench** where everything is free but output is discarded (a sandbox within the save).
5. **Undo restores 실타래.**

Two traps to avoid:
- **Create's "replaced blocks drop nothing".** In the 실타래 version, any overwrite or replace must refund.
- **Charging 실타래 on the swap of a gear ratio** (for example small cog to large cog). Swaps should cost the difference only, or nothing.

### Gaps
- I could not reach the official Factorio Friday Facts that describe ghost, undo or planner features (factorio.com was not tried; wiki.factorio.com was blocked). Only forum threads are cited.
- I found no source on Satisfactory's Blueprint Designer specifics (free placement inside the designer).

## Q5. Does a build-only resource leave throughput ratios untouched? Where does it indirectly affect production?

### Takeaway
A build-only currency that is never a recipe input does not appear in any production ratio. Ratio math (RPM, stress, items per minute) stays pure, and the shapez 2 "costs removed" design shows a factory game can be fully about ratios and logistics.

It still shapes production indirectly in four ways:
- **Factory size:** it caps how many machines exist, which caps total throughput.
- **Over-building and buffering:** it discourages them.
- **Design density:** it rewards compact, high-efficiency builds per part.
- **Reward pacing:** in a game with no other expansion bottleneck, the 실타래 income rate becomes the effective growth rate.

### Cited Findings
- **shapez 2** removes build costs and resource limits to be "the purest factory simulation" — [Steam [snippet]](https://store.steampowered.com/app/2162800/shapez_2__Factory/)
  - A GOG reviewer prefers shapez's loop because Factorio's crafting costs "make everything slower". Build costs mainly affect the pace of expansion, not the logic of ratios — [GOG [snippet]](https://www.gog.com/en/game/shapez)
- **Create alloy competition.** Andesite alloy is both the building material for kinetic parts and an item that factories mass-produce. So in vanilla Create, building directly competes with production output; dedicated alloy farms exist for this — [Create fandom](https://create.fandom.com/wiki/Andesite_Alloy); [createmod.com](https://createmod.com/schematics/andesite-alloy-factory)
- **Captain of Industry Unity.** Unity is a non-item currency that only accelerates construction or delivers build materials, so it affects build speed but not recipes — [CoI wiki, Unity [snippet]](https://wiki.captain-of-industry.com/Unity)
- **Against the Storm.** Build materials (planks, bricks, fabric) come from the same workshops and storage as production goods, which creates allocation conflict — [ATS wiki, Workshop [snippet]](https://hoodedhorse.com/wiki/Against_the_Storm/Workshop); [Steam [snippet]](https://steamcommunity.com/app/1336490/discussions/0/4039231211457190088/?l=italian)

### Inferences
- **Decoupling 실타래 removes a feedback loop.** In vanilla Create and Factorio, "build an alloy or plate factory to afford more factory" is itself a core loop. Taking it out has two effects:
  - Positive: ratio puzzles stay clean, and there is no "I can't experiment because I'm short of alloy".
  - Negative: there is no factory-driven snowball, so factory growth is tied entirely to 실타래 income from anime time.
  - Mitigation: keep some build costs in produced materials (for example monster-farm outputs or crafted metals for gears) and use 실타래 only as a placement or "binding" surcharge, or as the cost of unlocks and blueprints. This gives a hybrid where the factory still helps build itself.
- **Indirect cap on production.** With a 100% refund, 실타래 equals a budget of placed parts. Total throughput is bounded by the parts budget × parts efficiency.
  - That incentivises compact, clever gear trains. This suits a ratio-math lover and makes redesigning to "do more with fewer parts" a rewarding goal rather than a cost.
- **Budget pressure scales with design efficiency.** Because 실타래 is not consumed per tick, running machines longer never costs anything. It can't create "idle machine" penalties, and stress or RPM balance is unaffected.
  - The only throughput lever it touches is how many machines and shafts exist at once.
- **Keep 실타래 out of upkeep and repair.** If 실타래 were charged per part placed while production also needs more parts as tiers rise (bigger gear trains, more stress), the cost of factory growth rises superlinearly with tier.
  - Designers may want 실타래 cost per part to stay flat or fall at higher tiers, or to price bigger contraptions by "slot", not per block.
- **No daily cap.** Without a cap, a heavy anime watcher can bank a large budget. With 100% refunds, the budget never drains, so long-run pressure falls to near zero. A one-time build cost is a long-term growth pacer, not a permanent constraint.
  - If the designer wants a persistent goal, it must come from new things to spend on (unlocks, cosmetics, monster habitats), not from wear.

### Gaps
- I found no published design analysis (GDC talk, Game Developer article) that quantifies how decoupled build currencies affect throughput or factory size. The points above are inference.
- I found no Factorio Friday Facts on the philosophy of building-cost balance; it is not covered.
