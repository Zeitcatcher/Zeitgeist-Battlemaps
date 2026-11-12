# Changelog

Notable changes, newest first. Every version is also on the [Releases page](https://github.com/Zeitcatcher/Zeitgeist-Battlemaps/releases); to update inside Foundry, press Update on the module.

## 1.8.4 — rock walls and wall corners in the Kragmir deep mines

Fixed

- **Глубинные шахты: станция**, **Глубинные шахты: форт** and **Глубинные шахты: контора**: walls along the rock used to sit on its drawn edge, so a token stopped short of the stone or stood on it. They now run a little inside the rock, and the rock's edge is drawn ragged instead of ruler-straight. Boulders and stalagmites in the stone have walls of their own.
- The same three maps: where a wall meets a door or window, the corner is now drawn clean, without a step or a cross.

Walls changed on these three maps, so delete their scenes and import them again from the compendium. The other maps haven't changed.

## 1.8.3 — a wall seam in the Kragmir fort's cellar

Fixed

- **Глубинные шахты: форт**: in the cellar, where the cistern passage meets the turned house beside it, the passage's walls ran a little past the house's door posts and over its wall, so both corners showed a seam with an outlined end. Each is now one clean corner.

Only the cellar image changed. Walls, doors and lights are as before, so there is nothing to import again. The other maps haven't changed.

## 1.8.2 — wall corners on the Kragmir street and the mines station

Fixed

- **Крагмир: улица рабочего квартала**: the houses here stand turned a little off the grid, and wherever their walls met, an unturned post was drawn, so each corner showed a small cross. On all three levels the corners are now one wall turning, and at a T or a crossing the wall runs through. Two cellar corners by the tunnel from the pawnshop are fixed as well, and the sewer's corners are drawn the same way.
- **Глубинные шахты: станция**: on the deck, the open east end of the wardens' post's south wall had the same small cross. It is now a plain wall end.

Only the map images changed. Walls, doors and lights are as before, so there is nothing to import again. The other maps haven't changed.

## 1.8.1 — port warehouse fixes

Fixed

- **Заброшенный склад в порту**: the walls of the stores round the warehouse crossed at the corners. Each corner is now one wall turning.
- **Заброшенный склад в порту**: on every double door (the hall's two and the five stores'), the second leaf was drawn the wrong way round, its handle on the other face. Both leaves now mirror each other and the handles meet in the middle. Import the scene again from the compendium to get the fixed doors.

The other maps haven't changed.

## 1.8.0 — Kragmir port warehouse

New map

- **Заброшенный склад в порту** (Kragmir, an abandoned warehouse in the port), 52 × 60 squares, three levels, lit look. One long hall of crates and barrels with a double door at each end and a broken overhead crane, on the second line from the water behind a row of stores, the quay and the pier.
- Beams 15 feet up are a level of their own, reached by two ladders or over the crates. A token that steps off a beam falls to the floor.
- The harbour water moves, flowing west.
- No ambient sound on this map.

The other maps haven't changed. Import the new scene from the compendium.

## 1.7.0 — Kragmir mine office

New map

- **Глубинные шахты: контора** (Kragmir deep mines, the mine office), 80 × 54 squares, five levels, lit look. An office quarter you can walk into: the office around its courtyard, the assay house, the weigh house, the winding house, a guard post and the overseers' homes.
- A working rope incline 35 feet down the cliff: a button at either end calls the cart, and tokens ride in it.
- Smoke from six chimneys, which fades with each house's roof.
- Ambient sound: the winding gear and the assay furnace. A crowd stays off until the GM turns it on.

Module

- A new moving part, the rope incline, listed in **Механизмы** like the others.
- Smoke can fade house by house. A map has to ask for this; no other map does.

The other maps haven't changed. Import the new scene from the compendium.

## 1.6.0 — Kragmir deep mines fort

New map

- **Глубинные шахты: форт** (Kragmir deep mines, the fort), 80 × 109 squares, nine levels, lit look. An outer wall with a gatehouse, an inner wall with a twin-towered gate and a portcullis, wall walks between the towers, a keep, barracks, workshops and cellars. A token that steps off a wall or a ledge falls to the level below.
- Ambient sound: cave air, dripping water, fires, the forge and the anvil. The crowds stay off until the GM turns them on.

Module

- Two new macros: **Рассвет** and **Закат** set early morning and evening with a warm tint, which **День** and **Ночь** clear.
- A pressure plate can carry a trap: the GM gets a whispered card with its rolls, and the players hear it go off. The card's rolls are written for PF2e; other systems show them as raw text. Plates tell the GM when they refuse a token.
- A token standing on the top step of a turned stair no longer falls off the ledge beside it.
- The **Звуки** panel can keep a sound off until the GM turns it on.

The other maps haven't changed. Import the new fort scene from the compendium.

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

- Kragmir, a working-quarter street: 81 × 50 squares, twelve furnished two-storey houses, a market square, back lanes and yards, and a sewer under the street with ladder hatches and a hidden cellar entrance.

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
