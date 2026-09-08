# Kerbal Civilization Project

![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/KerbalMissile/Kerbal-Civilization-Project/total?style=for-the-badge&label=Downloads)
![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/t/KerbalMissile/Kerbal-Civilization-Project/main?style=for-the-badge)
![GitHub Release](https://img.shields.io/github/v/release/KerbalMissile/Kerbal-Civilization-Project?include_prereleases&style=for-the-badge)

---

**Description:**

Kerbal Civilization Project (KCP for short) is a mod that adds cities, roads, buildings to Sol all accurately placed as they appear in real life. To do so, it takes data from OpenStreetMaps (OSM) which gives info on the height, location, size, type, and even colour of the buildings. From there KCP draws those buildings in 3D, in real-time, as you go.

---

**Features:**

- Streaming (Streams tiles as you go)
- Caching (Caches tiles as you go to improve loading speed next time you see them)
- Buildings (Ex. Houses, Skyscrapers, etc.)
- Popular Landmarks:
  - Statue of Liberty
  - Calgary Tower
  - Burj Khalifa
  - Big Ben
  - Pyramids of Giza
  - Stonehenge
  - Empire State Building
  - Sydney Opera House
  - Taj Mahal
  - Christ the Redeemer
  - Colosseum
- Roads (Ex. Highways, etc.)
- Parking Lots
- Python Script (Downloads certain tiles or whole areas so you can see them in-game, quickly)
- Easter eggs on other planets
- LOD  to improve performance
- Realscale & Quarterscale support (Quarter is un-tested, should work though)

**Future Features:**
- Bridges
- City Lights
- Better building textures & models
- Traffic:
  - Cars
  - Boats
  - Planes
  - Trains
- More landmarks
- Live rocket launches (As a rocket launch happens IRL, you can see it in game)
- Regular Kerbol system support (Kerbin)
- Collisions

---

**FAQ:**

Q. Does KCP work with Mirage?

A. Yes it does!


Q. How does it work?

A. It takes building & street info (height, placement, size, etc.) from OpenStreetMaps then draws the shapes in KSP.


Q. Does KCP use Scatterer / Parallax / Kerbal Konstructs?

A. No, it uses its own system to accurately draw and place buildings, roads, and any other structures. Those systems use 3D models, KCP draws it in real time.


Q. How big is each tile?

A. Each tile is 2km x 2km

---

**Contributing:**
- Please report any bugs you may find (if you found them, I probably don't know about them)
- PR's are always welcome, same with feature suggestions

---

**Screenshots:**

Stonehenge:

<img width="1920" height="1080" alt="screenshot129" src="https://github.com/user-attachments/assets/6fba6e84-d908-4eac-b229-fee8dbb50158" />

Pyramids of Giza:

<img width="1920" height="1080" alt="screenshot127" src="https://github.com/user-attachments/assets/646d7fd2-f237-4aa2-b830-5778e15b1a10" />

Calgary:

<img width="1920" height="1080" alt="screenshot105" src="https://github.com/user-attachments/assets/6b6fdd40-49e5-42ec-b6bf-0d87a1dd4c21" />

---

**License:**

GPL-v3.0

---

**Credits:**

deltaaero had the idea first for a mod that takes OSM data and puts it in game, he is also working on a mod that does the same, except I am going in a different direction than him.

In short: The OSM data -> KSP buildings is not my idea

Here's his repo:

https://github.com/deltaspacesystems-ksp/OSMEarth
