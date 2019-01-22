# Reactive-Armour-BUILT
Built 3D Mecha Hack &amp; Slash Game developed in Unity for the Games Development Practicum class for a Bachelor's in Applied Computing at the Waterford Institute of Technology.

Source code available here: https://github.com/sn1perandr3w/Reactive-Armour-SOURCE

**HOW TO RUN:**
Simply download and run Reactive Armour.exe

**DESCRIPTION:**

This game was developed in 2 week sprints with 4 prototypes. What is uploaded here is a built version of the final prototype.
It is a proof of concept which could be developed into a larger game. As a result, there is no end goal as of yet, simply two
levels which the player can explore and complete set objectives on. 

The player takes control of a giant mech (Simplistically represented at the moment. Asset design wasn't taught to me yet, unfortunately.)
who must defend a colony from an attack by an enemy force, using mechs of their own. Movement is in 3 dimensions, allowing for great
freedom in both exploration and combat.

Upon getting close to an enemy, the game will switch into a lock-on mode where the camera will keep both combatants within the screen's boundaries.
Enemies are driven by a finite-state machine using Unity's built in animator controller. As a result, they can partake in various actions such as
patrolling a set path, pursuing a player, moving to last known position of the player, attacking the player and buildings full of civilians with both
melee and ranged attacks and lastly, guarding or being stunned by player attacks. Enemies will level up with the player depending on performance, gaining more health.

The objective in the first level is to destroy generators powering a forcefield around the area the player is in. Upon doing so, they will be allowed to exit into the world map.
The second level has a much simpler objective, simply destroy all of the enemies.

There is a repair station on the first level which will restore the player's health but normally, health and ammo pickups are
either scattered across the map or dropped by enemies in single use pickups. Chances of dropping will increase when a player has
low health or ammo, adding reward to risky gameplay.

The civilians of the colony are a bonus objective which do not change anything of the game. It is simply a moral decision whether to prioritise saving them or focusing on the enemies.
I feel as though in the future, in an expanded version of this project, this could involve story elements, not necessarily labelling the player a good or bad individual. The player's own guilt
over loss of civilians will be theirs and theirs alone.


**CONTROLS:**

Movement:
WASD keys for forward/left/back/right movement.
Space/CTRL for ascending/descending.
Shift for speed boost.

Aiming:
Move the mouse to aim when out of lock-on mode.
E to switch targets in lock-on mode or reengage target if having disengaged.
Q (Hold) to disengage target in lock-on mode.

Combat-specific:
Left Mouse Button to Fire weapon.
Right Mouse Button (Hold) to guard.
Tab to switch weapons (Only two at the moment, a sword and a sniper rifle.)

Misc:
ESC to escape to the map when permitted by the game.
F1 for a debug pause (Implemented purely because of a class requirement, not really used for anything.)

**Credits:**
Game developed by Andrew Bates (https://github.com/sn1perandr3w)
Sound Effects procured from Freesound.org (https://freesound.org/)
Music written by Kevin Macleod (https://incompetech.com/)
Developed in Unity3D (https://unity3d.com/)
Code written in Unity Monodevelop (https://www.monodevelop.com/) (Now depreciated with Unity.)

**Special Thanks:** 
The lads on the server for putting up with me being gone for a month thanks to college work.
Coffee and breathmints for literally keeping me awake for the all-nighters I pulled for this.



          _____      __                                _     ____           
         / ____|    /_ |                              | |   |___ \          
        | (___  _ __ | |_ __   ___ _ __ __ _ _ __   __| |_ __ __) |_      __
         \___ \| '_ \| | '_ \ / _ \ '__/ _` | '_ \ / _` | '__|__ <\ \ /\ / /
         ____) | | | | | |_) |  __/ | | (_| | | | | (_| | |  ___) |\ V  V / 
        |_____/|_| |_|_| .__/ \___|_|  \__,_|_| |_|\__,_|_| |____/  \_/\_/  
                       | |                                                  
                       |_|                                                  


