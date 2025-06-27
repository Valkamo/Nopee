# Nopee

Movement shooter game made in Unreal Engine 5.6.

Main Features:

Movement:
- Wallrunning
-> Forwards and Backwards
-> Wall to wall jumping
- Dashing
-> Any direction
- Double Jump

Combat:
- Shotgun
-> Reload
-> Ammo
-> Basic Animations

- Kick
-> F to kick
-> dashes to enemy
-> if speed < 1000 -> Kill enemy, little ragdoll
-> if speed > 1000 -> Kill enemy, big ragdoll
-> after kick auto dashes upwards
-> Animation missing
-> post process effect "impactframe" done

AI Enemy:
- Basic AI behavior
-> Chase player
-> Shoot player
- Basic health system
- Basic damage system
- Basic death system
- Basic ragdoll system
- Basic animation system

Save System:
- Save player data
- Load Save data
- Delete Save data
-> Timer -> Current and best time

Misc:
- Main menu -> start game, quit
- HUD
- Basic muzzle flash for weapons