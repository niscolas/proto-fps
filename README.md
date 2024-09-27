# 🎮 An Unreal 5 FPS Prototype

> 💡 This is a project made as a training for Unreal Engine, Blueprints and AI with Behavior Trees

### ✨ Features
- An extensible Weapon (Gun) Framework, allowing easy addition of new types of guns
- Guns become more inaccurate when shooting (with Crosshair Indication)
- Each Gun Type can have different damages, fire rates, innacuracy, ammo capacities and use a different type of ammo
- They also can have completely different types of bullets, like the Grenade Launcher, which isn't HitScan / LineTrace like the other guns
- Enemies that have health and can be defeated
- 

### 🌐 Maps
The project features 2 maps:

#### 🔫 Shooting Range
An area to test the guns and their features

https://github.com/user-attachments/assets/8e883fbb-3df0-4c31-8c1c-d9988bf651d5

<br/>

#### 👮 AI Patrol Area
An are to play around with an enemy patrol controlled by a Behavior Tree

##### 👁️‍🗨️ Patrolling Enemy Features
- Roam around predefined waypoints
- Hear the player's gun sounds (each gun has its own loudness, so there's a special Silenced Pistol in this map)
- Investigate the place where they heard shots coming from or where they have seen the player the last time
- Shoot the player if in sight

https://github.com/user-attachments/assets/a3564268-4d65-4269-8aa9-8a5ca3ee5600
