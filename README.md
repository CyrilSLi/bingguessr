# bingguessr

A GeoGuessr-like game using Bing Streetside imagery

## Controls

- `WASD` to move around
- `-` and `=` to zoom in and out
- `m` to switch between 3D and map view
- `Space` to submit your guess
- `r` to play again
- Click on the map to move to that location
- Map supports zooming, panning, and rotating

## Location generation

Locations are generated using a seed. URLs with the same `seed` query parameter will generate the same location. If no seed is provided, a random one will be generated.

## TODO

- Add settings menu (time limit, movement speed, etc.)
- Add score algorithm
- Add multiplayer rooms and track player scores