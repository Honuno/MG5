# MG5
## Devlog
Put your Devlog here.
1. I would say a NavMesh is more useful for when characters need to navigate around a level toward destinations. Unity's navigation system can find paths through walkable areas and around obstacles, which makes it good for NPCs or point and click movement, just like this minigame assignment. I would say it's less useful when movement needs to feel directly controlled by forces, momentum, or precise physical interactions.
2. The loop should check each array entry starting at index 0 and continuing while the index is less than _birds.Length. Each pass gets one bird from the array. Then "Vector3.Distance" measures the straight line distance between the bird's position and the player's position. The "if" statement compares that distance with "_interactDistance". Now, every bird whose distance from the player is less than or equal to "_interactDistance" will run away and birds farther away will not. The Runaway call receives the player's position, so the bird knows which direction to run away.
## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
