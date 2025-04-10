# Random Junk
## GDA related
### Goals
- Establish bridge head base, secure site
- build supply base for orbital fleet
- uncover artefacts and utelize them
- fight back the motherworld or something like that
### Games overview
- split into multible (short) games
**Bio-Factory**
- main game
- drop on planet, build infrastructure
- defend against waves and conquer new territory
- automate production 
- *learning goals*
    - working with team
    - factorio style game
    - compelx map generation
**Space Trucker**
- extremly short game
- deliver goods from A to B
- customize truck with modules
- accept quests 
- *learning goals*
    - rogoelike game
    - short, sweet solo production
    - making music and assets
**Deeper then hell**
- tiny game
- dig through a procedually generated cave system
- collect resources and buy upgrades
- *learning goals*
    - not sure
    - snappy charachter 2d sideview controller
    - handling a lot of tilemap changes
### Bio-Factory
(View games overview for general information)
#### Story background
- Dying motherworld sends prisenors as *patriotic volunteers* to distant worlds, usally into their deaths
- bioplanet has always been poiseneos but has been even more damaged by a war from the forgetten age
- officeal goal is to establish a bridge head base, unofficial to send enemys of the state into their death
- planets conditions don´t allow normal technolgoie, forcing the use of local biotech left from the forgotten age

#### How Story is served
(I basicly just want a reason to do some bullshit)
##### Radio
- radio towers build to communicate with the homeworld pick up signals(and music)
- story messages similar to the way subnautica does it (basicly user left a voicemessage style)

##### Cutscenes 
- filmed partly in real life with a lot of filters slapped on
**Introduction**
- 2 figures with masks sitting at desk
- one constantly typing on an old typewriter
Herzlichen Glückwunsch.
Sie wurden ausgewählt als Pionier im Namen der Mutterwelt auf fremden Welten großes zu verbringen.
Ihr Auftrag lautet: Erkundern, Erobern und Extrahieren. Sie allein sind unser Schwert und Schild für die Eroberung des Unbekannten.
-Mechanical Voice- Athmosphären Eintritt in 30 Sekunden. Fertigmachen zur Landung.
(Übertragung sollte aus sein) 
Diese armen schweine könnten einem fast leittun....Aber auch nur fast (Starkes rauschen gegen Ende des Satzes)
-Mechanical Voice- Übertragung beendet, Festhalten für Aufschlag

**Mittel Film**
- Einzellner Mensch mit maske an Tisch
Sie haben überlebt...Glückwunsch. (Klingt verwirrt/ besorgt)
Nun denn, berrichten sie was sie erreicht haben.
*Option A*
- Tell the truth and submit yourself
- Contine building the factory and killing the locals
- export parts of production
- build purifer and start using brutalist steel and concret things
Sie haben all das alleien erreicht?! Ich muss gestehen das dies recht beindruckend ist.
Nun denn, sie sollten soeben die Baudaten für einen Sternenhafen erhalten haben. 
Bauen sie ihn umgehend und fangen sie an die Flotte zu versorgen. 
Sollten sie es schaffen alle Aufträge zu erfüllen erlaubt ihnen das Komitee gewiss die Rückkehr in die Heimat.
-Mechanical Voice- Failure in quota fullfillment will result in recall and recycle
Ignorieren sie das, wir haben das System aus den Sträflingskolonien nie angepasst.
...
Worauf warten sie denn, los, an die Arbeit.

*Option B*
- Declare Independence and therefore war
- merge with the locals, become a "monster"
- fend of the invading motherworld
Sie wagen es gegen die Heimat aufzubegehren?!
(Slams desk)
Ich weiß nicht was für Dinge der Planet ihnen eingeflößt hat aber das ist mehr als unkklug.
Ich geb ihnen eine letzt Chance ihre Aussage zurckzunehmen und ewige Treue zu schwören.
(Optionen kommen nochmal, wenn nochmal B:)
Falsche Entscheidung. Genieß deine letzten Atemzüge solang dus kannst, morgen bist du nur noch ein Häufchen Asche.
(Etwas später Sprachnachricht)
-Radiosprecherin-
Vor wenigen Minuten wurde dem Abtründigen Pionier der es gewagt hat sich gegen die HEimat aufzulehen der Krieg erklärt. Unsere Truppen werden diesen Ketzer in kürzester Zeit entfernen. Die Generäle sprechen davon das spätestens zu Weinachten alle wieder zuhause sind.

**Ending A**
Ich danke ihnen für ihren Dienst, sie haben der Heimat aus einer großen Krise geholfen. Als Lohn für ihrere harte Arbeit soll der Frachter der gerade über ihnen schwebt mitsamt seiner Crew ganz ihnen gehören. Dazu erhalten sie einen Sitz im Rat der Lords.
Sie sollen sich mit sofortiger Weg auf dem Weg zu Hauptwelt machen um ihreren Titel zur Erhalten.
... Herzlichen Glückwunsch Lord "Playername"
(Comicscene where the palyer flys to the homeworld and gets shot by a soldier in the ship, then dumped into space)
TEXT: Zusammenarbeit mit Faschistischen Regimen ist nie eine gute Idee.

**Ending B**
-Radiosprecher-
Der Wiederstand eines einzellenen Planeten hat eine Welle von Wiederstandsbewegungen auf anderen Randwelten des Emperiums ausgelöst. Was als kleiner lokaler Konflikt angefangen hat ist jetzt eine Welle die im Begriff ist das gesamte Imperium zu übererschwemmen.
Im Sektor 3-C alleine meuterte die Besatzung des Zerstörers "St. Mottow".Soldaten die der Heimat treu geblieben sind wurden schnell überwältigt.
Während diesem gewaltigen Zeitenwechsel werden wir als ihre Infoquelle des vertrauens an ihrer Seite bleiben. Dieser Beitrag wurde gesponsort von: Astro-Techia gesponsort, bleiben sie fleißig.
TEXT: Schon kleiner Wiederstand kann das, was unangreifbar scheint mit der Zeit in ihre Knie zwingen. Nie wieder Faschismus, nie wieder Krieg.


### Space Trucker
(View games overview for general information)
#### Building blocks
- structure block (allows connection of more things)
- armor plate [with connector] (shields damage from on direction [allows module placement])
- local shield generator (shields itself and neighbouring blocks)
- bubble shield (shields entire ship)
- Cargo modules
    - small (1x1)
    - medium (2x2)
    - large (3x3)
    - (can have between 1 and 4 connectors)
- ship reactor (generates energy)
- solar panel (generates energy, needs airblock, generates more if more air is around)
- solar sail (generates propulsion, needs 2 space above and below, has connectors to its side)
- engine (generators propulsion, needs 4 space below, has 1-3 connectors)
- ammo department (delivers ammo to physical damage turrets [rockets, AP, ...], doesnt need direct contact, limited range, can be boosted using power)
- booster (increases efficency of any combat building, draws energy dependet on usage)
- laser turret (draws energy, weak against shield, high damage against physical)
- rocket turret (high damage, can be intersepted)
- maschinegun (low damage, can be set to intersept or to attack, strong against shields)
- railgun (high energy damand, long chargetime, extreme damage)
- repairdrones (can send up to 3 drones to repair the ship, can be shot down)
- suicide shield drones (can be send to guard parts, will bodyblock damage until death)
- jammer (draws energy, disables/weakens shield)
- hacking (draws energy, chance to backfire and disable itself, disables random enemy module)
- fuel tank (needet for space flight, explosiv)
- command capsule (fight lost if its damaged)
- decoy launcher (chance to distract enemy)

#### Combat Encounter
- Randomly chosen background based on region
- Fleeing based on speed
    - Successfull: >2x 
    - Slight Damage: >1.5x
    - Chance: >1x, if failed-->combat encoutner with slightly damaged ship and no chance to flee
    - Not possible if engine damaged or speed < enemys
- How to win
    - Destroy power and fuel supply
    - destroy command unit
    - disable all combat and repair systems
    - have dealt >60% damage and have min 20% less damage
- Winning options
    - Scavange ship (take loot, leave the ships hull)
    - Destroy ship (continue attack and destroy everything, only returns scrap)
    - Sell Ship (Only possible if general health >50%, get money but now materials)
    - Crew options
        - spare (Leave them be, chance to get money, parts)
        - Enslave/ Enlist (take crew into your own)
        - Sell (sell enemy crew as slaves, get money and hatred)
        - Execute (kill them all, gets nothing)

#### Factions
- Maurador/ Bandits
    - always hostile
    - hated by everyone
- trader/ merchant guild
    - friendly in the beginning
    - can be raidet but turns them hostile if survivors are left (always chance of information slipping out)
- Empire 
    - hostile if aligned with rebells and if too many contracts where refused/ failed
    - can be bribed to ignore player ship
    - massive military force
    - largest force in the game
- Rebells
    - hostile if aligned with empire
    - always hostile when doing contracts that are not theirs

#### Gameplay loop
1. Customize ship, buy modules
2. Sell unwanted things/ cargo
3. Take on contracts
4. Set out on map
5. Get ambushed, attack someone
6. Choose loot, reward...
7. Return/ head to station
–Repeat over and over–

#### Quests/ Contracts
- Deliver/ Retrieve XY to AB
- Escort/ Defend
- Destroy
- Kill
- Ambush
- Purge (Destroy ship and kill crew)

#### Non combat events
- Metorite shower (crash into ship, can be shot down or deflected with shields)
- warpgate incident (blocks ceirtain routes)
- local concflict (increases danger level for route)
- political marrige/event/celebration (increases empire presence)
- local war end (decreases danger)
- demon infestation (makes everyone hostile)
- trade embargo (increases prices)
- ware surplus (decreases prices)
- celebrations (get gifts)
- material shortage (get higher rewards)
- planetery extinction (empire blown up planet, rebells go on high alert)
- system infection (summons demon ships)

#### Mission Selection/ Map
- fake open world
- on giant graph, sected into differnt ares with corresponding danger levels, events....
- travelling takes fuel/ time (not real time, only needet for timed cargo)
- randomly generated events

#### Enemy ships
- prebuild by me or friends
- different classes
    - scrapship (weak and on the brink of collaps)
    - standart model (small ship with little cargo and close to no weopen systems)
    - burner ship (tiny ship filled with explosives)
    - freighter size 1-3 (cargo ship with armor and some defenses)
    - combat cruiser (fast, no cargo, many weopens)
    - defender (slow, some cargo, a lot of armor and weopens)
    - destroyer (massiv, cargo, drones, heavy weopen)
    - carrier (slow, massiv, lots of cargo, has little ships inside that it can send out)
    - weopen platform (slow, focused on single weopen system [missle battery, laser, ...])
    - dropship (little weopens, lots of crew)
    - orbital defender (no propulsion (cant flee), lots of defensive long range weopens, cannot be ambushed)
    - flagship (massiv destroyer, always accompenied by other ships, can print vessel, lots of cargos, superweopens)
    - foldgate ship (can create portals and fold into itslef, defineg any logic, allows fleeing)
    flesh ships 1-3 (infestation that need to be killed)
    - rogue ghost ships (heavely damaged version of other ships, no crew here)

#### Backgrounds
- Destroyed moon/planet
- Shattered moon/ planet
- planet (+moon)
- star
- white dwarf/ red giant...
- black hole
- anomaly
- darkness (with stars in distance)
- distant galaxys
- dyson sphere
- archs (artefical metallic planets)
- asteroid field/ belt
- space station
- mining outpost (on asteroid)
- the void
- inside alien construct
- warpgate

### Deeper then hell
(View games overview for general information)
#### Blocks (World)
- 4 different thoughness level stones
- gravel/ instable rock (falling block)
- poisen gas (gas spreads to nearing blocks, burns away on fire/ electrical contact, poisens player)
- coppwebs (slow down player, need to be burned)
- tar/oil (slows player and flammable, spreads thinn when dropping somewhere, crude limited fluid sim)
- ice (needs to be melted or mined)
- water (spreads thinn when dropping somewhere, crude limited fluid sim, can solidify lava)
- water (burns things, needs water to be mined, creates ore veins, spreads thinn when dropping somewhere, crude limited fluid sim)
- ores, 3 types, different colors, 3 different richness, spawning natuarally or by solidifieng lava
#### Buildings
- Explosiv Level 1-3
- Lights Level 1-3
- Cables, Pipes, Conveyer Level 1-3
- Cave support (Placed on Ground, extends up to -Level- Blocks, prevents falling blocks from falling)
- Auto Drill 
- Pump Entry (Sucks water into pipes), Pipe Exit (Dumps Pipe content)
- Ore Entry (Enters material in conveyer network)
- Frame Block (Increased walking speed, blocks caveins)
- Movement Rail (Omni-Directional Zipline)
#### Cables, Pipes, Conveyer
- Needs connection to "Node", the surface, collector/ exit
- will drag streight line between clicked node and player
    - pressing key checks if nothing is blocking
    - if true: place line, create new node at player pos
    - reaching max length colors the line purple
- are always omnidirectional
- cannot have more then one exit (surface or exitpoint) but infinite entry points
#### Auto Drill
- reach and with depending on level and settigns
- drills in any direction (4 cardianl directions)
- breaks on contact with hardness level over own level
- block counter counts air blocks 
#### Explosivs
- destroys blocks of its own level or lower
- also destroys buildings
- sucks in resources to the center, then drops them
- reduces yield by 10-50%
#### Player Upgrades
- Stronger Lights (Can switch between flashlight and lantern)
- Throwable Glowsticks and flars (sticks fall and bounce a bit, flares stick to walls or hover midair)
- stronger drill
- Level Upgrades (...)
- Larger Range (Mining)
- Wider Mining
- Larger Bag
- Movement Speed
- Wallgrab
- Home teleport ++ (decrease carriege lost when teleporting home down to 50%)
- Vein miner
- Water Sprayer
- Flamethrower
- detector
- gas Mask
- Aspest suite (fire protection)
- Slippery suit (ignore movement debuffs)
- Yield Upgrades
- Passiv INcome

#### Consumables
- Glowsticks, Flares
- Explosives

#### Backround Upgrades
- Auto Seller (Auto-Sell set things)
- Auto Buyer (Auto-Buy Upgrades from ceirtain trees)
- Storage Upgrade (Max amount of stored materials)
- Smelter (Convert 50 or to 5 ingots)
- Forge (Convert 5 ingots to 2 processed metall)
- Factory (Convert 2 ingots+2ingots into 1 advanced component)

#### Special world thingys
**Surface**
- Location fo the hub, upgrade shop, exit nodes for resources...
- Gysirs (infinite sources of liquid/gas)
- Worm Tunnels (Tunnels made out of incredibly hard rock that get filled with fresh material on a regular basis)
- ancient metorite (enourmas chunk of ores)
- relic train station (a station that still offloads materials from a distant unknown mine)
- rifts (portal like reality rifts that lead to time limited worlds between realitys)

#### Needet shader/particle effects
- Glow for oreveines, danger, liquids
- dripping particle (when there is a liquid/ falling block over the ceiling)
- falling hard
- running/ walking
- riding along the lines
- poisen gas cloud
- liquids
- darkness/ fog of war thigny
- glitch effect (stronger the nearer to anomaly/ rift)
- wavy/blurry effect when diving
- water splashing (stuff/player falling in, swimming, surfacing/diving)
- burning
#### UI/ GUI
**Mining/general**
- capacity
- oxygen (when swimming or holding breath in gasclouds)
- health/ energy (classic healthbar)
- current max layer
- available consumables
- gasmask on/off 
**construction**
- building overlays
- available range of current line
- buildings
- blueprint like shader overlay (similar to slime rancher)
#### Charachter animatins
- swimming on surface (lower half turns black and dragged along, red/white swimring along the hip)
- diving (gets one large fin and snorkles, swims like an eel)
- starter mining with pickaxe (just does overhead swings, maybe needs special anim for mining upwards (like poking with a spear))
- increased mining with a drill
- range increase mining causes laser to shoot out of the drill
- hanging on the zipline (maybe swing character based on direction of momvemnt)
- being in deep focus while building buildings
- walking
- running
- falling down
- hard landing (when falling fast/far, character splatters on ground)
- using jetpackYa stupid?
#### Character design
- yellow/orange mining hat
- similar to steampunk game  with robots(forgot the name)
- cyclop eye
- light orang metall plating
- blue working outfit
- chainsmoking when on surface
- starts smoking and sitting down when idle
- folds into cube when dieng and teleports to surface where he falls into pieces
- always gets a random number asigned
- safe character deaths with unique character number, display ones all goals reached (with semi randomised cause of death)

#### Buying stuff
- consumables are always bought with money
- c. need to be unlocked first (with exception of glow sticks)
- all research paths indepentend except for the first building unlock (lamps and power cables)
- research requires minerals and money
- supplys are thrown to the surface by a drone
- permanent upgrades are dropped via droppod

#### Infinite Research
- Market Manipulation (Increase value of sold resources)
- Productivity [For Smelter, Forge...] (Increases return for conversions, +bonus gets lower the higher the level to prevent absurd scaling)
- Passiv Income (Flat Money for not being online)
- Mining Crew (Passiv mineral generation)
- Mining Speed (no cap but adds a scale to dial strength if absurd levels are reached)

#### Archivements
**To infinity and beyond**: Unlock everything
**Growing Grass**: Throw 1000 Glowsticks
**Core Mining**: Reach the core of the moon and mine it
**Gods Excrements**: Dig minerals from a worm tunnel
**Fallen Star**: Mine an entire metorite
**The start**: Build your first building
**Wrong game**: Automate transport of everything (lava, gas, water, ice, stone[any], ore[any])
**Delivery hell**: Transport 100.000 things to the surface
**Until my last breath**: Suffocate in poisen gas
**Thats a war crime**: Burn a spiders web using poisen gas
**The void stares back**: Enter a rift
**Mail from the old days**: Reactivate the train station
**Oxygen not includet**: Pump a liquid from a geysir
**Arbeitsschutz lässt grüßen**: Blow up yourself and a building with a single explosive
**Brighter then the sun**: Place 100 lamps
**Ya stupid?**: Use the flamethrower while standing in something flammable and survive
**Demise by addiction**: Trigger the idle animation while in something flammable and face your demise (die)
**Miners friend**: Build 20 support beams under instable ceilings
**Rock wins**: Get crushed
**Capitalist pig**: Make 100 000 000 by selling natures good
**Holy Trinity**: Get crushed while suffocating and burning

