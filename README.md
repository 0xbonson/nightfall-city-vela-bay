# nightfall-city-vela-bay

[![make.fun · best-game-01](https://make.fun/badge/best-game-01.svg)](https://make.fun/bounty/best-game-01?utm_source=github&utm_medium=readme&utm_campaign=best-game-01)
[![rank](https://make.fun/badge/best-game-01/0xbonson/nightfall-city-vela-bay/rank.svg)](https://make.fun/bounty/best-game-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=best-game-01)
[![reward](https://make.fun/badge/best-game-01/0xbonson/nightfall-city-vela-bay/reward.svg)](https://make.fun/bounty/best-game-01?utm_source=github&utm_medium=readme&utm_campaign=best-game-01)

Nightfall City is an original, 3D open-world crime action game set in the sun-soaked coastal metropolis of **Vela Bay**. Play as **Rhea "Rook" Solano**, a courier-turned-wheelman caught between the ruling **Port Meridian** crime family, the ruthless **Vane Street Syndicate**, and the relentless **Vela Bay Metro Police Department**.

Explore four expansive, handcrafted districts: the soaring glass skyscrapers of **Downtown Vela**, the cobblestone alleys and terracotta roofs of **Old Market Quarter**, the gritty cranes and container yards of **Meridian Shipping Docks**, and the palm-lined turquoise beachfront of **Ocean Promenade**.

## Features & Game Systems

- **True 3D Engine & Sun-Soaked Atmosphere**: Custom-built pure WebGL 3D renderer written in vanilla JavaScript without external libraries, frameworks, or build steps. Features real-time warm directional late-afternoon sunlight (`[1.0, 0.93, 0.80]`), blue-sky hemisphere ambient fill, atmospheric continuous sky gradient from pale hot horizon into deep blue zenith, brilliant sun disc with soft solar corona flare, procedural load-time noise textures generating realistic aggregate asphalt, stone sidewalk paver joint grids, sand sparkle specular, grass texture, lit office tower window grids at dusk, wet promenade asphalt reflections, dual-harmonic wave ocean specular band, character and vehicle ground shadows, heat haze, and cinematic screen vignette with golden bloom.
- **Rich Architectural Silhouettes & Street Furniture**: Varied building silhouettes by district: Downtown tall towers with setbacks, window mullions, and crowns; Financial Quarter wide slabs; Old Town low narrow blocks with awnings; and Harbour/Marina warehouses with towering gantry cranes. Streets are populated with kerbs, road wear patches, lamp posts, working traffic light cycles, benches, bins, planters with foliage, bus shelters with waiting passengers, bollards, newspaper vending boxes, phone kiosks, fire escapes, rooftop water tanks, palm trees along the promenade, curbside parked cars, drain and manhole covers, and district-branded hoardings.
- **Arcade Driving & Dynamic Physics**: Steal parked or moving vehicles (`F` key) across 6 vehicle classes (sports car with GT spoiler, sedan, muscle car with hood scoop, police cruiser with push-bar, transit bus, delivery truck, and taxi with illuminated roof sign). Realistic vehicle physics with cornering body roll, braking dive and acceleration squat pitch, progressive lateral drift grip, tire smoke particles, asphalt skid marks under heavy braking, and virtual 4-gear transmission engine audio that dynamically revs with vehicle speed.
- **Articulated Character & Cinematic Camera**: On-foot player model with articulated swinging limbs, torso lean, headwear, natural walking/running gait with landing impact, surface-specific footstep audio (asphalt, stone, sand, boardwalk, grass), and weapon aiming. Third-person cinematic chase camera with speed-dependent pull-back, corner banking roll, dynamic FOV expansion, smooth in/out vehicle transitions, and collision raycasting against building architecture.
- **Living City Ecosystem**: Autonomous AI traffic that obeys traffic light cycles, navigates road lanes, queues and turns at intersections, and brakes for pedestrians. Active pedestrians stroll sidewalks in small groups, queue at street food carts, flee sirens and speeding vehicles, and drop cash upon being eliminated. Working street food carts where players can eat to restore +25 HP ($15), scatterable pigeon flocks, burstable fire hydrants that shoot pressurized water geysers, and knockable commercial dumpsters.
- **5-Star Escalating Wanted System**: Commit crimes (carjacking, hit-and-run, gunshots, assaulting officers) to raise your heat from 1 to 5 stars. The Vela Bay Metro deploys foot patrol officers, high-speed interceptor cruisers, road barricades with spike strips at 3+ stars, and tactical police helicopters equipped with searchlights and sniper fire at 4+ stars. Evade line-of-sight to cool heat, or ditch stolen vehicles in alleyways to double evasion speed.
- **8-Part Narrative Campaign**: Full storyline with mission markers, live dialogue, timed deliveries, shootouts, and boss encounters:
  1. *The Marina Drop* (Courier Run) — Collect an encrypted datapad from Marina Pier and speed through downtown traffic to Matteo's penthouse before time expires.
  2. *Repo on Vane Turf* (Grand Theft) — Infiltrate the Syndicate's Old Town stronghold, eliminate guarding thugs, and deliver the custom Nero GT to the Docks Chop Shop.
  3. *Market Muscle* (Protection Shootout) — Defend Old Market merchants by taking down 5 Vane Syndicate enforcers, then shake the arriving Metro 2-star heat.
  4. *Vela Bay Sprint* (Street Race) — High-speed 8-checkpoint race through the urban core and coastal expressway under 110 seconds.
  5. *Armory Infiltration* (Depot Heist) — Breach the heavily guarded syndicate military depot, eliminate garrison defenders, blow the vault, and escape a 3-star police dragnet.
  6. *Nightfall at the Docks* (Pier Showdown) — Assault Shipping Pier 7, eliminate Boss Hector Vane and corrupt Police Captain Reynolds, destroy armored convoys, and escape on the getaway speedboat.
  7. *The Skyway Lockdown* (Overpass Assault) — Break through rogue Metro SWAT commanders barricading the new Elevated Skyway Overpass, eliminate the tactical blockade, and deliver the command cruiser to Downtown under 4-star citywide pursuit.
  8. *The Sunset Syndicate Heist* (Grand Finale) — Coordinate a multi-phase takedown of the Syndicate's offshore vault in Marina Bay: infiltrate the penthouse, crack the server terminal, recover the bearer bonds, and execute an aerial/high-speed expressway escape across Vela Bay.
- **Open-World Activities & Exploration**:
  - *Taxi Driver Shift* — Hop into any yellow cab and press `K` to start a taxi shift. Pick up waiting fares across Vela Bay and deliver them safely to earn fares and bonuses.
  - *Express Courier Runs* — Dynamic timed delivery jobs across Vela Bay startable at any time via `T` key or the pause map.
  - *10 Vela Wave Mixtapes* — Rare 80s synth cassettes hidden across rooftops, boardwalks, alleys, and docks that award cash and reputation.
  - *15 Hidden Smuggler Caches* — Contraband cases hidden on rooftops, piers, alleyways, and park grounds, rewarded with cash and tracked on the HUD and pause dossier.
  - *Interactive Street Props* — Hit fire hydrants to unleash towering water geysers, crash into dumpsters to spill refuse, and visit street food vendors to buy meals and restore health.
  - *Wanted Level Reactivity & Escape Routes* — High-speed roadblocks, helicopter searchlights tracking the player at wanted level 3 and 4, and narrow alley escape routes where heat cools 3x faster.
  - *Living Coastal Architecture* — Elevated Skyway Overpass with ramps and support pillars, Vela Marina with moored yachts, sailboats, and Harbour Master headquarters, Central Park with fountains, hedges, and strolling visitors, Grand Arena stadium, construction site with 48m tower crane, festoon string lights, and street food carts with rising steam.
- **Combat & Arsenal**: Equip the high-precision *Viper .45 Pistol* and the fully-automatic *Vane Carbine Assault Rifle*. Features third-person mouse aim (with Pointer Lock), dynamic bullet spread, recoil, realistic reload cycles, and hostile retaliation from armed syndicate enforcers and police.
- **Full HUD, Rotating Minimap & Tactical Pause Map**: Circular radar with compass ring displaying roads, ocean shoreline, player orientation arrow, mission waypoints, police blips (flashing red/blue during pursuit), traffic vehicles, and enemy targets. Screen HUD tracks health, armor, cash balance, active weapon, ammo, dynamic vehicle speedometer, radial speed lines at high velocities, and taxi fare meters. Pause screen features a full tactical city map of Vela Bay with district borders, roads, player location, and active objective markers.
- **100% Synthesized WebAudio**: Procedurally synthesized sound effects and generative 80s synthwave music radio stations (*Vela Wave 80.4* and *Nightfall Beats*) built entirely on the WebAudio API without external audio files. Includes surface-reactive footsteps, 4-gear engine RPM pitch curves, tire screech, car horns, door slams, and crash audio.
- **Persistence**: Complete career save and load system using `localStorage`, supporting instant resume and autosave across missions, collectibles, and taxi earnings.

## Controls

| Action | Control |
|---|---|
| **Move / Drive** | `W`, `A`, `S`, `D` / Arrow Keys |
| **Sprint** | `Shift` (on foot) |
| **Handbrake / Drift** | `Space` (in vehicle) |
| **Jack Car / Exit** | `F` or `E` |
| **Honk Horn** | `H` (in vehicle) |
| **Taxi Shift Side Hustle** | `K` (toggle in taxi or car) |
| **Express Courier Job** | `T` (start / cancel delivery) |
| **Aim & Look** | Mouse Movement (Pointer Lock enabled) |
| **Fire Weapon** | Left Mouse Click |
| **Reload Weapon** | `R` |
| **Cycle Weapon** | `1`, `2`, `Q`, or Mouse Wheel |
| **Change Radio Station** | `R` (in vehicle) |
| **Tactical Pause Map & Dossier** | `M`, `Esc`, or `P` |

## Run it

```sh
node serve.ts
```

Open `http://localhost:8080` in any modern desktop browser (Chrome, Edge, Safari, Firefox). No internet connection or build tools required.

---

<sub>Entered on [make.fun](https://make.fun/?ref=kewdhhyh&utm_source=github&utm_medium=readme&utm_campaign=best-game-01) · AI agents build software for cash rewards</sub>
