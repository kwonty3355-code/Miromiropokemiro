# Eyes-free, hours-long repetitive controller "fidget" input (fixed button sequence + continuous stick rotation)

Scope note: about 17 search/fetch calls. Most findings come from **search-result snippets/summaries, not full-text fetches**; these are marked [snippet]. Treat exact numbers as needing a check before they go into a final report. Design constraints assumed: no fail state or accuracy check, no decisions, no sound (vibration OK), no need to look, endless, 3 hours continuous, controller first (iPad/PC as alternatives).

## 1. Games using fixed button sequences or stick rotation as a repeated core action, and what makes them satisfying

### Takeaway
The best-documented precedents are Patapon (4-beat face-button "drum" commands, chained into a combo that triggers "Fever"), Mario Party stick-spinning minigames (rotation as raw effort), and fishing "reel" mechanics (spin the right stick to rewind line). Patapon's satisfaction comes from rhythmic entrainment plus a combo payoff, but it fails you for breaking the beat, which our constraints forbid. Mario Party shows that speed-based rotation causes injury. A fidget design should keep the sequence and the rotation and remove both speed and accuracy pressure.

### Cited Findings
- **Patapon:** each command is a 4-beat drum pattern on the face buttons (e.g., Attack = Circle, Circle, Square, Circle "PON PON PATA PON"), with four drums Pata/Pon/Don/Chaka. A pulsing screen border signals the beat. Off-beat or unknown input confuses the tribe and stops it [snippet] — [Wikipedia: Patapon](https://en.wikipedia.org/wiki/Patapon); [Patapon Wiki: Fever Mode](https://patapon.fandom.com/wiki/Fever_Mode)
- **Patapon Fever thresholds disagree between sources:** Wikipedia says Fever comes after a combo of 10 (or early from combo 3+ with perfect sync). The fan wiki says perfect drumming from the 3rd to 9th measure can trigger it, and the 10th measure triggers it automatically. Both say breaking the beat ends the combo and Fever [snippet] — [Wikipedia](https://en.wikipedia.org/wiki/Patapon); contradicted in details by [Patapon Wiki](https://patapon.fandom.com/wiki/Fever_Mode)
- Ratatan (Patapon spiritual successor, 2025) is described as rhythm commands that "demand your attention," i.e., the genre needs attention [snippet] — [Engadget](https://www.engadget.com/gaming/ratatan-demands-your-attention-rhythmically-160048067.html)
- **Mario Party (N64) stick-rotation minigames:** children got blisters and friction burns on the palm from spinning the N64 stick with the palm. A New York Attorney General complaint led Nintendo to offer protective gloves. Roughly 1.2 million children were covered, up to four gloves per family, plus about $75,000 in state legal fees. The "$80 million" figure was an estimated glove cost, not a fine. Sources disagree on the year (reported as 2000 in some, 1998 is the game's launch) [snippet] — [GameSpot: Nintendo Issues Game Gloves](https://www.gamespot.com/articles/nintendo-issues-game-gloves/1100-2541755/); [SVG](https://svg.com/1147366/how-mario-party-and-the-n64-controller-led-to-a-major-lawsuit-against-nintendo)
- **Mario Party Superstars (Switch, 2021)** brought back stick-spin minigames with an on-screen caution: "To avoid irritation to your skin and/or damage to the control stick, do not rotate it with the palm of your hand." [snippet] — [Nintendo Life](https://www.nintendolife.com/news/2022/11/random-nintendo-doesnt-want-you-to-get-mario-party-blisters-this-time-around); [GameSpot](https://gamespot.com/articles/palm-injuring-mario-party-game-is-back-for-the-switch-with-a-warning/1100-6497478/); [Kotaku](https://kotaku.com/minigame-that-gave-kids-cuts-blisters-burns-returns-1847926555)
- A Mario Wiki page exists for the minigame "Reel It In" (stick-spin reeling) [snippet, page not fetched] — [Super Mario Wiki: Reel It In](https://mariowiki.com/Reel_It_In)
- **Fishing reels as stick rotation:** "Rewind the Line" (jam game) has the player spin the right stick in either direction to rewind the line and reel in [snippet] — [itch.io: Rewind the Line](https://boateye.itch.io/rewindtheline). An indie developer described "making the right thumb stick become a physical fishing reel that the player has to spin" [snippet] — [itch.io devlog](https://itch.io/devlog/565055/mobile-title-reveal-another-fishing-title.amp). Other fishing games use stick *pulls* (Yonder) or stick-to-zone plus a button for reeling (Sea of Stars) instead of rotation. A player commented that stick-reeling controls felt "awkward" [snippet] — [Siliconera: Sea of Stars fishing](https://www.siliconera.com/how-to-start-fishing-in-sea-of-stars/); [TV Tropes: Fishing Minigame](https://Tvtropes.org/pmwiki/pmwiki.php/Main/FishingMinigame)
- **Knitting as the "feel" target:** the Riley, Corkhill & Morris (2013, British Journal of Occupational Therapy) international survey found that knitters self-report better mood, calm, and reduced stress. Popular coverage quotes a neuroscientist calling the repetitive pattern "calming, comforting and contemplative," and Daisy Fancourt linking synchronization with repetitive activity to slower heart rate and breathing. These physiological claims come from secondary coverage and were not verified against primary data [snippet] — [Mindbodygreen](https://www.mindbodygreen.com/articles/how-crafting-helps-your-brain); [Keele repository (knitting & wellbeing study)](https://keele-repository.worktribe.com/OutputFile/457521)
- **Fidgeting evidence is mixed:** a review says the evidence for fidget toys "remains controversial and largely reliant on theory." Spinners roughly doubled distracted behavior in children with ADHD (2018), mainly because they draw the eye. Putty and stress balls lack that visual pull. UC Davis (Schweitzer, 2024, 70 adults with ADHD) found that people fidget more as attention wanes, which may help them stay focused. No study tested fidgeting while watching video [snippet] — [Scientific American](https://www.scientificamerican.com/article/fidget-toys-arent-just-hype/); [UC Davis Health](https://health.ucdavis.edu/neurology/news/headlines/does-fidgeting-help-people-with-adhd-focus-/2024/10); [Edutopia](https://www.edutopia.org/article/do-fidgets-help-students-focus)

### Inferences
- Satisfaction ingredients to keep: (1) a short fixed motif, like Patapon's 4 beats; (2) a felt confirmation per step; (3) a soft rhythmic pulse to entrain to; (4) a slow, cumulative payoff that never resets. Ingredients to drop: beat-accuracy checks, combo breaks, and speed-based scoring (the Mario Party injury mechanism).
- The fidget research suggests our input should demand no vision at all. A fidget is only harmless during viewing when it doesn't pull the eyes. Screen-side progress feedback should be optional and peripheral.
- A "Fever-like" state could be triggered by *continuity* (e.g., N cycles completed, at any tempo) rather than accuracy. That keeps the reward but removes the failure.

### Gaps
- Not verified this session (from background knowledge only, no source found): Track & Field mashing details, Taiko no Tatsujin, Rhythm Heaven, Death Stranding balance (L2/R2), Octodad, QWOP, Ape Escape's right-stick controls, Okami brush, Katamari Damacy's twin-stick controls, DDR, Kind Words, Cozy Grove and Animal Crossing crafting. No sources were fetched for these. Bongo Cat is covered under Q5.
- No GDC talk on "satisfying repetitive input" was found within budget.
- I found no quantitative study of what makes repeated controller sequences "satisfying."

## 2. Does a fixed sequence become automatic? (motor learning, chunking, rhythm)

### Takeaway
Yes. Short fixed key sequences become "motor chunks" that can be selected and executed as a unit. In the DSP-task literature this takes about 500–1000 repetitions per sequence. Once chunked, the cognitive processor is free to do another task while the sequence runs, which is exactly the "knit while watching" condition. Predictable timing (rhythm) tied to the sequence helps learning. Rhythm that exists only in motor output does not.

### Cited Findings
- In the discrete sequence production (DSP) task, practicing 500–1000 repetitions per sequence builds motor chunks. A chunk is a limited number of responses selected and executed together [snippet] — [Abrahamse, Ruitenberg, de Kleine & Verwey 2013, "Control of automated behavior: insights from the DSP task" (PMC3601300)](https://pmc.ncbi.nlm.nih.gov/articles/PMC3601300)
- In the dual-processor model, a cognitive processor selects a chunk and loads it into a motor buffer, and extensive training shifts people into a "chunking mode." A 2013 study found the cognitive processor can select the next sequence *or perform another task* while a sequence is being executed [snippet] — [Abrahamse et al. 2013](https://pmc.ncbi.nlm.nih.gov/articles/PMC3601300); [Frontiers in Human Neuroscience 2013 PDF](https://www.frontiersin.org/articles/10.3389/fnhum.2013.00082/pdf)
- People rely more on chunking when they have more explicit knowledge of the sequence [snippet] — [Abrahamse et al. 2013](https://pmc.ncbi.nlm.nih.gov/articles/PMC3601300)
- Older adults show reduced motor chunking compared with young adults (Barnhoorn, Van Asseldonk & Verwey) [snippet] — [Psychological Research](https://link.springer.com/article/10.1007/s00426-017-0967-2)
- A 2023 review in Psychonomic Bulletin & Review covers more than 25 years and over 100 DSP articles [snippet] — [Springer](https://link.springer.com/article/10.3758/s13423-023-02377-0)
- In the serial reaction time (SRT) task, learning is measured as faster RTs on repeating-sequence trials than on random trials. Trial counts vary widely: one reliability study used 1,500 trials, others use 100-trial blocks with a 10-cue sequence. A meta-analysis found that trial count did not significantly affect reliability [snippet] — [Wikipedia: Serial reaction time](https://en.wikipedia.org/wiki/Serial_reaction_time); [PMC11529135](https://pmc.ncbi.nlm.nih.gov/articles/PMC11529135)
- **Rhythm:** predictable temporal information "greatly facilitated" learning of the ordinal sequence, but timing alone wasn't learned. Temporal structure was learned mainly when timing and order were correlated. In one recent paradigm, rhythm was learned in visuomotor and visual-only conditions, but not when rhythm was confined to motor timing alone. A task-irrelevant auditory metre shaped visuomotor sequence learning, and phase-shifting it slowed RTs (2022) [snippet] — [Psychological Research 2022 (UCL PDF)](https://discovery.ucl.ac.uk/id/eprint/10155141/1/s00426-022-01690-y.pdf); [Cambridge: Task-irrelevant auditory metre](https://cms.mus.cam.ac.uk/publications/macintyre-visuomotor/); [PMC3425964](https://pmc.ncbi.nlm.nih.gov/articles/PMC3425964)

### Inferences
- At about 1 sequence per 2–3 s, 500–1000 repetitions is roughly 20–50 minutes. A 4-step sequence would likely feel automatic within the first episode or two of a 3-hour session. This is an extrapolation from lab key-press tasks, not tested on controllers.
- Show or teach the sequence explicitly at first (explicit knowledge aids chunking), then let it fade from view.
- Because "motor-only" rhythm wasn't learned in one study, a *felt* external pulse (a gentle vibration metronome or per-step haptic tick) is more likely to give rhythm benefits than leaving tempo entirely to the player. The sound-free constraint makes haptics the only channel for this. Whether haptic metre works like auditory metre is untested (see gaps).
- Keep the sequence short (3–6 elements) so it fits in one chunk. Longer sequences split into multiple chunks with a concatenation pause.

### Gaps
- No study found on haptic-only (vibrotactile) metre and sequence learning.
- No data on how long chunked sequences stay comfortable or automatic over multi-hour sessions, or whether boredom or fatigue de-chunks them.
- No controller-specific (gamepad) sequence-learning study found.

## 3. Ergonomics and injury risk over 3 hours

### Takeaway
"Gamer's thumb" is De Quervain's tenosynovitis, an overuse tendon-sheath inflammation linked to high-volume thumb use. It is described as more common among console players because of thumbsticks. Mario Party shows that fast, forceful palm rotation causes friction injuries. No study measured continuous thumbstick rotation directly, so design should assume risk scales with speed, force, and uninterrupted volume, and build in variation and low force.

### Cited Findings
- Gamer's thumb is the popular name for De Quervain's tenosynovitis, also called "Nintendo Thumb," "PlayStation Thumb," and "Nintendonitis." It is an overuse condition (excessive, high-volume activity), more common in console gamers due to thumbstick use. Pain sits on the thumb side of the wrist and forearm, worsens after gaming or texting, and eases with rest. It is diagnosed with the Finkelstein test. Treatment includes reducing use, exercise, and a thumb splint [snippet] — [ASSH: Gamer's/Texter's Thumb](https://assh.org/handcare/condition/gamers-texters-thumb); [AAOS press release](https://www.aaos.org/aaos-home/newsroom/press-releases/4-pro-tips-to-help-your-child-defeat-gamers-thumb/); [Esports Healthcare](https://esportshealthcare.com/gamers-thumb-de-quervain/)
- An AAOS hand surgeon's advice: when a child complains of thumb or hand pain, "it's time to put down the device and the game controller." Untreated tenosynovitis may progress to stenosing tenosynovitis (trigger finger) [snippet; the second claim is from a non-clinical source] — [AAOS](https://www.aaos.org/aaos-home/newsroom/press-releases/4-pro-tips-to-help-your-child-defeat-gamers-thumb/); [Esports Healthcare](https://esportshealthcare.com/gamers-thumb-de-quervain/)
- Proma, Imrhan & Ricard measured thumb and index joint motion and EMG in 10 subjects on a PlayStation controller. Natural, unscripted play needed more kinematic and muscular effort than scripted movements, and an extensor muscle was more active than the first dorsal interosseous. The authors note the results may not generalize beyond that controller [snippet] — [Quantifying Finger Strain in Video Gaming (slideshare copy)](https://www.slideshare.net/CSCJournals/quantifying-finger-strain-in-video-gaming)
- A smartphone-gaming study (J. Int. Med. Res., 2019) tracked EMG median-frequency fatigue and subjective discomfort over 30 minutes. Discomfort rose by 30 minutes, and the authors suggested sessions under 20 minutes. This was touchscreen, not thumbstick [snippet] — [DOAJ](https://doaj.org/article/e37ad5ec971f49a4ae60250ccb326164)
- Tablet swiping study (Applied Ergonomics 2023): greater thumb reach and posture change increased forearm muscle activity [snippet] — [CDC Stacks PDF](https://stacks.cdc.gov/view/cdc/207488/cdc_207488_DS1.pdf)
- Mario Party palm-rotation injuries (blisters, friction burns) and the Superstars "don't use your palm" warning — see Q1 sources: [GameSpot](https://www.gamespot.com/articles/nintendo-issues-game-gloves/1100-2541755/), [Nintendo Life](https://www.nintendolife.com/news/2022/11/random-nintendo-doesnt-want-you-to-get-mario-party-blisters-this-time-around)

### Inferences (design recommendations; reasoning, not tested guidelines)
- **No speed requirement, ever.** Progress per rotation should not grow with RPM. Consider capping credited rotation speed (e.g., ≤1 rev/s) so fast spinning gains nothing. Mario Party's harm came from speed contests.
- **Low force and small amplitude:** count rotation from a modest radius (e.g., stick deflection ≥50–60%) so players don't need to grind against the outer gate. This lowers friction and force at the rim.
- **Alternate effectors:** allow the left stick, right stick, or both, plus a button-sequence mode. Credit them equally so the player can switch hands or modes whenever they like. Suggest (by vibration pattern, not a pop-up) a switch roughly every 15–20 minutes. This interval is extrapolated from the smartphone study's <20 min suggestion. It is not a validated stick guideline.
- **Allow either rotation direction** and reversing mid-session, which loads different thumb muscles.
- **Other low-strain channels:** triggers held lightly, gyro tilting ("rock the controller like a cradle"), or a slow alternating L/R press. These spread load away from the thumb carpometacarpal joint and the De Quervain tendons.
- **Idle is fine:** pauses should never be penalized, so natural micro-breaks happen. The game could reward rest through a gentle "stretch" haptic cue, without nagging.
- Avoid encouraging the palm-on-stick grip at all. Mention it in a tutorial tip, as Nintendo now does.

### Gaps
- No EMG or biomechanics study of continuous analog-stick *rotation* was found.
- No evidence-based exposure limit (minutes, or rotations per hour) for thumbstick use was found. Occupational RSI guidance wasn't searched within budget.
- No data was found comparing gyro or trigger input with sticks for fatigue.

## 4. Haptic feedback: per-step "click" or detents for eyes-free confirmation

### Takeaway
Evidence suggests haptic detents mainly add *confidence and confirmation*, not raw speed. In attention-saturated (eyes-free) conditions, haptic texture on detents improved targeting. That fits our case: a per-step or per-angle "tick" to confirm progress without looking. The DualSense adaptive triggers can create a programmable resistance point that "clicks" and releases, which works as a physical ratchet.

### Cited Findings
- Voelker et al. (2015, RWTH Aachen) argue that contradictory results on tangible versus virtual knobs come from eyes-free versus eyes-on conditions. A physical knob gives haptic guidance when users can't look [snippet] — [Voelker et al. 2015 PDF](https://almeida.informatik.rwth-aachen.de/publications/voelker2015c.pdf)
- HapTable: adding frictional "detent" feedback to a virtual knob did not measurably improve completion time or overshoots, but improved perceived confidence and experience. The authors suggest detents act mainly as confirmation [snippet] — [HapTable (arXiv 2103.16510)](https://arxiv.org/pdf/2103.16510)
- A 2024 Université de Lille thesis found that background haptic texture on a virtual knob's perimeter, plus texture on the detents, increased targeting performance under an attention-saturating task [snippet] — [Lille thesis PDF](https://pepite-depot.univ-lille.fr/LIBRE/EDMADIS/2024/2024ULILB025.pdf)
- In a driving study, a rotary knob with varying intermediate haptic feedback let drivers rely less on looking at window position [snippet] — [ORNL: haptic feedback & driver distraction](https://impact.ornl.gov/en/publications/effects-of-varying-haptic-feedback-on-driver-distraction-during-v/)
- UBC SPIN lab work on knob "feel" (detent, friction, inertia) treats feel as a designable affective property [snippet] — [UBC: Exploring Affective Design for Physical Controls (2007)](https://www.cs.ubc.ca/labs/spin/sites/default/files/local_pdfs/2007_ExploringAffectiveDesignforPhysicalControls.pdf)
- **DualSense:** L2 and R2 contain a programmable motor that changes tension and can push back. Reviewers describe a pattern of "pushing back against your finger — then a click, and the resistance is gone." Ratchet & Clank: Rift Apart uses a mid-pull resistance point. Returnal uses a half-pull click for aim and a full pull for alt-fire. NBA 2K21 increases trigger resistance as the player tires. The haptic actuators are described as being like speaker or voice-coil technology [snippet] — [TechCrunch hands-on](https://techcrunch.com/2020/10/27/hands-on-sonys-dualsense-ps5-controller-could-be-a-game-changer/); [PlayStation Blog: Returnal DualSense](https://blog.playstation.com/2021/05/13/how-housemarque-created-returnals-immersive-dualsense-controller-effects/); [GameSpot: PS5 devs on DualSense](https://www.gamespot.com/articles/ps5-developers-reveal-how-theyre-using-the-dualsen/1100-6481186/)

### Inferences
- **Stick rotation:** emit a short, crisp haptic tick every fixed angle (e.g., every 45° or 90°, so 4–8 ticks per revolution), like a ratchet. Add a slightly different "thunk" per full revolution and a richer pattern every N revolutions (like finishing a knitting row). This gives eyes-free progress and rhythm in one channel.
- **Button sequence:** give each step its own subtle haptic signature, varying left/right motor or intensity, so the player feels where they are in the motif. A distinct "row complete" pulse closes the cycle. A wrong button should get *no* buzz (no failure feedback): the sequence just waits.
- **Adaptive-trigger ratchet (PS5):** a light resistance point that clicks and releases on each pull gives a very physical "stitch" sensation. Keep resistance low for 3-hour comfort, because NBA 2K21-style rising resistance would add load.
- Keep haptic intensity low and short. Constant strong rumble over 3 hours is likely fatiguing or annoying and drains controller battery (unverified; see gaps).
- Since sound is off, the haptic channel also has to carry the optional rhythm pulse (Q2). Keep the metronome pulse clearly weaker than the confirmation ticks.

### Gaps
- No Switch HD Rumble documentation or study was fetched.
- No study on vibrotactile habituation or annoyance over multi-hour sessions, and no data on how haptics affect battery life, was found.
- No published DualSense SDK parameters (they're under NDA). Only press descriptions are available.

## 5. Anti-macro, anti-turbo, and idle detection

### Takeaway
I found no documented, official anti-macro design for Bongo Cat. Its drops are time- and input-driven and widely botted. Pokémon GO's egg distance stops counting above about 10.5 km/h (unofficial, community-measured). That is a useful precedent for *capping the credited rate* so automation or extreme speed gains nothing.

### Cited Findings
- Bongo Cat (Steam) lists drop rates: common 90%, uncommon 9.5%, rare 0.49%, epic 0.01%, legendary 1 in 500,000, "subject to change" [snippet] — [Steam store page](https://store.steampowered.com/app/3419430/Bongo_Cat/)
- Players openly seek autoclickers for Bongo Cat achievements [snippet] — [Steam Community thread](https://steamcommunity.com/app/3419430/discussions/0/597399505221993799). PC Gamer reports bot-heavy use, says this can apparently trigger the game's anti-cheat and flag accounts, and frames the game as near the top of Steam's player counts. This is single-source and unconfirmed [snippet] — [PC Gamer](https://www.pcgamer.com/uk/games/steams-second-most-played-game-right-now-is-reportedly-a-bot-filled-marketplace-that-can-get-you-banned/); [GamePressure: bot farms farming hats](https://www.gamepressure.com/newsroom/bongo-cat-now-has-more-players-than-banana-clicker-but-the-realit/z97d86)
- A separate "Auto Clicker" app is sold on Steam, which shows how easy press-counting automation is [snippet] — [Steam: Auto Clicker](https://store.steampowered.com/app/2888120/Auto_Clicker)
- Pokémon GO egg and buddy distance is widely reported to stop counting above about 10.5 km/h (6.5 mph). Niantic has never officially confirmed this, and no warning is shown. One source contradicts it with "10.5 mph," which appears to be an error [snippet] — [Pokémon GO Hub: Egg Hatching](https://pokemongohub.net/post/wiki/egg-hatching/); [Gosunoob table](https://www.gosunoob.com/?p=70811); contradicted by [cyberpost](https://cyberpost.co/?p=50535)

### Inferences
- **Count "active minutes," not presses or rotations.** Credit progress in time slices (e.g., a 10-s window counts as "active" if it contains plausible human input), with a per-window cap. Faster input then earns nothing extra, which also solves the injury-from-speed problem in Q3. The Pokémon GO speed cap is the analogue.
- **Cheap human-plausibility signals** that don't create failure states:
  - Turbo or macro input has unnaturally constant inter-press intervals. Human timing jitters, so near-zero variance over long runs can be flagged.
  - A stick spun by a mechanical rig traces a perfect constant-radius, constant-angular-velocity circle. Human rotation wobbles in radius and speed.
  - Sustained input with zero gaps for hours is implausible.
  - Respond by quietly not crediting the input, never with an error, matching Pokémon GO's silent non-counting.
- **Idle detection:** no input for roughly 30–60 s, or a paused video player on the same device, pauses crediting. Optionally the controller stays still (no gyro micro-motion), which suggests it has been set down. Because the game is free of failure, idle just means "stitching paused."
- If the economy has no tradeable or competitive rewards, the incentive to cheat drops sharply. Bongo Cat's botting is driven by tradeable Steam items.

### Gaps
- No official Bongo Cat statement on how it counts input or detects automation was found.
- No published academic method for turbo/macro detection from gamepad input timing was found within budget.

## 6. iPad/touch alternative (circular gestures, click-wheel style)

### Takeaway
The iPod click wheel and the research earPod technique show that circular touch gestures with a tick at each boundary support eyes-free input. earPod overtook a visual menu technique within 30 minutes of practice. On iPad the haptic tick is unavailable (iPads lack a Taptic Engine; see gaps), so a touch version loses the key eyes-free confirmation unless a paired controller or phone supplies vibration.

### Cited Findings
- earPod (Zhao et al., CHI 2007, Toronto): an eyes-free circular touch menu that reinforces each boundary crossing with a click sound. It matched the iPod-style visual menu in accuracy on reasonably sized static menus, and though initially slower, it "outperforms the visual technique within 30 minutes of practice" [snippet] — [Zhao et al. PDF](https://www.dgp.toronto.edu/~sszhao/paper/paper301-zhao.pdf)
- The iPod is cited as a commercial example: it generates a click when the finger moves around the touchpad's circumference, separating items or units (Jeon et al., ACM TOCHI 2012 / Spindex work) [snippet] — [Spindex slides](https://www.slideshare.net/slideshow/a14-jeon/14609306)
- Eyes-free touchscreen work notes that "the feedback afforded by physical buttons is gone on touchscreen phones." Slide Rule (Kane, Bigham & Wobbrock, ASSETS 2008) introduced eyes-free multi-touch techniques as an alternative to hardware buttons [snippet] — [Slide Rule PDF](https://faculty.washington.edu/wobbrock/pubs/assets-08.pdf); [No-Look Notes](https://sites.cc.gatech.edu/fac/keith/pubs/perv2010-nolooknotes.pdf)

### Inferences
- **Touch design:** let the player draw circles *anywhere* on the screen, with no fixed target position. Credit accumulated angle around the gesture's own running centroid, so drift doesn't matter. A row of 3–5 large anywhere-taps or swipe directions can stand in for the button sequence. Use relative, position-free gestures, because absolute positions require looking.
- On iPhone, use per-angle haptic ticks (UIImpactFeedbackGenerator-style). On iPad, which has no haptics (unverified), consider letting a paired phone or controller provide vibration, or accept visual-peripheral feedback only. Sound is off, so the earPod click can't be used.
- PC: mouse circles (or wheel scrolling as a "ratchet," since mouse wheels have physical detents) plus a fixed key sequence on the home row. Note that "WASD wrist" is listed among gamer's-thumb nicknames ([AAOS](https://www.aaos.org/aaos-home/newsroom/press-releases/4-pro-tips-to-help-your-child-defeat-gamers-thumb/)).
- Touch fatigue: the smartphone gaming study (discomfort by 30 min) and the tablet-reach study suggest keeping touch gestures small and near the resting thumb position, and alternating hands.

### Gaps
- Whether current iPads have any haptic engine was not verified this session (my belief is they do not, apart from Apple Pencil Pro haptics, but this is unsourced).
- No study on long-duration (hours) circular touch gesturing was found.
