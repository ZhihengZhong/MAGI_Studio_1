# First-Person Horror Prototype (Unity)

**Author:** Zhiheng Zhong  
**Engine:** Unity (2021 or newer recommended)  
**Scripts included:**  
- `FirstPersonController.cs`  
- `DoorController.cs`  
- `FemaleGhost.cs`

---

## Project Description
This is a **small horror game prototype** made in Unity.  
It allows the player to walk around in first-person, turn a flashlight on and off, open doors, and encounter a scary ghost.  
If the ghost catches the player, the game restarts automatically.

The project is meant to show how basic horror mechanics (light, doors, being chased) can create atmosphere.

---

## Main Features
- **First-Person Controls**  
  Move with keyboard (WASD) and look around with the mouse.  

- **Flashlight Toggle**  
  Left mouse button turns the flashlight on/off.  

- **Door Interaction**  
  Walk near a door and press **Space** to open/close it.  

- **Ghost AI**  
  A ghost watches the player.  
  If you look back at it for too long, it moves closer, plays a scary sound, and may catch you.  

- **Game Restart**  
  When the ghost catches the player, the game reloads automatically after 5 seconds.  

---

## How to Play
1. Open the project in **Unity** (recommended 2021 or newer).  
2. Add the provided scripts to your **Player**, **Door**, and **Ghost** objects.  
3. Press the **Play button** in Unity to test.  
4. Controls:  
   - Move → `WASD`  
   - Look around → Mouse  
   - Flashlight → Left mouse button  
   - Open/Close Door → Space  

---

## Scripts Explained (Simple Terms)
- **FirstPersonController.cs**  
  Handles walking, looking around, flashlight toggle, and door interaction.  

- **DoorController.cs**  
  Makes doors open and close smoothly when the player presses Space nearby.  

- **FemaleGhost.cs**  
  Controls the ghost’s behavior:  
  - Watches the player  
  - Moves closer when the player looks back  
  - Plays a sound  
  - Catches the player and restarts the scene  

---

## Suggested Folder Setup
Assets/
Scripts/
FirstPersonController.cs
DoorController.cs
FemaleGhost.cs
Prefabs/
Player.prefab
Door.prefab
FemaleGhost.prefab
Scenes/
MainScene.unity
Audio/
ghost-sound.wav
