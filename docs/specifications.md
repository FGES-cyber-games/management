# Specifications

_This section is related to the management and upcomming tasks/updates of the project._

## V0 - Proof of Concept

This will be the minimum version of the project (as a demo). The goal will be to have a gun that can shoot at the target, and turn of the light.

- the gun can send data to the server
- the target can send data to the server
- A server
- the gun and the target are connected
- the gun can be identified and can send informations to the server

## V1 - Target contest

To improve the concept to a minimum playable version (where two players can actually play against each other), the goal will be to develop a small game based on targets hitting.

Two sets of targets are placed on a wall (one set per player), the number of targets must match. For each target lit up on one player's side, the matching target on the opposing player side is turned of. The number of target lit up and turned off is the same for both players.

When a player hit his target, he turns it off and light up the opposing matching target.

## V3 - Laser game

The goal is to have at least 6 players playing a full scale laser game. They can choose between different game modes, and are connected to a server that controls the rules of the game.

The following game modes will be implemented :

- Classic game (3v3)
- Classic game death match (3v3 with one live per session, for n sessions)
- No team (each player for himself)
- No team death match (sessions and lives included)
- Prey v Predator (every minutes the team who kills and the team who hides switch)