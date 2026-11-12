# Draw Your Way Out

**A 3D tactical action game built with Unity and C#, combining card-based programming, custom movement paths, and strategic robot combat.**

Players control programmable robots by assembling sequences of action cards. Each card defines an operation, from drawing movement paths to deploying weapons or repeating actions. Plan a sequence, execute it, and overcome enemy robots and environmental challenges.

**[Play on itch.io](https://itch.io/queue/c/8219093/csc404-fall-2026-collection?game_id=5045184)**

## Gameplay

The core gameplay revolves around constructing action sequences to control a robot in a tactical environment.

Players must carefully plan movements, select weapons, and manage action sequences to eliminate enemies and navigate levels.

### Core Features

- **Card-Based Programming:** Build action sequences using movement, weapon, and logic cards.
- **Custom Path Drawing:** Draw movement trajectories directly onto the game environment, allowing flexible robot navigation.
- **Tactical Combat:** Deploy different weapon types, including lasers, rockets, bombs, traps, and area-of-effect attacks.
- **Enemy AI:** Enemy robots with movement and behavioral logic that create tactical challenges.
- **Action Sequencing:** Combine movement, combat, and repeat operations into programmable action chains.
- **Path Visualization:** Preview robot movement paths to help plan actions before execution.

## Technical Implementation

### Robot Movement System

A custom movement system interprets player-drawn paths and translates them into executable robot movement. The system integrates with card-based commands to support flexible navigation and action sequencing.

### Enemy AI

Enemy robot movement and behavioral systems are integrated with the gameplay environment, providing dynamic combat encounters and tactical challenges.

### Modular Action System

A card-driven gameplay architecture supports multiple categories of operations:

| Card Type | Function |
|---|---|
| Movement | Execute player-defined movement paths |
| Weapon | Activate combat abilities and attacks |
| Logic | Modify action sequences through operations such as repetition |

The system combines these operations into executable sequences, allowing players to construct and experiment with different strategies.

## Tech Stack

- **Engine:** Unity 3D
- **Language:** C#
- **Game Systems:** Enemy AI, Movement Controllers, Card-Based Actions, Combat Mechanics
- **Version Control:** Unity Version Control

## Play the Game

Experience Draw Your Way Out on itch.io:

**[Play Draw Your Way Out](https://itch.io/queue/c/8219093/csc404-fall-2026-collection?game_id=5045184)**
