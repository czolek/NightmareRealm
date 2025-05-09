
# Nightmare Realm

A simple enemy wave defence game, with basic character progression.

Each defeated enemy charges up Pylon's energy. Once it is fully charged, it explodes, destroying any remaining enemies and bestows an upgrade on player's character. Each level more enemies will spawn and more would need to be defeated to charge up the Pylon, but Player gets more powerful.

## Implementation details

 1. The game is developed fully in Blueprint.
 2. Enemies are spawned randomly in predefined places. Their number is determined by the current round.
 3. Enemies are controlled by AI Behaviour Tree.
 4. Game utilises Unreal Gameplay Framework and Save system.

### Assets
Used assets:
1. [Wizard for Battle Polyart](https://www.fab.com/pl/listings/f17e8f86-b7b2-4840-9e77-5c57bfa30764)
2. [Skeleton Knight Modular](https://www.fab.com/pl/listings/fc3a309a-a3eb-46de-bebe-dcb40dc31e48)
3. [Starcraft Protoss Pylon USB Charger](https://sketchfab.com/3d-models/starcraft-protoss-pylon-usb-charger-a49af3818bad4ca6b4ab4644e51f86b2)
4. [Spooky Tree](https://sketchfab.com/3d-models/spooky-tree-2c9d935a7709402997e8232f7a4e05b1)
5. Sounds were found on https://freesound.org

## Roadmap
Following are features that I'd like to add to the game in the future:
- [ ] More enemy types, including flying and ranged ones, possibly also powerful mini bosses
- [ ] Offensive spells, e.g. lightning (upgradeable with stun and chaining), frost (upgradeable with slowdown and eventual ability freeze, making enemies vulnerable to shatter damage), poison  dealing damage over time
- [ ] Defensive spells e.g. dodge/teleport, shield
- [ ] Skill tree - instead of gaining one predefined upgrade each level, players would be able to select one from skill tree following their own preferred build
- [ ] Enemy resistances to elements, which would need to be countered by specific spells