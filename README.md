# MG7
## Devlog
I put sparrow, sparrow1, sparrow2, and sparrow3 in the _sparrows array so I can check all four with the same code. In Update(), the foreach loop goes through then one at a time. The player's position and each sparrow's position are Vector3 values, which give their x, y, and z coordinates in the scene. Vector3. Distance() uses those positions to work out how far the player is from that sparrow. If the distance is 5 units or less, SetActive(true) activates it. This runs every frame,so the birds ca be activated as the player gets close to them.

## Open-Source Assets
- [Forest Nature Pack](https://kaylousberg.itch.io/kaykit-forest) - environment 3D models
- [Quirky Series](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235) - animal 3D models
