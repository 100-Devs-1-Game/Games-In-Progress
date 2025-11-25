**Goal**
An endless runner with optional meta-progression. During a run, the player picks upgrades for weapons and stats. References: Vampire Survivors, Risk of Rain, Megabonk.

---

## **MVP Roadmap**

### **Core / Mechanics**

* Platform: web
* Input: mouse / keyboard / touchscreen
* Player movement: left–right–forward
* Player takes damage from obstacles
* Weapons: pistol (revolver?), automatic gun
* Shooting: auto-shoot when a target is in front
* Stats:

  * health
  * regeneration
  * weapon damage
  * tackle damage
  * defence
  * dodge
  * critical chance & power
  * attack speed
  * movement speed
  * pickup radius
  * experience multiplier
  * luck
  * (and maybe more)
  * All stats must be upgradeable
* Weapon upgrades (only 1 weapon per player):

  * clone (+1 hero)
  * ricochet
  * need 4–5 solid upgrades here
* Experience & leveling:

  * each level shows an upgrade window
  * choose either a stat or a weapon upgrade
  * rarity: common / rare / epic
  * luck affects rarity chance
  * rarity only boosts numbers
* Enemies:

  * move toward player
  * avoid obstacles (and maybe other enemies)
  * drop experience
  * attack when close
  * stats: health, damage, tackle damage, movement speed, attack speed
* Enemy types:

  * ordinary zombie
  * slow tank
  * fast small zombie
* Environment:

  * procedural level generation by assembling ~10 city pieces
  * each piece contains obstacles
* Floating damage numbers

---

## **3D Art (PSX-style, simple, dark, not horror)**

**Characters:**

* ordinary zombie (with customization: small details, clothing colors)
* zombie boss
* policeman player

**Environment:**

* road
* roadside fences
* building decorations

**Obstacles:**

* anything, more is better (low priority)

---

## **Animations (Mixamo, Mesh2Motion)**

**Player:** movement, shooting (pistol + gun), taking damage, death
**Zombie:** movement, attack, death
**Extra:** blow-off-head animation on crit

---

## **UI / UX**

* HUD: experience bar, stat levels, ability upgrades
* In-world health bar
* Optional icons for upgrades + rarity
* Upgrade selection window

---

## **SFX**

* footsteps
* shooting
* taking damage & death
* zombie sounds
* experience pickup
* hover & click
* level-up
* ambient + music
