# Albert Canal port model

A 3D printed model of BCTN Meerhout quay, the battery swapping station and Kwaadmechelen lock at 1:1600, with the animation projected onto it from above.

Everything for this project is here.

| | |
| --- | --- |
| Start page | https://alicemitakoff.github.io/albert-canal-port-model/ |
| Projection view | https://alicemitakoff.github.io/albert-canal-port-model/projection/ |

* `projection/` the straight down projection view. It is the same 3D scene as the albert-canal-vr animation, framed exactly to the printed model (1152 m by 647.68 m). By default it draws the 3D illusion for a viewer on the canal side; `?flat2d` gives the plain view from above and `?side=south` moves the viewer. Add `?proj=berth` or `?proj=lock` to loop one story, or `?3d` for the normal 3D view.
* `print/hybrid/` the in-between model (recommended): buildings, lock, bridge, swap station and container stacks printed; vessels, cranes, packs and trees projected.
* `print/stage/` the white stage for the 3D illusion (Le Petit Chef technique): only canal, quay and lock are printed, everything else is projected.
* `print/` the detailed model: the eight tiles and the cranes as 3MF files for Bambu Studio, with print settings in `print/README.txt`.

Orthofoto 2024 and DHM Vlaanderen II © Digitaal Vlaanderen (open data). Map data © OpenStreetMap contributors (ODbL).
