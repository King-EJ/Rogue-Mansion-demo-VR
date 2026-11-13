# Rogue-Mansion-demo-VR
VR mod for Rogue Mansion demo will make a new mod for full release 


ROGUE MANSION VR  v0.1.11 (test build) - for Rogue Mansion Demo (Unity 2022.3, IL2CPP, BepInEx 6)
=========================================================================================

<img width="1254" height="1254" alt="Rogue Mansion_ In VR" src="https://github.com/user-attachments/assets/9ac3ee18-6ebb-43de-9f5b-194084c7c03d" />

Install
-
unzip to game folder, only tested with virtual desktop XR

The views
---------
OWN FIRST PERSON (default, [View] OwnFirstPerson): the game stays in third person, your eyes are at the player's head
(the head is hidden) and BOTH of the player's arms follow your controllers. R3 switches between it and third person.
With it off, the game's own first person is used (its arms model on the right controller), as described below.
The game's own first / third person switch is used (its button, as on a gamepad).
THIRD PERSON .. you are where the game's camera is.
FIRST PERSON .. you are at the game's first-person camera; the game's first-person ARMS / WEAPON follow your RIGHT
                controller.
Your direction is the game camera's: the right stick left / right turns it, as on a gamepad.
The left stick walks where you look (first person).

Controls (the VR controllers are a gamepad; the game's own gamepad bindings)
-------------------------------------------------------------------------
  Triggers = LT / RT, right grip = RB (dodge), left grip held = left stick is the D-pad, A B X Y, sticks, stick clicks = L3 / R3, menu button = Start
  Right stick down (first person) .. laser on / off
  Swing the RIGHT controller ...... melee attack (RT) - only while a melee weapon is in your hands
  Both stick clicks ............... re-centre;  hold both 1.2 s = VR settings menu

6DOF aim
--------
Shots and melee hits go where your right controller points (first and third person): while the game works out a shot
its camera is put on your controller. First person: the bullets leave from the controller and a red laser shows the
aim (right stick down = laser on / off). [Weapons] SixDofAim, ShotsFromController, AimPitch.
First-person arms: [Weapons] FirstPersonArmsFollow, FirstPersonArmsOffset (right, up, forward m),
FirstPersonArmsRotation (degrees) - the right hand of the game's arms is put on your controller.


Disable: to disable Mod rename winhttp.dll to winhttp.dll.bak

[VR Mod Manager](https://github.com/King-EJ/VR-Mod-Manager/releases/tag/VRModManager)

LICENSES
-
Uses Astien's OpenXR bridge. Free, non-commercial.

