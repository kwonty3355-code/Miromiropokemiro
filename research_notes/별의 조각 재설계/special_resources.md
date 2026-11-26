# Special (non-producible / externally-sourced) resources in factory & base-building games — and how they avoid breaking production balance

> Method note: WebFetch could not reach any host in this session (satisfactory.wiki.gg, shapez2.wiki.gg, dsp-wiki.com, steamcommunity.com, steamdb.info, wiki.captain-of-industry.com all failed DNS — outside the session's allowed network). **Every finding below comes from search-result snippets/summaries and is marked [snippet].** Page bodies were not read. Exact numbers should be re-checked against the live wiki before quoting them as fact. Games in the brief that I could not verify by search (Techtonica, Palworld, Factorio SA, Mindustry, Create, ONI, Timberborn, Foundry, Infinifactory, Opus Magnum, Factory Town) are listed under Gaps, not presented as facts.

## Q1. Catalogue: which special resources exist, how they are obtained, what they are spent on

### Takeaway
The verified examples fall into four families: (a) **fixed world-count pickups** that amplify buildings (Satisfactory Somersloops 106, power slugs to shards, Mercer Spheres; Frostpunk Steam Cores); (b) **one-time choice tokens** (Satisfactory Hard Drives, which pick 1 of 2 alt recipes); (c) **currencies made from production but spent outside production** (Shapez 2 Blueprint Points, Shapez 1 blueprint shape, Captain of Industry Unity); (d) **cross-run meta-currencies** (DSP Metadata, Against the Storm Citadel Resources).

### Cited Findings
**Satisfactory: Somersloop (fixed count, amplifies production)**
- There are 106 Somersloops in total as of Patch 1.0. The wiki calls them a "non-renewable resource" [snippet] — [satisfactory.wiki.gg Production Amplifier](https://satisfactory.wiki.gg/wiki/Production_Amplifier)
- Production amplification works per slot. In a 1-slot building (Constructor, Smelter) one Somersloop gives +100% output. Partly filled slots give a proportional boost ("4 slots but only 1 … only a 25% boost") [snippet] — [satisfactory.wiki.gg Production amplification](https://satisfactory.wiki.gg/wiki/Production_amplification)
- Amplification raises power use sharply. Wiki example: one Somersloop in a constructor multiplies total power by 4 [snippet] — [satisfactory.wiki.gg Production Amplifier](https://satisfactory.wiki.gg/wiki/Production_Amplifier)
- Wiki advice: save Somersloops for the ends of production chains (e.g., Assembly Director System, Pressure Conversion Cube, where an Assembler needs only 2 to double). Somersloops can be moved, so track where temporary boosts sit [snippet] — [satisfactory.wiki.gg Production Amplifier](https://satisfactory.wiki.gg/wiki/Production_Amplifier)
- Somersloops are also spent as research inputs. The Production Amplifier unlock costs 1 Somersloop + 100 SAM Fluctuator + 50 Circuit Board. The Alien Power Augmenter unlock costs 1 Somersloop + 100 SAM Fluctuator + 50 Computer [snippet] — [satisfactory.wiki.gg Research](https://satisfactory.wiki.gg/wiki/Research); [satisfactory.guru MAM Alien Tech](https://satisfactory.guru/articles/read/index/id/100/name/MAM+-+Alien+Technology)
- Alien Power Augmenter: +500 MW and +10% grid capacity in its base state. Fed 5 Alien Power Matrices/min, the grid boost rises to +30% [snippet] — [satisfactory.wiki.gg APA](https://satisfactory.wiki.gg/wiki/APA). One guide lists the build cost as 10 Somersloops + 50 SAM + parts. This is a single source and unverified [snippet] — [gamever.io](https://gamever.io/knowledge-base/how-to-use-the-alien-power-augmentor-in-satisfactory-release-10)
- A pre-1.0 Steam player noted "only 106 Sloops can be obtained" and asked whether endgame dupe tech could make more. This signals that players feel the cap [snippet] — [Steam discussion](https://steamcommunity.com/app/526870/discussions/0/4423185135322244328)

**Satisfactory: Power Slugs to Power Shards (overclocking)**
- Each Power Shard slot allows +50% clock speed, so 3 shards are needed for 250% [snippet] — [DiamondLobby](https://diamondlobby.com/?p=9384)
- Slug yields: Green = 1 shard, Yellow = 2, Purple = 5 [snippet] — [DiamondLobby](https://diamondlobby.com/?p=9384)
- Power formula: the exponent is 1.321928 (log2 2.5): "you need 2.5x more power to double your productivity." At 250% clock a building uses about 335.77% of base power. Patch 0.7.0.0 lowered the exponent for production buildings [snippet] — [satisfactory.wiki.gg Advanced clock speed](https://satisfactory.wiki.gg/wiki/Tutorial%3AAdvanced_clock_speed); [Clock speed](https://satisfactory.wiki.gg/wiki/Clock_speed)
- Power Shards also go into research. The Alien Power Matrix research costs 50 Singularity Cell + 100 Power Shard + 500 SAM [snippet] — [satisfactory.wiki.gg APA](https://satisfactory.wiki.gg/wiki/APA)

**Satisfactory: Mercer Spheres (spent on the Dimensional Depot, a logistics tool)**
- The Dimensional Depot Uploader is unlocked in MAM Alien Technology for 1 Mercer Sphere + 11 SAM. Upload-speed tiers cost Mercer Spheres plus SAM: the 120/min tier is 13 spheres + 151 SAM, the 240/min tier is 23 spheres + 199 SAM. A calculator site also lists 30/min (3 spheres) and 60/min (7 spheres) tiers, so the sources do not fully agree [snippet] — [satisfactory.wiki.gg DD Uploader](https://satisfactory.wiki.gg/wiki/Dimensional_Depot_Uploader); [satisfactory-calculator Mercer Sphere](https://satisfactory-calculator.com/en/tools/detail/id/Desc_WAT2_C/name/Mercer+Sphere)
- "All upgrades to the Dimensional Depot and Dimensional Depot Uploaders require Mercer Spheres (97 total) and SAM Fluctuators (1,040 total)" [snippet] — [satisfactory.wiki.gg DD Uploader](https://satisfactory.wiki.gg/wiki/Dimensional_Depot_Uploader)
- Mercer Spheres are found at fixed map spots (location lists exist for Patch 1.0), so depot upload is slow at first [snippet] — [BisectHosting guide](https://www.bisecthosting.com/blog/satisfactory-mercer-sphere-locations-crafting-recipes-tech-tree)

**Satisfactory: Hard Drives (choice tokens)**
- There are 118 crash sites, each with one Hard Drive. Scanning a drive in the MAM offers 2 random alternate recipes. You pick one and can reroll once. Unchosen picks can be made later from the hard-drive library. Four drives are spent directly on research (Compacted Coal, Turbofuel, Rocket Fuel, Ionized Fuel) [snippet] — [satisfactory.wiki.gg Hard Drive](https://satisfactory.wiki.gg/wiki/Hard_Drive); [Alternate recipe](https://satisfactory.wiki.gg/wiki/Alternate_recipe)

**Dyson Sphere Program: Metadata (cross-save meta-currency)**
- Metadata is earned across save files. Production rate = "the average number of Matrices produced per minute (calculated over the most recent hour of gameplay)." It can only be spent in a save with a different seed than the one that earned it. Uses: instantly research a technology, or redeem it for matrices [snippet] — [DSP Wiki Metadata](https://dsp-wiki.com/Metadata)
- Difficulty scaling: a resource multiplier below 1x increases metadata, above 1x decreases it [snippet] — [DSP Wiki Metadata](https://dsp-wiki.com/Metadata); a player reports the same at x0.6 [snippet] — [Steam](https://steamcommunity.com/app/1366540/discussions/0/594036392036029806/)
- Metadata is tracked per cluster address (seed + resource multiplier + star count), not per bare seed. Contributions from different cluster addresses add together (2022 patch). Running a save longer at the same rate gives no extra metadata, because only increases since the last export are credited [snippet] — [Steam "Metadata clarification"](https://steamcommunity.com/app/1366540/discussions/0/3803901984157405416/); [SteamDB patch 0.9.25](https://steamdb.info/patchnotes/8597874/)
- A 2022 update allowed splitting white metadata into its five component colours [snippet] — [Steam "Metadata clarification"](https://steamcommunity.com/app/1366540/discussions/0/3803901984157405416/)

**Shapez 2: Blueprint Points / Research Points / Operator Level**
- Blueprints unlock at milestone 2. Milestones grant Blueprint Points that scale from 2,500 early to 250,000 late. A December 2024 patch rebalanced milestones to give more late-game points [snippet] — [shapez2.wiki.gg Milestones](https://shapez2.wiki.gg/wiki/Milestones); [Changelog](https://shapez2.wiki.gg/wiki/Changelog)
- Operator Level: after a milestone's final shape is done, you keep delivering shapes into the Vortex to raise Operator Level, which pays Blueprint Points. A garbled wiki table suggests 25,000 per level for levels 1–9, 50,000 for 10–24 and 100,000 for 25+ [snippet] — [shapez2.wiki.gg Operator Level](https://shapez2.wiki.gg/wiki/Operator_Level); [RPS review](https://rockpapershotgunom.pages.dev/posts/shapez-2-early-access-review-splendid-abstract-factory)
- Pasting a blueprint spends Blueprint Points, plus free Platforms if the blueprint is a platform. A player example: "1 PU 237 buildings 1216 BP" (about 5 BP per building by my own arithmetic). The RPS reviewer found even the costliest pastes cost "only a few thousand points," so points were rarely a constraint [snippet] — [Steam guide Prime Platforms](https://steamcommunity.com/sharedfiles/filedetails/?id=3320548627); [RPS review](https://rockpapershotgunom.pages.dev/posts/shapez-2-early-access-review-splendid-abstract-factory)
- Shapez 2 upgrades are bought with Research Points, a separate currency from Blueprint Points [snippet] — [shapez2.wiki.gg Upgrades](https://shapez2.wiki.gg/wiki/Upgrades)
- Shapez 1 (original): blueprints are paid in a specific shape ("CbCbCbRb:CwCwCwCw"), so a player who runs out of that shape cannot paste. This comes from a single 2020 forum thread [snippet] — [Steam shapez 1](https://steamcommunity.com/app/1318690/discussions/0/2569816094929939890)

**Captain of Industry: Unity**
- Settlements generate Unity based on which needs are met: usually 1–2 Unity per month for each fully satisfied resource [snippet] — [CoI Wiki Unity](https://wiki.coigame.com/Unity)
- Spent on: instant delivery of construction materials (quick build), instant repair of broken vehicles and buildings when Maintenance is missing, production boosts on buildings (-0.25 Unity per boosted building), and edicts (some cost monthly Unity) [snippet] — [CoI Wiki Unity](https://wiki.coigame.com/Unity); [CoI Wiki Edicts](https://wiki.coigame.com/Edicts)
- Players: "most unity used in my game is quick build/remove." Guides advise keeping Unity for emergencies and world-map claims, not construction speed [snippet] — [Steam CoI](https://steamcommunity.com/app/1594320/discussions/0/603029525548267213/); [earlyguides CoI tips](https://earlyguides.com/captain-of-industry/tips)

**Frostpunk: Steam Cores**
- The Steam Core is "the only item in the game that the player cannot create." It is found by scouting and needed for advanced facilities and automatons [snippet] — [Frostpunk Gamepedia](https://frostpunk.gamepedia.com/Steam_Core); [PC Gamer](https://www.pcgamer.com/frostpunk-guide/)
- Players hit a hard wall once every scouting node is used up. Dismantling returns cores, so the stock is fixed but can be moved around. Automatons trade off against advanced buildings [snippet] — [Gamepressure](https://www.gamepressure.com/frostpunk/how-to-get-steam-cores/z3ad86); [Steam Frostpunk](https://steamcommunity.com/app/323190/discussions/0/1696045708639971790)

**Against the Storm: Citadel Resources (meta)**
- Food Stockpiles, Machinery and Artifacts are carried out of a successful expedition. They are spent in the Smoldering City on permanent capped upgrades: Brass Forge global production speed up to +28%, and an Obsidian Archives line that slows the Queen's Impatience. Some levels unlock features (Mine Upgrades at Brass Forge lv3). Since 2022 the only requirement to unlock a new upgrade row is player level [snippet] — [Hooded Horse wiki Upgrades](https://wiki.hoodedhorse.com/Against_the_Storm/Upgrades); [Destructoid](https://www.destructoid.com/how-to-get-and-keep-artifacts-in-against-the-storm/); [Eremite progression update](https://eremitegames.com/progression-update/)

### Inferences
- Every "fixed count" resource that Satisfactory and Frostpunk spend directly on production has a hard ceiling (106 / 118 / 97 / scout nodes). This is the opposite of the 별의 조각 brief ("endlessly useful, no inflation"). These designs avoid inflation by having no faucet once the world is cleared, so the endgame becomes a dead stock.
- DSP Metadata and Shapez Operator Level are the only verified examples of an **endless faucet that stays non-inflationary**. DSP does it with a *rate* (avg matrices/min over the last hour), not a running total, plus "only the increase since last export counts." Shapez caps the reward per level, but levels themselves continue.

### Gaps
- Exact Somersloop/APA build costs, and whether 1.0+ patches changed the counts: wiki pages unreadable.
- DSP: whether using Metadata disables achievements or Milky Way upload, and the exact metadata cost per tech. No snippet covered this, and dsp-wiki.com was unreachable.
- Shapez 2: exact paste-cost formula per building/platform, and whether research upgrades reduce it.

## Q2. How do Shapez blueprint points, DSP metadata and Satisfactory power shards make a scarce resource "genuinely needed" while keeping ratio math intact? Does overclocking change the math?

### Takeaway
Only the Shapez and DSP currencies leave ratio math untouched, because they are spent *outside* the production graph: on pasting (a build action) and on skipping research (a progression action). Satisfactory shards and Somersloops deliberately rewrite per-building throughput (up to 250% clock, 2x output) and power, so they *do* change ratio math. Satisfactory confines the damage with a hard world cap and a steep, non-linear power cost.

### Cited Findings
- Overclocking changes the rate: each shard adds +50% clock, so a building runs at up to 250% of its recipe rate. Power scales superlinearly (exponent ~1.32, about 335.77% power at 250%). The designed tradeoff is "2.5x power to double productivity" [snippet] — [satisfactory.wiki.gg Advanced clock speed](https://satisfactory.wiki.gg/wiki/Tutorial%3AAdvanced_clock_speed); [DiamondLobby](https://diamondlobby.com/?p=9384)
- Somersloops double output (not inputs) per filled building, and partial fill gives a proportional boost. So the ratio of output to input changes. This is a true free-output multiplier, priced in power (about 4x) [snippet] — [satisfactory.wiki.gg Production amplification](https://satisfactory.wiki.gg/wiki/Production_amplification)
- Shapez 2 Blueprint Points are produced by the factory (milestones and vortex shape delivery) but only consumed by the paste/blueprint tool, never by machines [snippet] — [shapez2.wiki.gg Milestones](https://shapez2.wiki.gg/wiki/Milestones); [RPS review](https://rockpapershotgunom.pages.dev/posts/shapez-2-early-access-review-splendid-abstract-factory)
- Counter-evidence that Shapez 2 BP is not "genuinely needed": the RPS reviewer says points were rarely a constraint, and a player says "it's extremely easy to build a farm for blueprint points very early" [snippet] — [RPS review](https://rockpapershotgunom.pages.dev/posts/shapez-2-early-access-review-splendid-abstract-factory); [Steam shapez 2](https://steamcommunity.com/app/2162800/discussions/0/785450979403484545/)
- Shapez 1 used a *specific shape* as blueprint currency, so the player had to build and maintain a dedicated line feeding a non-production tool. That makes it genuinely needed, at the cost of spending factory throughput on the tool [snippet] — [Steam shapez 1](https://steamcommunity.com/app/1318690/discussions/0/2569816094929939890)
- DSP Metadata is earned from throughput (matrices/min) but spent only on research skips or matrix redemption in *another* seed. Inside any one save, factory ratios are untouched. It shortens the early tech climb of the next run [snippet] — [DSP Wiki Metadata](https://dsp-wiki.com/Metadata)
- Captain of Industry Unity is a hybrid. Its quick-build and repair uses sit outside throughput, but "boost" uses (-0.25 Unity per building) raise production speed. Players report using Unity boosts on blast furnaces to cover coal shortages, i.e. to patch ratio deficits [snippet] — [CoI Wiki Unity](https://wiki.coigame.com/Unity); [earlyguides CoI](https://earlyguides.com/captain-of-industry/tips)

### Inferences
- For a design that "must not change production/rotation/stress/ratio math": the Satisfactory shard and Somersloop model and CoI Unity *boost* are counter-examples, because they are rate multipliers. The safe families are (1) spending on the build/edit tool (Shapez), (2) spending on a progression skip across runs (DSP), and (3) spending on logistics *capacity* outside the graph (Satisfactory Dimensional Depot upload rate: it moves items into central storage and does not change recipes).
- Shapez 2 shows the failure mode of "currency for tools": if the faucet is generous and tied to normal play, it stops being a real constraint. Shapez 1 shows the opposite failure: if the currency is a factory product, the factory must be sized for it, which ties factory scale to the currency.
- Overclocking sentiment (inferred from the design notes; see Q5 for gaps): Satisfactory keeps the math planner-friendly because clock is a continuous dial, power cost is a closed formula, and underclocking is free. The rate change is *legible*, not hidden. A star-fragment rate modifier, however legible, would still violate the brief.

### Gaps
- No quantified player sentiment on whether overclocking "ruins" ratio planning (Reddit and Steam unreadable).
- No source on how Shapez 2 devs justify BP as a gate.

## Q3. Patterns where a scarce resource is spent on the *capacity of the player's tools* (blueprint size, editor features, number of active blueprints, copy/paste) rather than production

### Takeaway
There are three confirmed instances: Shapez 1/2 (paste costs currency), Satisfactory Dimensional Depot (rare spheres buy upload rate and stack capacity of a remote-access logistics tool), and CoI Unity quick-build (currency buys instant construction delivery). None of the verified sources show a game that charges for *editor features* or the *number of saved blueprints*. That niche looks open.

### Cited Findings
- Shapez 2: every paste costs Blueprint Points in proportion to the blueprint's contents (example: 237 buildings = 1216 BP) [snippet] — [Steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3320548627)
- Shapez 1: a dedicated shape is the paste currency [snippet] — [Steam shapez 1](https://steamcommunity.com/app/1318690/discussions/0/2569816094929939890)
- Satisfactory: Mercer Spheres (fixed count, 97 total for all upgrades) raise Dimensional Depot upload rate in tiers (to 120/min, then 240/min) and depot upgrades. This is pure tool capacity: how fast you can pull materials into the build gun's remote inventory [snippet] — [satisfactory.wiki.gg DD Uploader](https://satisfactory.wiki.gg/wiki/Dimensional_Depot_Uploader)
- CoI Unity "instantly deliver resources to construct buildings," i.e. it buys construction-tool speed. Players say most of their Unity goes to quick build and remove [snippet] — [CoI Wiki Unity](https://wiki.coigame.com/Unity); [Steam CoI](https://steamcommunity.com/app/1594320/discussions/0/603029525548267213/)

### Inferences
- Pricing a *per-use* action (paste in Shapez 2, quick-build in CoI) needs a continuous faucet, and the cost loses meaning once the faucet is large (Shapez 2 reviewer). Pricing *permanent capacity tiers* (Satisfactory depot) creates real desire but ends once the tiers are bought. A non-inflationary, endless version would need capacity that resets, is re-allocatable (like moving Somersloops around), or is sized against a fixed *slot budget* rather than an unbounded tier ladder.
- Somersloop "move it to where it matters now" behaviour is a useful template. A fixed or slow stock that the player *re-allocates* among tool slots (for example blueprint slots, editor overlays, saved layout count) gives endless decisions without inflation. The scarcity is in allocation, not accumulation.
- Brief caution: a tool-capacity spend can slip into "convenience-only," which was rejected. It counts as "genuinely needed" only if the tool is the main way a large factory gets built, as with Shapez paste at scale.

### Gaps
- I found no verified examples of currency-gated blueprint *slot count*, blueprint *size limits*, or editor features in Factorio, Foundry or Techtonica. Couldn't search further within budget.

## Q4. Patterns where the resource governs *rules* (modifiers, challenges) or meta-progression across saves

### Takeaway
DSP Metadata (cross-save research skip, scaled by difficulty) and Against the Storm Citadel Resources (cross-run capped permanent bonuses, including rule-like ones such as slower Impatience) are the verified models. Both tie payout to difficulty or success, and both cap or rate-limit to stop inflation.

### Cited Findings
- DSP: harder settings (resource multiplier below 1x) pay more metadata. Easier settings pay less [snippet] — [DSP Wiki Metadata](https://dsp-wiki.com/Metadata)
- DSP: metadata can't be spent in the seed (cluster address) that earned it. This forces a *new* save to cash in, so it rewards restarts and variety rather than a single snowball [snippet] — [DSP Wiki Metadata](https://dsp-wiki.com/Metadata); [Steam clarification](https://steamcommunity.com/app/1366540/discussions/0/3803901984157405416/)
- DSP anti-inflation: payout is a *peak rate* (average matrices/min over the last hour), and only increases since the last export count. Idling a save longer earns nothing [snippet] — [DSP Wiki Metadata](https://dsp-wiki.com/Metadata); [Steam](https://steamcommunity.com/app/1366540/discussions/0/594036392036029806/)
- Against the Storm: permanent upgrade lines have hard caps (production speed max +28%). Unlocking rows is gated by player level (since 2022). Resources only carry over on a successful expedition [snippet] — [Hooded Horse wiki](https://wiki.hoodedhorse.com/Against_the_Storm/Upgrades); [Destructoid](https://www.destructoid.com/how-to-get-and-keep-artifacts-in-against-the-storm/); [Eremite](https://eremitegames.com/progression-update/)
- CoI edicts are toggleable global rule modifiers, some paid in monthly Unity upkeep. A rule is "rented" by a recurring cost instead of bought outright [snippet] — [CoI Wiki Edicts](https://wiki.coigame.com/Edicts)

### Inferences
- The DSP "pay by peak rate, not total; only deltas count" rule is a strong anti-inflation template for any endless faucet. For 별의 조각 this means paying for *best-ever* or *new* anime-mode achievement and not cumulative minutes, which would also stop tying factory size to anime time.
- CoI's *upkeep-priced* rules (edicts with monthly Unity) are a model where a resource is endlessly useful with no stockpile inflation: the spend recurs, and the player chooses which rules to keep active. If the rules are factory-*constraint* modifiers (challenge rules), they change what the player solves without changing recipe ratios.
- Against the Storm's caps show permanent meta bonuses must hit a ceiling to avoid power creep, which conflicts with "endlessly useful." Endless usefulness then has to come from re-allocation or upkeep, not accumulation.

### Gaps
- No verified data on Shapez 2 challenge or scenario modifiers bought with currency, Factorio Space Age meta, or Palworld Ancient Technology Points (search budget exhausted).

## Q5. Player sentiment: which special resources feel great vs annoying

### Takeaway
Verified sentiment is thin, from snippets only. Fixed-count scavenger resources produce "hit a wall" or "only 106" frustration (Frostpunk cores, Somersloops). Currencies with an overly generous faucet become irrelevant (Shapez 2 BP). Players actively budget emergency-use currencies like CoI Unity and praise them as a safety valve.

### Cited Findings
- Frostpunk: a player "explored every possible scouting node and could no longer build advanced structures or automatons" [snippet] — [Gamepressure / Steam](https://www.gamepressure.com/frostpunk/how-to-get-steam-cores/z3ad86)
- Satisfactory: the "only 106 Sloops" question about duping shows players feel the hard cap [snippet] — [Steam](https://steamcommunity.com/app/526870/discussions/0/4423185135322244328)
- Satisfactory APA: "you will likely spend more power trying to keep one augmenter supplied than you will gain." A guide author prefers spending Somersloops on amplification [snippet] — [Steam](https://steamcommunity.com/app/526870/discussions/0/4843148768111246870); [Satisfactory Power guide](https://exploreation-exploitation-automation.netlify.app/)
- Shapez 2: BP "rarely a constraint" (RPS), "extremely easy to build a farm" (player) [snippet] — [RPS](https://rockpapershotgunom.pages.dev/posts/shapez-2-early-access-review-splendid-abstract-factory); [Steam](https://steamcommunity.com/app/2162800/discussions/0/785450979403484545/)
- CoI: a guide says repairing with Unity "costs seconds" versus a full in-game month of rebuilding a stalled chain, and warns against wasting Unity on construction speed early [snippet] — [earlyguides CoI](https://earlyguides.com/captain-of-industry/tips)
- DSP: players discuss metadata mechanics (cluster address, delta export) in depth. I found no "cheating" complaints in the search results [snippet] — [Steam clarification](https://steamcommunity.com/app/1366540/discussions/0/3803901984157405416/)

### Inferences
- "Great" correlates with a resource that solves a crisis or opens a new run (Unity repair, DSP fresh-seed skip). "Annoying" correlates with a hard cap combined with map scavenging (cores, sloops) or a meaningless price (Shapez 2 BP).
- For 별의 조각: avoid a fixed total (cap frustration) and avoid a per-action price small enough to ignore. The best-supported shape is a re-allocatable or upkeep spend on tool capacity or rule modifiers, with an anti-inflation faucet like DSP's.

### Gaps
- Reddit threads on Somersloop hunting, power slug collection and DSP metadata were not reachable, so no quotes. Search returned no relevant Reddit snippets.
- Not researched or verified (budget/network): Techtonica cores, Palworld Ancient Technology Points, Factorio Space Age non-producibles, Mindustry, Create (experience nuggets), ONI, Timberborn, Foundry, Infinifactory, Opus Magnum, Factory Town. The report writer should not cite specifics for these without another check.
