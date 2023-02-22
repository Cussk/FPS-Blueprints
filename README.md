# FPS-Blueprints

 FPS made with Unreal Blueprints.  Character movement, mouse look and jump.  Character animation blueprints and state machines.  Attaching weapon to charcter mesh, attaching animations, sounds and vfx to shooting.  Create line trace and hit results with weapon to denote hitting targets.  
 
 Created drone enemy class that will chase player when in aggro range and explode on contact with overlap collisions.  Created patrol points and have drone cycle between them.  Added aggro on on being shot and lights color change from blue to red on aggro.  

Added UI elements health bar, crosshairs and ammo amount that update dynamically through blueprints. 

Implemented damage and health for player and drone, doing damage with weapon and taking damage from drone explosions.

Created health and ammo pickup classes to replenish resources.

Created custom game mode with enum states using UI and blueprints to change between states and denote to player game goals.  Announcement UI changing based on which gamestate player is in.  Countdown to game start.  Timer UI continuously updating to show how much time left to win.  Drone count that updates on each drone destroyed.  Game ending on player runnning out of time or health.  Player winning if all drones destroyed within time limit.
