ALBERT CANAL PORT MODEL FOR 3D PRINTING
BCTN Meerhout quay to Kwaadmechelen lock, scale 1:1600 (true scale, no height exaggeration)

FILES
tile_A1 to tile_A4   north row, west to east (canal and lock)
tile_B1 to tile_B4   south row, west to east (quay, hub, container yard)
cranes_x3            three gantry cranes built from the real crane in the scene (A frame legs, twin girders, machinery house, trolley and cab)
tile_layout.png      where each tile goes
top_view_for_projection_alignment.png   the exact top view of the model

SIZE
Whole model 720 x 404.8 mm. Columns are 124.8, 237.6, 231.2 and 126.4 mm wide. Rows are 202.4 mm deep.
Detail is modelled on a 0.2 mm grid: single containers, crane rails, bollards, hub equipment, roof shapes.
Water sits 2.4 mm above the bottom of the tile. The upper reach is 6.25 mm higher than the lower reach.

PRINT SETTINGS (Bambu Studio, P2S, 0.4 mm nozzle)
Matte white PLA. Layer height 0.12 mm for the lock tiles (A3, A4) and 0.16 mm for the rest.
3 walls, 15% infill, 5 top layers, no supports, no brim.
Cranes: print upright as they open, 0.08 or 0.12 mm layers, tree supports on build plate only, with a brim. They are 18.6 mm tall and the legs are about 1.5 mm thick, so remove supports gently.
Tile A3 has the road bridge printed as a real span over the three lock channels. Leave supports off, the printer bridges it.
Do not rotate or scale the tiles. Print each one flat as it opens.

ASSEMBLY
Glue the tiles to a flat board following tile_layout.png. Each crane has a 0.6 mm key under its feet that drops into the matching slots on the two crane rails, long arm over the water. A drop of glue holds it.

PROJECTION
Render the animation with an orthographic camera looking straight down, covering exactly this rectangle
(scene coordinates of the albert-canal-vr project, X east, Z south, metres):
NW corner  X 640.30  Z -53.85    (5.098091 E, 51.101594 N)
NE corner  X 1756.11 Z 232.64    (5.114021 E, 51.099019 N)
SE corner  X 1595.04 Z 859.97    (5.111722 E, 51.093380 N)
SW corner  X 479.23  Z 573.48    (5.095792 E, 51.095955 N)
Centre     X 1117.67 Z 403.06    Width 1152 m, depth 647.68 m, canal axis horizontal (scene rotated 14.4 degrees).
The battery swapping station is on tile B2: two docking stations with packs on charge, the battery storage row, solar canopy, control building and its own crane.
Trees are single crowns at real height (capped at 10 mm).
Not printed, so they can be projected: vessels, e-barge, tender, battery packs, crane trolleys and the push tow chamber gates.
The push tow chamber is printed at the lower water level.
