# YAVIR regions

Offline region packs for the YAVIR iPhone app (checkpoint-based walking navigation that works without internet).

Each folder is one region:

- `map.pmtiles` — vector map tiles
- `graph.bin` — walking network
- `pack.sqlite` — addresses, streets, landmarks, search index

`catalog.json` lists the regions and file sizes; the app reads it to show what can be downloaded.
Display names in the catalog are in Russian because the app interface is Russian.

## Data

Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, available under the Open Database License (ODbL).
Tiles are built with the [Protomaps](https://protomaps.com) basemap toolchain.
