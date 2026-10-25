# Changelog

Notable changes, newest first. Every version is also on the [Releases page](https://github.com/Zeitcatcher/Zeitgeist-Battlemaps/releases); to update inside Foundry, press Update on the module.

## 1.5.0 — ambient sound

Sound on five maps

- Izudin's manor, the lake tower and the ruined tower: birds and wind by day, crickets and an owl at night, over the open ground. The **День** and **Ночь** macros switch between them.
- The lake tower: waves lap along the shore and at the jetty, and water drips in the basement.
- The Kragmir street and the mines station: cave air on every level, and drips by the station's puddles.
- Outdoor sounds carry through walls and floors: indoors and upstairs they come softer and muffled. An open-air room upstairs, such as the lake tower's balcony, hears them clearly.

Module

- A new macro, **Звуки**: the GM's panel for the open scene's sounds. Each sound plays by the time of day, always, or not at all, and every player hears a change at once.
- The sounds are CC0 recordings from Freesound, cut into seamless loops of about 0.4 MB each.

The other maps haven't changed. To get the sounds, delete the five maps from your world and import them again.

## 1.4.0 — Kragmir deep mines station

New map

- **Глубинные шахты: станция** (Kragmir deep mines, the station), 80 × 54 squares, lit look. The station stands on a rock shelf 35 feet above the town's lower street, and both are in one scene. A grand stair and a freight lift go down the cliff. The train stops on a raised platform on stone piers that fades over a token beneath it, and a hoist tower lifts ore carts up to the track. Six buildings you can walk into: the office on two floors, two warehouses, the workers' shed, the hoist tower and the wardens' post on its stone base.
- Rocks, stacks of crates, carts, machines and the platform's piers have object walls along their drawn outline: they stop movement and hide what stands behind them. Rubble and rock heaps are difficult terrain.

Module

- Ledges and raised platforms: a token that steps off the edge drops to the level below, and a chat card shows the falling damage (a damage roll in PF2e).
- Lifts carry tokens between levels. Each stop has a gate that opens where the platform stands and a call square. A player sees the lift's button while their token stands on the platform; the GM sees it for the selected token.
- A client setting, **Map animations**, for animated maps to come. No scene in this release is animated.

The other maps haven't changed. Import the new station scene from the compendium.

## 1.3.0 — swinging doors

All maps

- Doors swing open and shut on their hinges with Foundry's door animation. Each opens into its room: the indoor side, or the larger of two rooms. The map images no longer have doors painted in.

Izudin's manor

- A door in the same place on the ground and upper floors was one door for both, so opening it on one floor opened it on the other. Each floor now has its own.

Kragmir street

- The twelve house stairs no longer have a square of different wood at the top of the wooden upper floors.

Module

- A script for moving map parts: drawbridges, lifts, portcullises and pressure plates. Players get a button on the map when their token stands at a lever or on a lift, and the GM gets the **Механизмы** macro. No scene in this release uses them yet. Button text in English and Russian.

Imported scenes keep their old doors: delete the Zeitgeist Battlemaps scenes from your world and import them again.

## 1.2.0 — turned houses

Kragmir street

- Each house stands turned 0.5 to 1.5 degrees off the grid, its yard with it, each its own way. One-square alleys now run between the houses and at both ends of the street.
- Every wall runs along a grid line and every door spans whole squares, so tokens no longer catch on a door jamb or stand half inside a wall.
- Ground textures blend into each other along their edges and at passage mouths instead of meeting on a straight line. Bare rock is grey everywhere.
- Some rooms lost a square to make room for the alleys. The temple hall was laid out again around its aisle.

All maps

- No table, chair, counter or crate stands inside a wall. Fixed on the Kragmir street (the tavern terrace among others), in the lake tower (two cages and the telescope) and in Izudin's manor (a crate by the back stair).

Imported scenes keep their old walls and lights: delete the Kragmir street, lake tower and Izudin's manor scenes from your world and import them again.

## 1.1.0 — Kragmir street

One new scene, eight in all.

Maps

- Kragmir, a working-quarter street: 81 × 50 squares, twelve furnished two-storey houses, a market square, back lanes and yards, and a sewer under the street with ladder hatches and a secret cellar entrance.

Play

- Every house on the street has its own roof.
- Rock columns block movement and limit sight. Rock outcrops are difficult terrain.
- Crystal lamps and fires burn at any hour, so the street stays lit at night.

Verified on Foundry v14.367.

## 1.0.0 — first public release

First public release. Seven scenes and two macros.

Maps

- Izudin's manor: basement, ground floor, upper floor and a pitched roof as its own Level.
- Lake tower: basement, four floors and a cone roof, in lit and flat looks.
- Ruined tower: an outdoor map with fading tree crowns and difficult terrain, in both looks.
- The Sixth Facet club: one furnished floor with ten lights, in both looks.

Play

- Walls, doors, windows and lights match the painted image.
- Roofs fade while a token is inside.
- Night lights switch on as the scene darkens.
- Macros **День** and **Ночь** set the open scene to daylight or night.

Verified on Foundry v14.367.
