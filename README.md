# Space Ring Things - Scaleable Multiplayer Games with OpenShift
Multiplayer games, especially at large scale, have unique considerations for
their design. While traditional monolithic game server design has served the
industry well, it's possible that a microservices-based approach could work
better and be more scaleable, within certain constraints.

Red Hat has a Gaming Community of Practice (COP), and we (the gaming COP) are
going to attempt to design a multiplayer game that uses just such an
approach.

There is an interesting [thesis
paper](https://pdfs.semanticscholar.org/be47/da0d4a057f5e2f9324a476c1417a3fa9ad8c.pdf?_ga=2.232486303.1819868501.1599161898-2045526526.1599161898)
by Mauno Vähä that explores microservices design as it applies to multiplayer
online RPGs. We will use it as a reference for this project.

## Game Overview
**Concept:** Battle Royale-esque “last person standing” space ship battles

**Genre:** Battle Royale, 2D top-down looter shooter

**Elevator Pitch:** In space, if you’re not first, you’re last. But being first
comes with consequences. Vanquish your opponents and pick up components from
the wreckage. Make good choices, because each component you strap on makes you
heavier and pulls you deeper into the gravity well - where everyone else with
more guns and more gear already is.

## Gameplay and Art References
Combat similar to [Star Control: Origins](https://en.wikipedia.org/wiki/Star_Control:_Origins)
Technology and battle tactics inspired by [Firefly's Reavers](https://en.wikipedia.org/wiki/Reaver_(Firefly)
Minimal art style to start inspired by [Radius Raid](https://js13kgames.com/games/radius-raid/index.html)
Also art style inspired by [Warships](https://news.blizzard.com/en-gb/starcraft2/10058311/arcade-highlight-warships)

## Key Game Design Features
* Infinite scale universe grows as more players join the game
* "real time" (not turn-based)
* Long term persistent state
* Click and command rather than twin-stick
* 2D Top Down
* Permadeath - if your ship is destroyed, you start over
* Roguelike - Sectors are procedurally generated
* Actor removal drops "loot" which can be used to modify ship
* Ships get heavier as more mods are added which pulls them towards
  the center of the game universe

## Architectural Design
2022 update - based on team conversation here is the updated draft components architecture:
![](https://github.com/redhat-gamedev/srt-multiplayer-game-design/blob/master/srt-arch-draft2022-02-08.png)

Original design components list is below:
* account service
* * ties an "identity" to a player (game stuff)
* website
* logger service (existing EFK in OpenShift?)
* * at minimum, each service needs to conform to logging standards
* * containerized = stdout/stderr
* chat service
* * text to start
* * voip later?
* leaderboard service
* need some kind of game server
* * ring vs sector on ring?
* * how many players in a sector / ring?
* data service (data grid?)
* "ai service" for fake players / NPC
