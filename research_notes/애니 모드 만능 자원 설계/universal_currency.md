# Universal ("spend it anywhere") currencies earned from activity/time, and their endless sinks

Context reminder: target resource is "실타래", earned in eyes-free "anime mode" (controller input while watching anime). It is not a factory material, not for gacha/monsters, must not change factory throughput math, must be endlessly useful, with no caps, no stamina, no fail states and no periodic checking. Construction or placement is a likely sink.

Research notes: about 17 tool calls. nookipedia.com and gamerant.com fetches failed because the hosts are outside the session's allowed network. Most findings are from search-result snippets, marked [snippet]. Reddit was not reachable directly. Sentiment comes from forums, press and Steam discussions surfaced in search.

---

## 1. Examples: how each currency is earned and spent

### Takeaway
The best match for 실타래 is a currency earned from "living in the game" that buys unlocks, convenience, decor or construction and can never become the main money: Nook Miles, Qi Gems and Fortnite's any-mode XP all work this way. Satisfactory's coupons and Pokémon Sleep's Dream Shards differ. Coupons are fed by production surplus. Dream Shards feed character power, so they become a bottleneck. Genshin's Resin is the clearest anti-pattern: capped stamina, widely called a chore.

### Cited Findings
**Animal Crossing: New Horizons, Nook Miles**
- Earned from everyday activities and achievements. For example, talking to every villager on the island in one day earns 300 Miles. A daily Nook Stop check-in is another easy source. [snippet] — [iMore](https://www.imore.com/animal-crossing-new-horizons-how-earn-nook-miles-fast); [Game8](https://game8.co:443/games/Animal-Crossing-New-Horizons/archives/284018)
- After the house loan is paid, the program becomes Nook Miles+. It adds more redeemable items and new small rotating tasks, and some tasks carry multipliers of up to 5x. [snippet] — [iMore: What are Nook Miles](https://www.imore.com/animal-crossing-new-horizons-what-nook-mileage-program)
- Spent at the Nook Stop ATM terminal on items and feature unlocks. The Nook Miles Ticket costs 2,000 Miles, flies the player to a random mystery island, and can be bought repeatedly. The first ticket is free. Example prices: Custom Design Pro Editor 800, Triangular Topiary 1,000, Pretty Good Tools recipes 3,000. [snippet] — [iMore guide](https://www.imore.com/animal-crossing-new-horizons-nook-miles-guide); [GamerGuides](https://gamerguides.com/animal-crossing-new-horizons/guide/nook-miles/earning-nook-miles/spending-nook-miles); [GamesRadar](https://gamesradar.com/how-to-get-nook-miles-tickets-animal-crossing-new-horizons)
- No source showed a way to convert Miles into Bells, the main money. [snippet; absence of evidence] — [search summary incl. Shacknews 2.0 notes](https://shacknews.com/article/127536/animal-crossing-new-horizons-update-200-patch-notes-add-brewster-kappn-and-more)

**Pokémon Sleep, Dream Shards (contrast: a universal currency tied to power)**
- Spent alongside Candy to level up Pokémon. The shard cost per Candy climbs from 14 at Level 1 to 309 at Level 50. [snippet] — [Serebii level-up table](https://www.serebii.net/pokemonsleep/pokemonlevel.shtml)
- "The amount of Dream Shards a Pokémon needs will only grow as it becomes stronger." [snippet] — [Gameranx](https://gameranx.com/features/id/471669/article/pokemon-sleep-what-are-dream-shards-and-how-to-get-them/)
- Candy Boost trades about 6x or more the usual shards for faster EXP. This is a voluntary premium sink. [snippet] — [Game8](https://game8.co/games/Pokemon-Sleep/archives/419854)
- Earned mainly from sleep research, which means simply sleeping. Rewards were raised in Version 1.10.0 (August 2024) to "make the game easier to play". Version 2.6.0 added diminishing returns: from the 11th Pokémon researched in a day, shards and research EXP are halved. [snippet] — [Bulbagarden](https://bulbagarden.net/threads/more-information-released-on-pokemon-sleeps-august-update-with-adjustments-to-rewards-to-improve-playability.302464/latest); [PokemonGoHub 2.6.0](https://pokemongohub.net/post/sleep/pokemon-sleep-version-2-6-0/)

**Satisfactory, AWESOME Sink and FICSIT Coupons (contrast: fed by the factory)**
- Any item sunk gives points. Points convert to coupons on an escalating curve: the first 3 coupons cost 500 points each, then the nth coupon costs 250 × (ceil(n/3) − 1)² + 1000 points. The cost freezes at 249,501,250 points from coupon 2,998 onward. A Chinese wiki gives different constants (500 multiplier, 1,000 for the first coupons), so the constants are disputed. — [Satisfactory Wiki: AWESOME Sink](https://satisfactory.wiki.gg/AWESOME_Sink); [BWIKI](https://wiki.biligame.com/satisfactory/AWESOME_Sink)
- One player estimate puts about 750 coupons at about 4 billion cumulative points. [snippet] — [Steam discussion](https://steamcommunity.com/app/526870/discussions/0/4843149419127011219)
- Alien DNA Capsules use a separate counter that scales linearly, +1,000 points per coupon group. Each sink type has its own escalation. [snippet] — [Satisfactory Wiki](https://satisfactory.wiki.gg/AWESOME_Sink); [Steam](https://steamcommunity.com/app/526870/discussions/0/3801649759599050781)
- The AWESOME Shop sells signs, lights, walls, foundations, beams, pillars, roofs, windows, swatches and patterns, plus repeatable part purchases (for example, Modular Frames for a few coupons). All one-time unlocks cost only 347 coupons in total. [snippet] — [Satisfactory Wiki: AWESOME Shop](https://satisfactory.wiki.gg/wiki/AWESOME_Shop); [4netplayers](https://www.4netplayers.com/en/blog/satisfactory/satisfactory-awesome-sink-shop-coupons)

**Stardew Valley, Qi Gems**
- Earned from Mr. Qi's Special Orders (for example, Qi's Crop Quest pays 100 gems; several orders pay 40–50), from Shrine of Challenge mode in the Mines, and by trading surplus Golden Walnuts. Sources disagree on the walnut-to-gem rate. [snippet] — [Stardew Wiki: Qi Gem](https://stardewvalleywiki.com/Qi_Gem); [TheGamer](https://www.thegamer.com/stardew-valley-qi-gems-guide/)
- Spent only in Qi's Walnut Room vending machine. They cannot be sold for gold (g). [snippet] — [Stardew Wiki: Qi's Walnut Room](https://stardewvalleywiki.com/Qi%27s_Walnut_Room)

**Slime Rancher 1/2, Newbucks (main money; shows the late-game surplus problem)**
- In Slime Rancher 2, Newbucks buy Conservatory plots for slimes, food or storage, plus Vacpack and item upgrades. [snippet] — [Slime Rancher Wiki: Newbucks](https://slimerancher.fandom.com/wiki/Newbucks)
- In Slime Rancher 1, the developers adjusted the 7Zee Rewards Club costs, which now cap at 150k. This is a status ladder used as an endgame money sink. [snippet] — [Steam dev post](https://steamcommunity.com/app/433340/discussions/0/133262848301155784)

**Palworld, Technology Points and Ancient Technology Points (contrast: finite)**
- Technology Points: 6 per level-up, plus fast-travel points and Technology Manuals. Ancient Technology Points come only from first-time boss kills (5 per Syndicate Tower boss), once per Alpha Pal, and from Ancient Technical Manuals. The wiki (v0.7.0) lists 72 points from Alpha Pals and 35 from tower bosses. Older guides give much lower totals. These are finite unlock currencies, not endless ones. [snippet] — [Palworld Wiki: Technology Points](https://palworld.wiki.gg/wiki/Technology_Points); [Palworld Wiki: Ancient Technology Points](https://palworld.wiki.gg/wiki/Ancient_Technology_Points); [Destructoid](https://www.destructoid.com/how-to-get-more-technology-points-in-palworld/)

**Fortnite, "XP from any experience" (earn by playing anything)**
- Since December 1, 2024 the Battle Royale, Music and LEGO passes all advance from XP earned in any Fortnite experience, except Save the World. — [Fortnite news, Oct 28 2024](https://www.fortnite.com/news/coming-soon-progress-your-fortnite-passes-by-playing-any-experience?lang=en-US); [Epic help](https://www.epicgames.com/help/fortnite-battle-royale-c-34254770/gameplay-c-33726977/how-to-earn-xp-in-fortnite-a17775130)
- Mode caps still exist: LEGO Fortnite has a daily cap of 420,000 XP. The weekly Creative cap is 4.0M (Chapter 6) or 4.8M (Chapter 7, unverified), about 60 levels. Epic changed caps without notice, which drew backlash. [snippet] — [Prima Games](https://primagames.com/tips/lego-fortnite-xp-cap-explained); [PC Gamer](https://www.pcgamer.com/games/battle-royale/fortnites-drastically-diminished-save-the-world-xp-rewards-is-a-bug-epic-says/); [AllThings.How](https://allthings.how/fortnite-chapter-7-xp-guide-fast-ways-to-level-up/)

**Genshin Impact, Original Resin (contrast: capped stamina)**
- Original Resin is a regenerating stamina that gates rewards from key activities. HoYoverse raised the cap from 160 to 200, the first increase since 1.1. Critics called it "a band-aid on a big open wound". — [Escapist](https://www.escapistmagazine.com/genshin-impact-increases-maximum-resin-cap-for-the-first-time-in-years/); [PC Gamer](https://www.pcgamer.com/genshin-impact-resin-patch-changes); [TheGamer](https://www.thegamer.com/genshin-impact-resin-problem-fix/)

**Pikmin Bloom, steps**
- Walking is the core loop: steps grow Pikmin, plant flower petals along routes, and drive leveling (steps, Pikmin grown, expeditions). Niantic's pitch is "an app that brings a little joy to your everyday journeys on foot". — [Wikipedia: Pikmin Bloom](https://en.wikipedia.com/wiki/Pikmin_Bloom); [TechRadar](https://www.techradar.com/au/news/why-im-counting-on-pikmin-bloom-to-reinvigorate-my-daily-walks)

**Islanders, score as currency**
- Earning points refills the building inventory. Reaching thresholds unlocks a choice between two building packs and eventually lets the player move to a new island. Score is cumulative across islands. In Islanders: New Shores, some thresholds give one-time "boons" instead of buildings. — [Wikipedia: Islanders](https://wikipedia.com/wiki/Islanders_(game)); [Inverse](https://www.inverse.com/gaming/islanders-new-shores-nintendo-switch-xbox-playstation-pc)

**Rusty's Retirement (idle desktop-bar farm)**
- Runs as a narrow bar on the desktop beside other work. Currencies include Spare Parts (upgrades and expansion) and Biofuel. The Spare Parts and Biofuel description comes from a fan guide. [snippet] — [Destructoid](https://www.destructoid.com/?p=1090101); [shapes.inc fan guide](https://shapes.inc/guides/rusty-s-retirement-guide)

### Inferences
- The examples sort along three axes:
  - **Source:** activity or time (Nook Miles, Dream Shards, Fortnite XP, Pikmin steps, 실타래) versus production surplus (Satisfactory coupons).
  - **Sink:** power (Dream Shards, which become a bottleneck) versus access, convenience and decor (Nook Miles, Qi Gems, AWESOME Shop).
  - **Supply:** finite (Palworld ATP, Islanders unlocks) versus endless.
- 실타래 should be activity-sourced, access/decor/construction-sinked and endless. That places it closest to Nook Miles+ plus repeatable tickets, combined with Satisfactory's escalating-cost curve as the endless tail.
- Satisfactory shows that a separate escalating counter per sink type works: DNA Capsules scale linearly while items scale quadratically. That fits a design where each 실타래 sink category has its own cost curve.

### Gaps
- Not researched in this pass because of the tool budget: Melvor Idle, Minecraft emeralds/XP, Terraria, Bongo Cat, Warframe, Destiny XP or Engrams, Dorfromantik's progression. From background knowledge only, unverified:
  - Minecraft XP is spent on enchanting and anvils, and anvil repairs show "Too Expensive!" past level 40, a famous hard ceiling. Mending turned XP into an endless repair sink.
  - Bongo Cat (Steam 2025) drops cosmetic hats or skins from keystroke and click counts while you do other work, the closest analogue to "earn while doing something else".
  - Verify all of these before relying on them.
- Nookipedia (exact Nook Miles+ task counts and caps) could not be fetched because the host is blocked.

---

## 2. Endless sinks: keeping the currency worth collecting after hundreds of hours, and failure cases

### Takeaway
Endless value comes from four things: escalating costs (Satisfactory's quadratic coupon curve, Dream Shard cost per level), repeatable consumable purchases (Nook Miles Tickets, Kapp'n tours), periodic new content (ACNH 2.0), and a status or prestige ladder (Slime Rancher 7Zee). The failure mode is a currency left with nothing to buy: Nook Miles before 2.0, a 200k-plus Newbucks hoard in Slime Rancher 2, and Destiny 2 Legendary Shards, which ended in the currency being deleted outright.

### Cited Findings
- **Escalating cost:** Satisfactory's coupon cost grows quadratically per group of 3 and freezes at about 249.5M points per coupon. The curve gives surplus production a destination forever. — [Satisfactory Wiki](https://satisfactory.wiki.gg/AWESOME_Sink)
- **Escalating cost tied to power creates scarcity rather than surplus:** in Pokémon Sleep the shard cost per Candy rises from 14 to 309 by Level 50. An official notice (Japanese, undated) acknowledged that leveling several Pokémon in parallel had become hard and promised gradual improvements. [snippet] — [Serebii](https://www.serebii.net/pokemonsleep/pokemonlevel.shtml); [Game8 JP](https://game8.jp/pokemonsleep/542176)
- **Repeatable consumable:** the Nook Miles Ticket (2,000 Miles) can be bought without limit and is the main late-game Miles sink. Its value "fluctuates drastically depending on your goals, resources, and… patience". [snippet] — [GamesRadar](https://gamesradar.com/how-to-get-nook-miles-tickets-animal-crossing-new-horizons); [CyberPost](https://cyberpost.co/?p=1117664)
- **Failure, then a fix by new content:** guides note that after the early essentials there is "much less to do with your miles". The 2.0 update (November 4, 2021) expanded the Nook Stop inventory and added repeatable Kapp'n boat tours to mystery islands for 1,000 Miles each, a "Be a Chef!" recipe pack for 2,000 Miles, new furniture and hairstyles, and 9 new Nook Miles achievement categories. Press described Miles as having "a substantial increase in their value". [snippet] — [Sportskeeda: 9 new achievements](https://www.sportskeeda.com/esports/news-animal-crossing-new-horizons-2-0-update-introduces-9-new-unlockable-nook-miles-achievements); [GameRant headline](https://gamerant.com/animal-crossing-new-horizons-november-update-nook-miles-valuable-good/); [Shacknews](https://shacknews.com/article/127536/animal-crossing-new-horizons-update-200-patch-notes-add-brewster-kappn-and-more)
- **Failure in a fan economy:** NMTs were "a grind to obtain and of little use in-game" but became high-value trading currency between players. [snippet] — [Nintendo Life](https://nintendolife.com/features/soapbox-crossing-the-line-how-i-helped-corrupt-the-animal-crossing-economy)
- **Failure from a hoard with nothing to buy:** a Slime Rancher 2 player shelved the game "until we can actually use the 200k+ monies" (December 2023). The suggested fix was to gather resources for locked items. [snippet; single anecdote] — [Steam discussion](https://steamcommunity.com/app/1657630/discussions/0/4038102936181554599)
- **Prestige or status ladder as a sink:** Slime Rancher 1's 7Zee Rewards Club, with costs capped at 150k by a developer adjustment, was described by a player as the endgame: "once you have your ranch figured out… what else is there to do but maximize profits?" [snippet] — [Steam](https://steamcommunity.com/app/433340/discussions/0/133262848301155784)
- **Worst-case failure, deleting the currency:** Bungie removed Legendary Shards from Destiny 2 (announced in This Week at Bungie, September 14, 2023; costs phased out from Season 23; fully deprecated with The Final Shape, June 2024). Bungie's stated reasons were that shards were "an unstable part of the Destiny 2 economy" and that removal reduced currency bloat. No exchange was offered for stockpiles; one player lost 18,847 shards. Afterwards Glimmer took over as the sink and was criticized as inflated (for example, an Iron Banner weapon costs 25,000 Glimmer plus an engram). — [PC Gamer](https://pcgamer.com/destiny-2-is-going-to-delete-one-of-its-main-currencies-because-players-used-exploits-to-stockpile-too-much); [GameSpot](https://www.gamespot.com/articles/destiny-2-is-saying-goodbye-to-legendary-shards-from-season-23/1100-6517745/); [Dexerto](https://dexerto.com/destiny/destiny-2s-iron-banner-highlights-the-glaring-problem-with-glimmer-3002206)
- **Diminishing returns as an anti-inflation lever:** Pokémon Sleep 2.6.0 halves shard yield from the 11th research per day. This is effectively a soft cap, which 실타래 rules out. — [PokemonGoHub](https://pokemongohub.net/post/sleep/pokemon-sleep-version-2-6-0/)

### Inferences
- With no caps allowed, 실타래 cannot control inflation on the supply side the way Sleep 2.6.0 or Fortnite's XP caps do. The sinks must absorb unlimited input. The proven tools for that are:
  - an escalating per-category cost curve, as in Satisfactory, so cost per unit rises with how much you have already bought or built;
  - construction costs that scale with base size, such as the nth decorative or placement piece costing more, or footprint or tier-based pricing;
  - a repeatable consumable that is always worth one more, like the NMT;
  - an endless prestige or status track, such as a cosmetic "loom level" or rank like 7Zee.
- Lessons from Destiny's Legendary Shards: never let the currency feed the core economy's costs, or stockpiles become a balance problem the designers can only fix by deletion. And never delete without converting; players hated losing their hoards.
- One-time unlocks run out fast (Satisfactory's 347 coupons, ACNH's essentials). A pure unlock shop will hit the Nook Miles "nothing left" wall. A repeatable or escalating tail is mandatory.

### Gaps
- No reliable data on how much Nook Miles active players hold after hundreds of hours. A Bell Tree forum thread asking this exists but was not fetched.
- No developer postmortem or GDC talk found specifically on sink design for activity currencies. Not searched this pass.

---

## 3. Preventing the universal currency from becoming an economy multiplier or a pay-to-skip of the main loop

### Takeaway
Successful examples wall the currency off from the main economy. You cannot convert Nook Miles to Bells or sell Qi Gems for gold, and both are spent only in a dedicated shop. The cautionary cases are currencies that buy production or power: Satisfactory's coupons buy parts and Dream Shards buy levels.

### Cited Findings
- Qi Gems "cannot be sold for g" and can only be spent in Qi's Walnut Room. — [Stardew Wiki: Qi Gem](https://stardewvalleywiki.com/Qi_Gem)
- No Miles-to-Bells conversion found. Miles buy tickets, recipes, decor, app upgrades and tours. [snippet] — [Shacknews](https://shacknews.com/article/127536/animal-crossing-new-horizons-update-200-patch-notes-add-brewster-kappn-and-more); [iMore](https://www.imore.com/animal-crossing-new-horizons-nook-miles-guide)
- Satisfactory's AWESOME Shop sells repeatable production parts (for example, Modular Frames), so coupons can stand in for a production line players haven't built yet. This is a mild production leak, tolerable only because coupons come from the factory itself. [snippet] — [4netplayers](https://www.4netplayers.com/en/blog/satisfactory/satisfactory-awesome-sink-shop-coupons)
- Most AWESOME Shop items are building and decor (signs, lights, walls, foundations, beams, pillars, roofs, windows, swatches, patterns). Lights draw power. — [Satisfactory Wiki: AWESOME Shop](https://satisfactory.wiki.gg/wiki/AWESOME_Shop)
- Islanders spends score only on more buildings and placement options, never on score multipliers bought directly. — [Wikipedia: Islanders](https://wikipedia.com/wiki/Islanders_(game))
- Destiny 2's shards fed gear costs and were dupe-exploited into a "too rich or too poor" wealth gap. [snippet] — [Mein-MMO](https://mein-mmo.de/en/destiny-2-deletes-its-most-important-currency-because-you-are-either-too-rich-or-too-poor-and-have-cheated-anyway,1035896)

### Inferences
Guardrails for 실타래, synthesized from the patterns above:
1. **Make it a one-way wall.** 실타래 never converts into factory items or main money, and the reverse never happens either, so factory throughput math stays untouched. This is the Qi Gem and Nook Miles rule.
2. **Buy capability-neutral things.** 실타래 should buy construction, placement, cosmetic and access content, such as decor blocks, base expansion, new biomes or areas, and layout conveniences. It should never buy items, machines' output, speed multipliers or monster power.
3. **If it pays for building, make it a parallel cost for non-functional pieces.** Satisfactory's lights draw power, a reminder that even "decor" can touch the main economy. For 실타래 decor, keep zero gameplay side effects, or have 실타래 pay only the "placement fee" while functional machines keep their factory-material cost.
4. **Avoid coupon-for-parts shortcuts.** Satisfactory's part purchases are the exact leak to avoid, because 실타래 comes from time, not production.

### Gaps
- No designer quotes found that explicitly explain why Bells and Miles are non-convertible. This is inferred from the observed design.

---

## 4. Player sentiment: rewarding or chore-like?

### Takeaway
Activity-earned currencies feel good when they reward what the player would do anyway: Pikmin Bloom, early Nook Miles. They feel like chores when tied to caps, dailies or a power bottleneck: Genshin Resin, Fortnite's surprise XP caps, Dream Shard shortages. Nook Miles' specific late-game complaint is that the main sink, tickets, serves time travelers and island-hunters, leaving little for everyone else.

### Cited Findings
- Pikmin Bloom "adds just the right amount of reward to a walk without distracting from the actual activity" and "doesn't require a lot of your attention". Critics call it monotonous. — [TechRadar](https://www.techradar.com/au/news/why-im-counting-on-pikmin-bloom-to-reinvigorate-my-daily-walks); [Engadget](https://www.engadget.com/pikmin-bloom-has-been-helping-me-meet-my-outdoor-walking-goals-for-years-000025214.html); [App Store reviews](https://apps.apple.com/us/app/-/id1556357398)
- A Bell Tree forum user complained that Nook Miles are "extremely focused towards time travel". [snippet] — [Bell Tree Forums](https://www.belltreeforums.com/threads/i-despise-nmt.534653)
- A "Nook Miles+ and Binge-Playing" essay argues that Nook Miles+ rewards binge sessions; title and snippet only, not fetched. [snippet] — [Pixel Poppers](https://pixelpoppers.com/2020/03/nook-miles-and-binge-playing/)
- Genshin Resin is "much-hated" and limits how often you can get rewards. Fans asked for years for cap increases; a developer non-answer upset them. — [TheGamer](https://www.thegamer.com/genshin-impact-resin-problem-fix/); [Sportskeeda](https://sportskeeda.com/esports/genshin-impact-fans-unhappy-hoyoverse-responds-resin-issues-lack-endgame-content)
- Fortnite: unannounced XP caps drew backlash ("Epic said nothing at all about the new XP cap prior to pushing it live"). Shared any-mode XP was received as "makes every mode worth playing". — [PC Gamer](https://www.pcgamer.com/games/battle-royale/fortnites-drastically-diminished-save-the-world-xp-rewards-is-a-bug-epic-says/); [Dexerto](https://dexerto.com/fortnite/fortnite-reveals-huge-battle-pass-change-that-makes-every-mode-worth-playing-2965697)
- Destiny shard removal: one critic wrote "I won't miss you", while others feared "the MMO's next currency disaster". — [Destructoid](https://www.destructoid.com/bon-voyage-destiny-2-legendary-shards-i-wont-miss-you/); [GamesRadar](https://gamesradar.com/after-6-years-of-dupes-and-complaints-bungies-removing-legendary-shards-from-destiny-2-which-could-be-amazing-or-the-mmos-next-currency-disaster)
- Islanders: score-chasing makes players "curb aesthetic instincts" and build "ugly clumps… just for the score". Dorfromantik players cared about aesthetics instead. — [Edge via Magzter](https://magzter.com/fr/stories/Entertainment/Edge/Islanders); [search summary](https://www.inverse.com/gaming/islanders-new-shores-nintendo-switch-xbox-playstation-pc)
- Rusty's Retirement is praised for idle play "on the side while focusing on other things". [snippet] — [Destructoid](https://www.destructoid.com/?p=1090101)

### Inferences
- 실타래's eyes-free, no-cap, no-check design avoids the Resin and daily-task chore pattern by construction. The remaining risk is the Nook Miles late-game "nothing worth buying" problem, which makes the sink design in section 2 critical.
- The Islanders lesson: if 실타래 cost scales with building, keep the pricing from punishing beautiful but inefficient layouts. Price by count or tier, not by "efficiency", so it doesn't push players into ugly optimal clumps.
- The Fortnite lesson: never quietly change earn rates. Players treat accrued time-currency as owed.

### Gaps
- Reddit was not reachable; no direct quotes on Dream Shards ("shard poor" sentiment is widely known but unsourced here). No Steam review aggregate on Bongo Cat was gathered.

---

## 5. Presentation: counters, session summaries, visual piles

### Takeaway
Little sourced material was found. The cited examples show a dedicated terminal or shop as the "place" where the currency lives (the Nook Stop ATM, Qi's vending machine) and petals and flowers as a visible trail of earned activity (Pikmin Bloom).

### Cited Findings
- Nook Miles are redeemed at a physical ATM-like terminal in Resident Services. This gives the currency a diegetic home. — [Shacknews / search summary](https://shacknews.com/article/127536/animal-crossing-new-horizons-update-200-patch-notes-add-brewster-kappn-and-more)
- Pikmin Bloom turns steps into planted flowers along the route, a visible map trace of accumulated activity. Events tie step goals to planting counts. — [Wikipedia](https://en.wikipedia.com/wiki/Pikmin_Bloom); [Digital Trends via search](https://digitaltrends.com/?p=2833821)
- Rusty's Retirement presents its idle economy as a thin bar along the edge of the desktop. — [Destructoid](https://www.destructoid.com/?p=1090101)

### Inferences
- For 실타래:
  - Show a physical spool or skein pile in the base that visibly grows. The yarn metaphor suits a stacked ball or skein, like Pikmin's flower trail.
  - After each anime-mode session, show a soft "this session you spun N 실타래 (about X minutes)" summary, which fits the no-checking rule because it appears only when the player returns.
  - Spend at a diegetic place, such as a loom or weaver NPC or terminal, in the spirit of the Nook Stop.

### Gaps
- No sources found on "you earned X this session" summary screens (for example, idle-game offline-earnings popups) or on visually stacking currency piles in base builders. Both need a targeted search, for example idle-game offline-progress UI or Melvor offline summary.
