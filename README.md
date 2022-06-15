# Scaleable Multiplayer Games with OpenShift
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

[Design Document](https://docs.google.com/document/d/1UFdZLXFNJEXsKti0vM-CDGuFxrR4l7G_yddqmNFJjb8)

## Thoughts / Notes (2020-09-09)
* RTS potentially 
* precalculate graphical/physics in cloud and send to client
* "How could we have a game on OpenShift with millions of simultaneous players?"
* how do we deal with state distribution at massive scale?
* short term state vs persistent state?

## Thematic Game Element Thoughts
* resource management
* control one or more units
* * units can change over time ("levels")
* * units can have inventory
* * units can have some stats
* * are units persistent when players are not present?
* interact with other players
* what other forms of data would persist? (win/loss, etc)
* some kind of events
* * interactions between two or more players
* * how do these impact the universe?

## Committed Elements
* space theme
* 2D
* "circle of death" fight to the center
* map scales out with number of players
* * rings / sectors
* * can move in but not out (unless you die)
* some concept of cash 
* player has a ship that they can modify
* ship has a fixed number of slots for "loot"/modifications
* modifications (items) have rarity and specs
* chat system
* leaderboards
* "real time"
* when players leave a sector that sector can disappear (too few people)
* browser-based "client" minimum experience
* gravitational trope to determine where players can spawn

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


